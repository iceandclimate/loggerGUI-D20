# loggerGUI-DL20

GUI for the DL20 borehole logger. "The AU logger"

![image of the Borehole logger](https://github.com/iceandclimate/loggerGUI-DL20/blob/main/assets/logger.png?raw=true)

Known dependencies
* python3
* PyQT5
* matplotlib
* numpy
* pyserial
* pip
* minimalmodbus

See also:
https://github.com/Aarhus-University-MPE/DL20
(updated ch340 drivers can be found here: http://www.wch-ic.com/download/CH341SER_EXE.html)


installation instructions:
- [miniconda3](https://docs.conda.io/en/latest/miniconda.html)
- conda install -c conda-forge mamba
- mamba install -c conda-forge pyqt matplotlib numpy
- mamba install -c conda-forge pyserial
- mamba install -c conda-forge pip
- pip install minimalmodbus
