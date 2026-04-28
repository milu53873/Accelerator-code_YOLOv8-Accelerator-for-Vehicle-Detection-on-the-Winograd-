# Accelerator-code_YOLOv8-Accelerator-for-Vehicle-Detection-on-the-Winograd-
TOP: CONV.v   

     └─ winograd2d.v
     
        └─ A_y_A.v
        
           ├─ B_x_B.v
           
           └─ G_w_G.v
          
testbench: testfixture.v

跑testbench:
ncverilog CONV.v testfixture.v

