-> Open track.info in libs.tech

![VirtualBox_vsdworkshop_08_04_2024_21_18_54](https://github.com/Santhosh1901/VSD_Digital_VLSI_SoC_design/assets/66910104/dc56c48c-5387-4b3b-b5c2-83a97c215dce)

->type command help grid in tckon window and the given details

![VirtualBox_vsdworkshop_08_04_2024_21_23_43](https://github.com/Santhosh1901/VSD_Digital_VLSI_SoC_design/assets/66910104/e06cf7e0-0ebd-4bc3-afc9-8c4d26b77220)

->Now change the port names in the tckon window using commands
port class inout
port use power

port class inout
port use ground

port class input
port use signal

port class output
port use signal

->THen extract .lef file and copy it in src folder

->And also copy fast typical and slow files

->Modify config.tcl

![Screenshot (63)](https://github.com/Santhosh1901/VSD_Digital_VLSI_SoC_design/assets/66910104/a30b8ed5-a6f6-4bcf-a8a1-3b1ccba13401)

->Then run the docker in openlane and type following comments

->./flow.tcl -interactive

->package require openlane 0.9

->prep -design picorv32a

->set lefs [glob $::env(DESIGN_DIR)/src/*.lef]      

->add_lefs -src $lefs

->run_synthesis



