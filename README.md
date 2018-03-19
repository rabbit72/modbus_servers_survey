# Modbus servers survey
This script request servers and output data in file <now_datetime>.xlsx.

# How to install
Python 3 should be already installed. Then use pip (or pip3 if there is a conflict with old Python 2 setup) to install dependencies:

```bash
$ pip install -r requirements.txt
```
# Quick start

```bash
$ python3 modbus_servers_survey.py
```

Running on Windows is similar.

*(Possibly requires call of 'python' executive instead of just 'python3'.)*

# Format hosts
*IP,name_server*
```127.0.0.1,565_SGP
127.0.0.1,587_SGP
127.0.0.1,678_SGP
127.0.0.1,688_SGP
127.0.0.1,896_SGP
```

