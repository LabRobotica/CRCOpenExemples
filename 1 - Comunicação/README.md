##Exemplo Comunicação 

Esse exemplo tem como objetivo mostrar como se compila um codigo no LPC para C5GOpen com uso da eORL.

#Para baixar o codigo

$ git clone https://github.com/labrobotica/ExemplosC5GOPEN.git

#Compilação

$ cd 1-Comunicação
$ cmake .
$ make

# Execução

$ sudo ./main

#Saida Desejada

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
Loop Loop Loop Loop Loop Loop Loop Loop Loop {Etc Etc Etc} 
[F] ORLOPEN_StopCommunication
Synchronous data thread is terminating...

[F] ORL_terminate_controller