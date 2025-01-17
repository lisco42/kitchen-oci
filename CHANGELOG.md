# kitchen-oci CHANGELOG

# 1.14.0
- feat: add optional parameter `defined_tags`
- 

# 1.13.0
- feat: add Network Security Group support
- feat: add support for attaching multiple volumes

## 1.12.3
- feat: add support for specifying compartment by name

## 1.12.1
- Refactor `oci_config` method to account for `warning: Using the last argument as keyword parameters is deprecated` deprecation warning
- Set dependency on oci gem to 2.15.0

## 1.12.0
- Added support for Flex and Preemptible instances
- Set dependency on oci gem to 2.14.0
- Further reduction of characters known to cause winrm password issues

## 1.11.2
- Set dependency on oci gem to 2.10.0

## 1.11.1
- Removed characters from password string known to break winrm

## 1.11.0
- Added support for user_data raw string

## 1.10.1 Issue 22
- Added safeguard for cluster_name length restriction in DBaaS.

## 1.10.0 DBaaS support
- Added support for DBaaS.
  - instance_type is new optional parameter (compute or dbaas)

## 1.9.0 Use instance principals
- Added support for `use_instance_principals`

## 1.8.0 Freeform tags
- Added optional parameter `freeform_tags`

## 1.6.0 WinRM password option
- Added option to set winrm password, instead of randomly generating one

## 1.5.0 Windows support

- Added cloud-init support.
- Added support for Windows targets.
  - Can inject powershell script to set a random password and enable WinRM
