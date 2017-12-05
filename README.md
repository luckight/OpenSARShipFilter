# OpenSARShipFilter

///////////////////////////////////////////////////////////////////////////////
OpenSARShipFilter is a tool used to filter the OpenSARShip dataset to acquire specified ships conveniently for your researches. 
OpenSARShipFilter is developed and maintained by EasySAR interest group. 
EasySAR interest group is dedicated to the easy use of SAR data.
The OpenSARShip dataset provided by Shanghai Jiaotong University can be downloaded freely from http://opensar.sjtu.edu.cn/

If you have used this tool in your research, please cite our work.
Reference: 
X. Leng,etc.On Noncircularity of Sea Surface in Single-Channel Synthetic Aperture Radar Imagery,IEEE TGRS, in previewing.

Contact Email: luckight@163.com, kangmiao15@163.com, lzkmylz@163.com
///////////////////////////////////////////////////////////////////////////////

1. Prerequisites

. Verify the MATLAB Compiler Runtime (MCR) is installed and ensure you have installed version 8.3 (R2014a).   

. If the MCR is not installed, do the following:
  (1) enter
  
      >>mcrinstaller
      
      at MATLAB prompt. The MCRINSTALLER command displays the location of the MCR Installer.

  (2) run the MCR Installer.

Or download the Windows 64-bit version of the MCR for R2014a from the MathWorks Web site by navigating to http://www.mathworks.com/products/compiler/mcr/index.html

2. Run

Put the OpenSARShipFilter.exe into the folder containing 'Ship.xml', which is unzipped from the OpenSARShip dataset. The unzipped folder contains files 'Ship.xml', 'Metedata.xml', 'ReadMe.pdf', folders 'Patch','Patch_Cal','Patch_RGB', 'Patch_Uint8' usually.

Then click OpenSARshipFilter.exe, input filtering conditions (length, width,incidence, head, length error ratio), run and get the fitered results.
