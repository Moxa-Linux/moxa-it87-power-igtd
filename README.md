# moxa-power-igtd

Power ignition management is the controller that manages power distribution to\
in-vehicle computers by receiving signals when starting the ignition system of\
transportation vehicles.

## Config example
- PWR_IGT_PIN: the super IO gpio pin number of power ignition, e.g. GP85
- PWR_IGT_SIG_OFF_VAL: the power ignition signal off status
- PWR_IGT_DELAY_SEC: the delay time (sec) of daemon

edit: `/etc/moxa-configs/moxa-power-igtd.conf`
```
PWR_IGT_PIN=85
PWR_IGT_SIG_OFF_VAL=0
PWR_IGT_DELAY_SEC=1
```
