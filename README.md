# class-6-rasa

Commands to be executed in Anaconda prompt:
``` python
conda create -n rasa python=3.8
conda activate rasa
pip3 install -U --user pip && pip3 install rasa
rasa --version
```

#Create a Working directory as per your requirement:
```python
# For windows user - create a folder inside the C:\Users\<username> with foldername as  --> class-6-rasa
cd class-6-rasa
pip3 install rasa[spacy] --user
python3 -m spacy download en_core_web_md
#if above line failes - run below line
python -m spacy download en_core_web_md
rasa init
/stop

--
# Optional Step:
- Download & install VS code : https://code.visualstudio.com/download
- Download & install Git : https://git-scm.com/downloads
- Start Vs code and select Terminal on Top

```