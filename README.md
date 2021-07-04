```sh
cd iseproj/fpga_hf
xtclsh
% source fpga_hf.tcl
% run_process
% exit
mv fpga_hf.bit ../..
git reset --hard
git clean -dfx .
cd ../..
```
