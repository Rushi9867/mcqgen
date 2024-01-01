# mcq genrator
# How to run?
### Steps:
clone the repository
```bash
Project repo: https://github.com/
```
### Step 01-Create environment after opening the repository

create conda environment:
```bash
 conda create -p env python=3.8 -y
```

activate conda environment:
```bash
 source activate ./env
```

create virtual environment in vscode:
```bash
 python -m venv venv
```

activate virtual environment in vscode:
```bash
 venv/Scripts/activate
```
### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

create git repository
```bash
 git init
```
```bash
 git branch -M main
```

Run StreamlitApp.py file:
```bash
 streamlit run StreamlitApp.py
```


IN AWS:
```bash

1. first login to the AWS: 
 https://aws.amazon.com/console/

2. search about the EC2

3. You need to go launch to config the ubuntu machine

4. launch the machine 

5. update the machine
 sudo apt update

 sudo apt-get update

 sudo apt upgrade -y

 sudo apt install git curl unzip tar make sudo vim wget -y

 git clone https://github.com/Rushi9867/mcqgen.git

 touch .env

 ls -a

 vi .env

 press INSERT

  OPENAI_API_KEY="--- --------------------------------"
  esc
  :wq

  cat .env

 sudo apt install python3-pip

 pip3 install -r requirements.txt

6. Go to Instances security gruops add Edit Inbound rule

add rule 
Type - Custom TCP
Protocol - TCP
Port Range - 8501
Source - ANywhere ipv4
save rule

 python3 -m streamlit run StreamlitApp.py
```

copy public ipv4 address on main page 

--.--.--.--.:8501
