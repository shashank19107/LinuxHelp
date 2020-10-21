# LinuxHelp
Some starting linux files
this repository contains Sublime builds for linux, both with input and output files and also command line executions.

******** Most Important (Wifi drivers for lenovo Linux) (Realtek RTL8822BE)*********
steps to follow:
>>> clone lwfinger-rtlwifi-new
>>> make using command $./make
>>> install using sudo ./make install
>>> sudo modprobe -r rtw_8822be
>>>sudo modprobe rtw_8822be
>>>reboot



If the above steps don't help:
>>> another folder named r8822be in this repo
>>>commands to follow
$cd r8822be
$./make
$sudo ./make install
$sudo modprobe -r rtw_8822be
$sudo modprobe rtw_8822be

NOTE: last kernel for which it worked is 5.0.51.0 (genric)


