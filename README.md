# WDACBlockEDR
Repo containing prepped WDAC policies to block EDR vendors

## ⚠️ Important Disclaimer

**Local administrator rights are always required** to implement these WDAC policies. Additionally, a system reboot is often necessary for the policies to take effect.

## Usage

To block an EDR using these WDAC policies:

1. Navigate to the specific EDR folder in this repository
2. Follow the README instructions for that specific EDR which will include:
   - Required policy files to copy
   - Where to place the files on the target system
   - Any additional configuration steps needed
3. Reboot the system
4. The EDR should now be blocked from executing

Note: Each EDR may have slightly different implementation details, so always check the individual README files for the most accurate instructions.

The policies are designed to take effect after a system reboot and prevent the EDR services and components from loading.
