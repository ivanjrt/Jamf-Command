# Jamf-Cheat Sheet
sudo is required to have full authorothy on running the commmand as root
-verbose  switch will show the command being run with the required Info


# Help on jamf commands
``` ruby
jamf help
```

# Checks	for	policies check-in
you will find the ID of the policy on the URL of it
``` ruby
jamf policy
jamf policy -id 25
```

# Update the inventory
``` ruby
jamf recon
```

# Checks for Jamf Version
``` ruby
jamf about
```

# Install a package
``` ruby
jamf installs
```

# Enrolls	this	machine
``` ruby
jamf enroll
```

# Reboots	the	computer
``` ruby
jamf reboot
```

# Uninstall the JAMF agent  -- Quit the appplication first on processes
``` ruby
jamf –removeFramework
```

# Removes	the	jamf	MDM	profile -- Quit the appplication first on processes
``` ruby
jamf removeMdmProfile
```

# Collecting logs to check for JAMF
collect logs from these locations:
```
/private/var/log/install.log* 
/private/var/log/jamf.log
/private/var/log/system.log* 
```
# Checking on Processes on a MAC
``` ruby
top
```
or use Activity Monitor <br/>
![image](https://user-images.githubusercontent.com/44326428/170172842-7d1c6625-dcf0-4dc6-81f5-f0c7a2dbb473.png) 

<br/>
<br/>
# Connecting Jamf Pro with Intune Commercial<br/>
https://docs.jamf.com/10.24.1/jamf-pro/administrator-guide/Microsoft_Intune_Integration.html

![image](https://user-images.githubusercontent.com/44326428/170173545-de12f01c-f1c0-40c5-bf89-8e17418c4d97.png)
if doing this the MDM managment will come from JAMF the only thing intune will recieve is the inventory and from there can create a Compliance.<br/>
Note: Company Portal needs to be deployed from JAMF -No Intune, If done directly then Intune will try to take Managment<br/>
More informaiton on Technical paper:<br/>
https://docs.jamf.com/technical-papers/jamf-pro/microsoft-intune/10.36.0/Introduction.html



