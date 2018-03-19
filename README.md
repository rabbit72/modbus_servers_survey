# Modbus servers survey
This script request servers and output data in file <now_datetime>.xlsx.

# How to install
Python 2.7 should be already installed. Then use pip to install dependencies:

```bash
$ pip install -r requirements.txt
```
# Quick start

```bash
$ python modbus_servers_survey.py
```

Running on Windows is similar.

# Format hosts
*IP,name_server*
```127.0.0.1,565_SGP
127.0.0.1,587_SGP
127.0.0.1,678_SGP
127.0.0.1,688_SGP
127.0.0.1,896_SGP
```

