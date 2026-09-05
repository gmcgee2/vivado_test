# Windows
1. Add vivado to your PATH (https://windowsloop.com/how-to-add-to-windows-path/). If you installed to the default location, just add ``C:\Xilinx\Vivado\2025.2\bin``. After doing this, open a terminal and run ``vivado -version`` to make sure it is working.
2. Clone this repo.
3. Open a terminal in the project folder and run ``vivado -mode batch -source test_create.tcl``.
4. Go into vivado, open project, go to the ``testproj`` folder that was just made and open ``testproj.xpr``.
5. Generate the bitstream and test it on your board. An LED should light up with each switch.



# Linux
1. Add settings64.sh to ~/.bashrc by adding ``source /<Your Vivado Install Path>/Vivado/2025.2/Vivado/settings64.sh`` to the end of the file and reopen your terminal. Run ``vivado -version`` to make sure it is working.
2. Clone this repo.
3. cd into the project folder and run ``vivado -mode batch -source test_create.tcl``.
4. Go into vivado, open project, go to the ``testproj`` folder that was just made and open ``testproj.xpr``.
5. Generate the bitstream and test it on your board. An LED should light up with each switch.
