# raspi_ble_gamepad
Configure a Raspberry Pi 4 as a BLE gamepad


## Configlueration

```
sudo hciconfig hci0 class 0x002508

sudo hciconfig hci0 piscan
```

Run `sudo bluetoothctl`
...then input this'n here at the prompts:

`power on`
  Changing power on succeeded

`discoverable on`
  Changing discoverable on succeeded

`pairable on`
  Changing pairable on succeeded

`agent NoInputNoOutput`
  Agent is already registered

`default-agent`
  Default agent request successful

`exit`

