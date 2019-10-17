# Exemplo de Uso da Modalidade Listen

## Descrição

Exemplo comentado com o minimo de funções necessarias para iniciar e finalizar uma comunicação entre o LPC e CRC (fazendo uso da biblioteca eORL fornecida pela Comau), e para fazer uso da modalidade Listen.

Esse README tem como objetivo mostrar como baixa o codigo fonte, compilar o codigo no LPC para C5GOpen com uso da eORL, e executar.

## Para baixar o código

    $git clone https://github.com/labrobotica/ExemplosC5GOPEN.git

## Para compilar o código

    $cd ExemplosC5GOPEN
    $cd '2 - Listen'
    $cmake .
    $make

## Para executar o código

    #./main
ou

    $sudo ./main

## Saída Desejada

    Connection to 192.168.29.2: CNTRLC5G_2213436.c5g

    [F] ORLOPEN_initialize_controller

                    *----------------------------------------*
                    |      ORL C5G Software licensed to:     |
                                    <  >
                    |               2015-09-17               |
                    |           All Rights Reserved          |
                    |             Copyright 2013             |
                    |              Comau S.P.A.              |
                    *----------------------------------------*

    [ORL] C5G Open realistic Robot Library (ORL) correctly initialized!
    192.168.29.2: CNTRLC5G_2213436.c5g OK

    [...]
