# Intune Custom Configuration MacOS Profile - Custom Login Banner

> Austin Lai | March 12th, 2022

---

<!-- Description -->

Intune Custom Configuration MacOS Profile - Custom Login Banner.

Custom Banner for MacOS, created using Mac Profile Creator.

<!-- /Description -->

<br />

## Table of Contents

<!-- TOC -->

- [Intune Custom Configuration MacOS Profile - Custom Login Banner](#intune-custom-configuration-macos-profile---custom-login-banner)
    - [Table of Contents](#table-of-contents)
    - [Custom Banner for MacOS - Intune mobileconfig](#custom-banner-for-macos---intune-mobileconfig)

<!-- /TOC -->

## Custom Banner for MacOS - Intune mobileconfig

```text
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>PayloadContent</key>
	<array>
		<dict>
			<key>LoginwindowText</key>
			<string>This system is restricted to authorised users.
Individuals who attempt unauthorised access will be prosecuted.
If you are unauthorised, terminate access now.
By continuing to use this system you indicate your awareness of and consent to these terms and conditions of use.

</string>
			<key>PayloadDisplayName</key>
			<string>Loginwindow</string>
			<key>PayloadIdentifier</key>
			<string>com.github.erikberglund.ProfileCreator.6B3BFD39-3829-4CFE-ADF8-31901EA7835A.com.apple.loginwindow.F8FF24AB-CB1D-4E3A-8AE7-BCBB07A8D2BF</string>
			<key>PayloadOrganization</key>
			<string></string>
			<key>PayloadType</key>
			<string>com.apple.loginwindow</string>
			<key>PayloadUUID</key>
			<string>F8FF24AB-CB1D-4E3A-8AE7-BCBB07A8D2BF</string>
			<key>PayloadVersion</key>
			<integer>1</integer>
		</dict>
	</array>
	<key>PayloadDisplayName</key>
	<string>Custom Login Banner</string>
	<key>PayloadIdentifier</key>
	<string>com.github.erikberglund.ProfileCreator.6B3BFD39-3829-4CFE-ADF8-31901EA7835A</string>
	<key>PayloadOrganization</key>
	<string>EVYD</string>
	<key>PayloadScope</key>
	<string>System</string>
	<key>PayloadType</key>
	<string>Configuration</string>
	<key>PayloadUUID</key>
	<string>6B3BFD39-3829-4CFE-ADF8-31901EA7835A</string>
	<key>PayloadVersion</key>
	<integer>1</integer>
</dict>
</plist>
```

<br />

---

> Do let me know any command or step can be improve or you have any question you can contact me via THM message or write down comment below or via FB
