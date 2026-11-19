# Fastapi 
# step 1
activate env and install fastapi
```bash
python -m venv .venv
```
activate it
```bash
.venv\Scripts\Activate.ps1
```
install this
```bash
pip install uv
uv init FILE_NAME
cd FILENAME
uv add "fastapi[standard]"
```
now open it in vs code 
```bash
code .
```
all the stuff in main.py
# step 2
the content is in main.py we are basically just making a normal application with hello world 
```bash
uv run fastapi dev main.py
```
two types 
1. fastapi dev
2. fastapi run
dev mode will automatically reload the changes done in the server, for good performance use run
<br>
this returns the json format output
# for better version of the output 

```bash
LINK/docs
```
# redoc

```bash
LINK/redoc
```
# now we are trying to convert list of array to json format 
make a decorator and return the list of array , making that into different path /api/posts you can give any name uh want /apime/posts anything
# add html front page 
in main.py uuh will get to know 




