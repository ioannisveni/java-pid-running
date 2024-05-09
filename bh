#!/bin/bash

count =`sudo pwdx $(pgrep java) | wc -l`
echo $count 
if [ $count -eq 5 ] then
	echo "OK: All required processes are running"
else
	echo "CRITICAL : 4 or more proccesses are not running"
fi	
