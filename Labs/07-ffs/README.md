# Lab 7: Latches and Flip-flops

## Lab assignment

1. Preparation tasks (done before the lab at home). 
    * Characteristic equations and completed tables for D, JK, T flip-flops.
   
   **q**n+1 = **d**
   

   | **clk** | **d** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 0 | 0  | no change |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 1 | 0 | change |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 1 | 1 | no change |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 0 | 1 | change |

   | **clk** | **j** | **k** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-: | :-- |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 0 | 0 | 0 | No change |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 0 | 1 | 1 | No change |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 1 | 0 | 0 | reset |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 1 | 1 | 0 | reset |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 0 | 0 | 1 | set |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 0 | 1 | 1 | set |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 1 | 0 | 1 | toggle |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 1 | 1 | 0 | toggle |

   | **clk** | **t** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 0 | 0 | no change |
   | ![rising](IMAGES/eq_uparrow.png) | 0 | 1 | 1 | no change |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 0 | 1 | toggle |
   | ![rising](IMAGES/eq_uparrow.png) | 1 | 1 | 0 | toggle |
    

2. D latch.
    * VHDL code listing of the process `p_d_latch` with syntax highlighting,
    


    * Listing of VHDL reset and stimulus processes from the testbench `tb_d_latch` file with syntax highlighting and asserts,
    
    
    * Screenshot with simulated time waveforms; always display all inputs and outputs. The full functionality of the entity must be verified.



3. Flip-flops.
    * VHDL code listing of the processes `p_d_ff_arst`, `p_d_ff_rst`, `p_jk_ff_rst`, `p_t_ff_rst` with syntax highlighting,
    
    
    * Listing of VHDL clock, reset and stimulus processes from the testbench files with syntax highlighting and asserts,
    
    
    * Screenshot, with simulated time waveforms; always display all inputs and outputs. The full functionality of the entities must be verified.




4. Shift register.
    * Image of the shift register schematic. The image can be drawn on a computer or by hand. Name all inputs, outputs, components and internal signals.

