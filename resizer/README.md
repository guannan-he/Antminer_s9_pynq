# requirements:  
ver(pynq) >= 2.5  
run code below to update your pynq  
`sudo pip3 install --upgrade pynq`  
# how to use:  
1. copy ./resizer folder to ~/pynq/overlays/  
2. copy ./demo_resizer folder tp ~/jupyter_notebooks/  
* use ps to resize picture:  
open your jupyter web console and run /demo_base/resizer_ps.ipynb  
average execute time is around 1000ms  
* use pl to resize picture:  
open your jupyter web console and run /demo_base/resizer_pl.ipynb  
average execute time is around 300ms  
# project detail:  
./s9_pynq_resizer.7z is this project folder  
./ip is the official IPcore  
#references:  
[base.bit and base.hwh](https://github.com/kangyuzhe666/zynq7010-pynq-2.5)
[IPcore, resizer_ps.ipynb, resizer_pl.ipynb ](https://github.com/Xilinx/PYNQ-HelloWorld)