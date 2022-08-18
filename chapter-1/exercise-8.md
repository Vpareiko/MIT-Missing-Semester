** Write a command that reads out your laptop battery’s power level or your desktop machine’s CPU temperature from
/sys. Note: if you’re a macOS user, your OS doesn’t have sysfs, so you can skip this exercise. **
* `sudo apt install acpi` -> `acpi -b > current-battery-charge.txt` -> `cat current-battery-charge.txt`