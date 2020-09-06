# shakti-e-class-pre-built-mcs
This repository has a snapshot of the MCS file built for the Shakti e-class processor when running on the Arty-35 kit.

The snapshot was taken on 06/09/2020 with the master git repository source of Shakti E-Class and has no intent of being upto date, please use this with care.



To use this repository, simply clone it with 

```
git clone https://github.com/sreeharshaangara/shakti-e-class-pre-built-mcs.git
```



With Xilinx Vivado 2018.3 installed, In your command-line,  please enter,

```
vivado -nojournal -nolog -mode tcl -source tcl/program_mcs_arty_a7_spansion.tcl
```



Once you successfully program, you will be able to see the Shakti logo via UART with baud 19200