# Changelog

## [Unreleased]

### Added

- Add FDCAN support for Zest_Core_STM32H753ZI.

### Changed

- Rename `zest_sensor_p_t_rh` shield to `zest_sensor-p-t-rh`.
- Fix SX1272 configuration for Zest_Core_FMLR-72.
- Fix button code for Zest_Core_nrF5340.

## [3.7.0+202412] - 20241204

### Added

- Add ADC support for all Zest_Core using `sixtron-adc`.
- Add BNO055 and IIS2DLPC support on Zest_Sensor_IMU.
- Add PWM support for all Zest_Core using `sixtron-pwm`.
- Add SPI chip select definition for Zest_Core_nRF5340, Zest_Core_nRF52832.
- Add `sixtron-adc` and `sixtron-pwm` bindings.
- Add flash partitions and Ethernet definition for Zest_Core_STM32H753ZI.
- Add support for Bosch BNO055 sensor driver.
- Add support for ILITEK ILI9163C display driver.
- Add support for Maxim MAX17201 fuel gauge driver.
- Add support for Microcrystal AG RV-8803-C7 rtc driver.
- Add support for Quectel L86 modem driver.
- Add support for Texas Instruments TSC2003 touchscreen driver.
- Add support for Zest_Adapter_Click.
- Add support for Zest_Battery_LiPo.
- Add support for Zest_Display_LCD.
- Add support for Zest_Core_STM32L4A6RG v3.0.0.
- Add support for Zest_Core_nRF52832 v1.1.0.
- Add support for Zest_Core_nRF5340.
- Add support for Zest_Interface_RS232.
- Add support for Zest_Interface_RS485.
- Add support for Zest_RTC_RV-8803-C7.
- Add support for Zest_Storage_microSD.
- Add support for input subsystem on all Zest_Core.

### Changed

- Fix button polarity for all Zest_Core.
- Fix configuration in HTU21D driver.
- Fix compatible for shield Zest_Radio_GNSS.
- Fix Ethernet definition for Zest_Interface_Ethernet.
- Fix fdcan bus-speed deprecated properties for Zest_Core_STM32G474VE.
- Fix I2C device on sixtron bus for Zest_Core_nRF5340.
- Fix LoRa definition for Zest_Radio_LoRa868.
- Fix PWM definition for Zest_Core_STM32L4A6RG.
- Fix sensor definition for Zest_Sensor_P-T-RH.
- Fix UART configuration for Zest_Core_nRF5340.
- Fix Z_Motion BLE configuration.
- Rename ICAP pin names to ICAPT.

## [3.7.0+202408] - 20240809

### Added

- Add support for Z_Motion.

### Changed

- Support Zephyr OS 3.7.0.
- Update Zest_Core_FMLR-72 driver to Zephyr hardware model v2.
- Update Zest_Core_STM32G474VE driver to Zephyr hardware model v2.
- Update Zest_Core_STM32H753ZI driver to Zephyr hardware model v2.
- Update Zest_Core_STM32L4A6RG driver to Zephyr hardware model v2.
- Update Zest_Core_STM32L562VE driver to Zephyr hardware model v2.
- Update Zest_Core_nRF52832 driver to Zephyr hardware model v2.
- Update Z_IAQ board to Zephyr hardware model v2.
- Update AMS AS621x driver to Zephyr hardware model v2.
- Update Honeywell HPMA115 driver to Zephyr hardware model v2.
- Update Microchip MCP3425 driver to Zephyr hardware model v2.
- Update Omron 2SMPB-02E driver to Zephyr hardware model v2.
- Update Sensirion SCD4x driver to Zephyr hardware model v2.
- Update TE Connectivity HTU21D driver to Zephyr hardware model v2.

## [3.6.0+202407] - 20240703

### Added

- Add support for Zest_Core_FMLR-72.
- Add support for Zest_Core_STM32H753ZI.
- Add support for Zest_Core_STM32L562VE.
- Add support for shield Zest_Interface_Ethernet.
- Add support for shield Zest_Radio_GNSS.
- Add support for shield Zest_Radio_LoRa868.
- Add missing pre-commit configuration for Zest_Core_STM32L4A6RG.
- Add `sixtron_connector` label for Zest_Core_STM32L4A6RG.
- Add Zest_Core_STM32L4A6RG metadata for test runner.
- Add README for shield Zest_Radio_GNSS.

### Changed

- Fix Honeywell HPMA115 driver initialization.
- Update pre-commit configuration for shield Zest_Radio_GNSS.

## [3.6.0+202404] - 20240426

### Added

- Add support for Zest_Core_nRF52832.
- Add support for Zest_Core_STM32G474VE.
- Add support for Z_IAQ.
- Add support for Microchip MCP3425 ADC.
- Add support for Omron 2SMPB-02E pressure sensor.
- Add 2SMBP-02E pressure sensor driver to Zest_Sensor_P-T-RH.
- Add DS18B20 temperature sensor driver to Zest_Sensor_P-T-RH.
- Add CI to auto update the manifest.

## [3.5.0+202402] - 20240221

_Initial release._

[3.5.0+202402]: https://github.com/catie-aq/zephyr_6tron-manifest/releases/tag/v3.5.0+202402
[3.6.0+202404]: https://github.com/catie-aq/zephyr_6tron-manifest/releases/tag/v3.6.0+202404
[3.6.0+202407]: https://github.com/catie-aq/zephyr_6tron-manifest/releases/tag/v3.6.0+202407
[3.7.0+202408]: https://github.com/catie-aq/zephyr_6tron-manifest/releases/tag/v3.7.0+202408
[3.7.0+202412]: https://github.com/catie-aq/zephyr_6tron-manifest/releases/tag/v3.7.0+202412
