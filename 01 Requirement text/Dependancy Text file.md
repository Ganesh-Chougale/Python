## Create a text file 
```bash
touch requirements.txt
```  
## write all dependancies here  
```txt
requests==2.31.0
flask==2.3.3
numpy>=1.24
```  
## Install all dependancies  
```bash
pip install -r requirements.txt
```  
## To create text file based on existing environment  
```bash
pip freeze > requirements.txt
```  