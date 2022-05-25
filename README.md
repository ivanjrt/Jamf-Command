# Jamf-Cheat Sheet
sudo is required to have full authorothy on running the commmand as root
-verbose  switch will show the command being run with the required Info


# Help On jamf commands
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

# Uninstall the JAMF agent
``` ruby
jamf –removeFramework
```

# Removes	the	jamf	MDM	profile
``` ruby
jamf removeMdmProfile
```

# Checking on Processes on a MAC
``` ruby
top
```
