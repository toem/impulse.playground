<img src="impulse.png" width="256px" >

# impulse playground

[**impulse**](https://toem.de/index.php/products/impulse) is an event and waveform visualization and analysis workbench (simulation, traces, logs) which helps engineers to comfortably understand and debug complex semiconductor and multi-core software systems.

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/toem/playground)

## Play with gitpod

Just enter [https://www.gitpod.io#https://github.com/toem/impulse.playground](https://www.gitpod.io#https://github.com/toem/impulse.playground) into your browser and log-in with your github account.

## Quick Start

* Select a file to view.
* Use the context menus 'Open with' and select the impulse Viewer (You may select the impulse Viewer as the default option at this point).
* On activation, it may take a while (a few secs) to load the backend java server. The OS may ask you for approval.
* Create a new view.
* Open the 'Samples panel' to examine the signal details. 
* Have fun !

https://user-images.githubusercontent.com/9350222/127842523-0da465e4-77aa-49ab-9b9e-2e72a6fe2838.mp4

## Core files

* recMl/ recMZ

    impulse main xml based signal format (un-compressed/compressed).

* recJs (Script)

    recJs files are signal script files. You might prepare signal references, define test vectors for your design or script a custom reader. Everything is based on the same simple api that is used in signal scripts and serializer.

* flux (flux trace)

    recTr (flux) is an open trace format. Emitters can be downloaded in source form from toem git hub or imported with from eclipse.

* VCD files

    The Verilog Value Change Dump can be seen as a standard format and is supported.

## VP files

* TAB
    The Analog Tabular Format (TAB) is used in SystemC AMS systems. The format uses pure text and stores the numeric values in columns similar to CSV. 

* SCV
    The SCV (SystemC Transaction DB) format is used by the default transaction db writer of the SystemC Verification Library (TLM transactions).

## Spice files

* RAW
    The Spice 3 format is a format for dump files generated by analog electronic circuit simulation tools. Spice 3 is an open source circuit simulation program for nonlinear DC, nonlinear transient and linear AC analyses.


## more to come ....

* Logging
* Realtime OS traces
* HDL Simulator outputs
* CTF and other trace formats
