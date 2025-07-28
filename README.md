# touchpadNimo project for diagnotics wrt Nimo notebook touchpad being unresponsive
- Nimo model N151
- Ubuntu 24.04.02 LTS
- kernel 6.14.0-24
- 24~24.04.3-Ubuntu SMP PREEMPT_DYNAMIC

## Files
- catProcBusInpDev - result of cmd: cat /proc/bus/input/devices
- catProcBusInpDev2 - cat /proc/bus/input/devices after a reboot (to be sure
- evtestEv6 - Result in alt console of sudo evtest /dev/input/event6 
- instrucs - Ignore, this is just notes for me while collecting
- syslogTail - tail -500 /var/log/syslog > sysLogTail (this way since no Xorg.0.* as in instrucs
- xinputList - result of cmd xinput --list > xinputList

Other
- github repository:  https://github.com/MikeC711g/touchpadNimo#
- github clone: git clone https://github.com/MikeC711g/touchpadNimo.git
