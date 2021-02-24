# monograph_test
This repository contains additional materials for monograph "..."  
You have 2 options:
- clone this repository and use your own execution environment to run code
- clone this repository, download prepared execution environment built using jupyter notebook and run this code

# Instruction for 2nd option
Environment supports **only** 32bit and 64bit versions of Windows 10 and web-browsers Firefox, Chrome, Safari.  
To unpack environment archive you should have installed 7z or WinRAR tool in your system

### Cloning repository as zip archive
![Clone repo help image](ReadMePics/clone_repo.png)

### Download execution environment from the following link
[Download environment](https://drive.google.com/file/d/1kiq_l-r7EfCqmrfZKh_yAmi4dLfqbDKp/view?usp=sharing)

After you downloaded archive unpack it in any directory on your computer.  
Copy notebook (file with .ipynb extension) and directory *data* from this repository into *notebooks* directory inside environment directory.  
Run batch file *run_jupyter_lab.bat* from environment directory.  
Jupyter lab will open in your browser. Select desired notebook in the left side of the page.

# How to use your own data with this code
This program allow you to pas data only in files with *.npy* extension.  
If you have data in txt format you can convert it to npy format with *Converter.ipynb* and after pas your converted data to any example.  

## Format of txt file
All txt files should be placed in *txt_data* directory. Directory *txt_data* should be placed in the same directory as *Converter.ipynb* notebook. One file contains all spectra of one class.  
Program expects txt files with next format. Each column of file contains one spectrum. Columns separated with comma sign *,*. Values are represented in E-notation.  
![Txt data format image](ReadMePics/txt_data_format.png)  
  
Example
2.4e-04,3.2e-04, ... 4.2e-04  
2.3e-04,3.2e-04, ... 4.4e-04  
  
...
  
2.3e-04,3.1e-04, ... 4.1e-04  

## Format of npy file
