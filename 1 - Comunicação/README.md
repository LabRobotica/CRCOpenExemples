# Exemplo Comunicação

## Descrição

Exemplo comentado com o minimo de funções necessarias para iniciar e finalizar uma comunicação entre o LPC e CRC fazendo uso da biblioteca eORL fornecida pela Comau.

Esse README tem como objetivo mostrar como se compila um codigo no LPC para C5GOpen com uso da eORL.

## Para baixar o código

    $git clone https://github.com/labrobotica/ExemplosC5GOPEN.git

## Para compilar o código

    $cd 1-Comunicação
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

    [F] ORLOPEN_set_period
    [ORL][#00][#00] ORL_set_interpolation_time (16.000000 msec): Status => [0] - The service is successful.
    [ORL][#00] ORLOPEN_set_period (ORL_16_0_MILLIS): Status => [0] - The service is successful.

    [F] ORLOPEN_SetCallBackFunction

    [F] ORLOPEN_StartCommunication
    Synchronous data thread is starting...
    Loop Loop Loop Loop Loop Loop Loop Loop Loop {Etc} 
    [F] ORLOPEN_StopCommunication
    Synchronous data thread is terminating...

    [F] ORL_terminate_controller
