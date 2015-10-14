# TLTintColor
help you set the default tint color for your app.
Shorten the time of customization for UIControls with just one line of code.

<img src="https://raw.githubusercontent.com/TechLoveVN/TLTintColor/master/screen1.png" alt="Screenshot" style="width: 320px;"/>
![alt tag](https://raw.githubusercontent.com/TechLoveVN/TLTintColor/master/screen2.png)
![alt tag](https://raw.githubusercontent.com/TechLoveVN/TLTintColor/master/screen3.png)
# Setup
- Import "DPTheme.swift" into your project.

- Just one simple line of code inside 'didFinishLaunchingWithOptions':
``` swift
let mainColor: UIColor = TechLoveTintColor.color(0x017460, alpha: 1.0)
let secondColor: UIColor = TechLoveTintColor.color(0xE0F2F1, alpha: 1.0)
let fontName = "Avenir"

TechLoveTintColor.setupTheme(
	mainColor,
	secondaryColor: secondColor,
	fontName: fontName,
	lightStatusBar: true)
```

- (Optional) Go to your Info.plist file and set value for key 'View controller-based status bar appearance' is 'NO' for the status bar to be set to light content.

- You can custom color for each controls, for example:
``` swift
TechLoveTintColor.customizeButton(UIColor.redColor())
```


# Contact
Email: robert@techlove.vn Website: http://techlove.vn
