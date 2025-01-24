# aaf-api-py
appsolve application framework fast-api starter kit  

`aaf-api-py` is a Python, Fast-API based api starter kit. Its build around best practices such as router based feature moudles.  

Some of the highlevel features  
1. Feature modules. All features are hosted in `features` folder and common code is hosted in `common` folder

### To start
Install the dependencies  
```bash
cd api
pip install -r requirements.txt
``` 

Start api  
```bash
uvicorn api:app --reload
```