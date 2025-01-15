# Hardware Used
NRF5284DK was used to test the BLE firmware

# IDE Used
NRF connect for Visual Studio Code was used to debug the firmware

# SDK
NRF SDK 2.5.0 was used to develop the firmware

# BLE_Firmware
Firmware is one of the examples from https://academy.nordicsemi.com/courses/bluetooth-low-energy-fundamentals/. Firmware contains following things:
* A custom GATT service which contains 2 characteristics, one for LED and one for Button
* Button characteristic has read and notify operations associated with it and LED characteristic has write operation associated with it
* LED characteristic requires pairing with Authentication, this makes the security level to 3 or 4 depending upon if you are using legacy pairing or LE Secure Connections
