## Q1: What is the  best practice for index?
### A1: "%{[@metadata][beat]}-%{[@metadata][version]}-%{[processor][event]}-%{+yyyy.MM.dd}" }

## Q2: If I want to avoid the new line in log file like ERR, SEVERE in LOGLEVEL, what is can edit in filebeat config file?
### A2: all line in log file, don't express all records in the document
