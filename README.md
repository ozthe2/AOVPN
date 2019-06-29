# AOVPN
My PowerShell scripts for AOVPN


## Start-AOVPN
A function that attempts to reconnect to the AOVPN based on 2 criteria:
- The device is not domain authenticated
- The AOVPN connection is no longer connected.

Use this function in a scheduled task that has triggers based on various event ID's such as waking from sleep, network change etc etc.
