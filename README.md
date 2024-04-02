![Screenshot (59)](https://github.com/Santhosh1901/VSD_Digital_VLSI_SoC_design/assets/66910104/3ea3acd3-ae7d-42aa-b966-2469d3936181)
-> The internal structure of a package contains various macros and foundry ip's.

-> In order to communicate between softwares or programs to a chip,  the programs are first converted to assembly level language(RISC V assembly program).

-> The assmbly program in turn converts the assembly level to machine level codes i.e. 1's and 0's, so as to execute a program and get desired output.
![Screenshot (60)](https://github.com/Santhosh1901/VSD_Digital_VLSI_SoC_design/assets/66910104/d7f35262-48f7-482c-9de3-02c6b105e1d1)

                                                                 ***************INTRODUCTION TO OPLENLANE***************

-> For designing a ASIC we need RTL code, EDA tools and PDKs since RTL codes for designs are available to us from github,google, etc. We need EDA tools to synthesize and thats where OPENLANE comes into picture where it is completely automated without any human intervention.

-> For process design kit that is for taping out we use SKYWATER 130nm which is also opensource.

![Screenshot (61)](https://github.com/Santhosh1901/VSD_Digital_VLSI_SoC_design/assets/66910104/73e36abe-50a1-4599-a820-75be2d141ae1)


                                                                    ***************OPENLANE DESIGN FLOW***************

-> When synthesis_run command is exexcuted the design is synthesized.

-> From the final synthesis statistic report we obtain the Flop Ratio which is equal to No Of DFF/Total No of Cells





