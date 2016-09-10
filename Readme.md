# Power-On Script for a telnet enable power device

This script is a simple telnet script that send some command to a device that switches on certain power ports on the device

*IP-Power Commands*
lets take a look at this command here --> 'cmd1=setpower=11110000'
~~~~~~~~
'cmd1=setpower=11110000'
~~~~~~~~

  - cmd1 is a variable that I define in the script.
  - setpower is  a command on the IP-Power device
  - the 8 digit number is how you would togle the logice switches on the device. 1 means on and 0 is off
  - the first 4 digits are the only digits that togle the 4 ports on the switch in respective order.
  - the last four digits mean nothing but have to be sent in the command for the device not to error.
