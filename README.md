# MacBook-NoBattery-FrequencyFix

Removing the battery from your MacBook results in the machine running at its lowest frequency. There is a very good guide on how to solve this issue [here](https://portugnole.blogspot.com/2020/05/running-macbook-without-battery-lets-go.html?m=1) however it does not cover how to carry the procedure under MacOS Big Sur.

The procedure is as follows:

1. Disable FileVault 
1. Disable SIP and authenticated root
1. Remove IOPlatformPluginFamily.kext
1. Install CPUTune
