# Communication Example

## Description

Example commented with the minimum of functions required to initiate and terminate communication between LPC and CRC using the eORL library provided by Comau.

This README aims to show how to compile a LPC code for C5GOpen using eORL.

## To download the code and go to folder

    git clone https://github.com/labrobotica/CRCOpenExemples.git && cd 'CRCOpenExemples/1 - Communication'

## To compile code

    cmake. && make

## To run the code

    sudo ./main

## Desired Exit

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
