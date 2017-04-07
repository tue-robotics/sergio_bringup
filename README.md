# sergio_bringup
Launch, machine and parameter files required to bringup the SERGIO robot

## UDEV RULES FOR HOKUYO ON SERGIO3

sudo chmod a+rw /dev/ttyACM0
sudo chmod a+rw /dev/ttyACM1

    ATTRS{manufacturer}=="Hokuyo Data Flex for USB", SYMLINK+="sensors/hokuyo_busid_%b"

Make sure you check the USB bus-id of each laser

## Torso calibration
Follow steps in: [sergio_torso_calibration](../../../sergio_torso_calibration)
