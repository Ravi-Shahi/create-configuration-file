# Ansible-create-configuration-file

## Description

Welcome Developers, This playbook helps you to create a configuration file with the help of raw data passed by user using delimeters:-
 - '|' for set of data 
 - ';' for individaul data which can be port, machine etc.

## Mandatory Variables
The first value and last value after split using ';' are mandatory values, if this data is absent set of data will be skipped
