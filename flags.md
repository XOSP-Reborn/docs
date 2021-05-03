### SoniUI Specific Build flags ### 

#### soni.mk:  ####

- Source our custom product configuration by: 

`  $(call inherit-product, vendor/soni/config/common_full_phone.mk) `

- Our lunch command is `soni_device` .

- If you need to debug (enable ADB on Boot), make an eng build or export ` TARGET_DEBUG_ENABLE=true`.

- Overlay maintainer name and Telegram link [here](https://github.com/JamieHoSzeYui/android_device_xiaomi_rosy/commit/f29c2f11d2a0ad0cccd1e2e432a58db131c78d2c)

Note that we might change our lunch command. Stay tuned.
