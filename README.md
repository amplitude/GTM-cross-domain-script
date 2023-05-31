# GTM-cross-domain-script

This repository provides a script to use the Amplitude Analytics Browser SDK GTM template for cross-domain tracking.

## Description

This script allows users to track user activity across different domains seamlessly and provides useful insights for the growth of your business.

## Prerequisites

- You are required to create a Custom HTML type tag and copy the code snippet in your GTM.

- This script is specifically tailored for using the Amplitude Analytics Browser SDK GTM with the default instance.
  - If you are using a tag with a custom instance name, please use `amplitudeGTM._iq["your-instance-name"]`.
  - For Amplitude Analytics Legacy
    - You need to enable deviceIdFromUrlParam. Please set `deviceIdFromUrlParam = true` during configuration
    - You can use`amplitude.getInstance()` or `amplitude.getInstance('your-instance-name')` if you have customized instance name.
    - `amp_device_id` is designated as the parameter key for deviceId within the URL. Please use `amp_device_id` instead of `deviceId` for legacy GTM template.

## License

This project is licensed under the terms of the MIT license.
