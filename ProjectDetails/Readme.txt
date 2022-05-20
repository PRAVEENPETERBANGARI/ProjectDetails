Step 1:
Import the files  from github using the command

!git clone (link of github code)
%cd file_name

Example:
!git clone  https://github.com/sldeep/SLDeep
%cd train.ipynb

Step 2:
Run the below command for uploading dataset from drive

from google.colab import drive
drive.mount('/content/drive')

Step 3:
Upload the utils in content folder 
Utils contains files i.e
1.cpp.py
2.lex.py
3.yacc.py
Example:
from utils import lex
from utils import yacc
from utils import cpp

Step 4: Set path for dataset from drive
Example:
zip_name = "/content/drive/MyDrive/SLDEEP/data(10kfiles).zip"
# The Archive Containing The Actual Codes
archive = zipfile.ZipFile('/content/drive/MyDrive/SLDEEP/data(10kfiles).zip', 'r')

Step 4: Execute the source code 