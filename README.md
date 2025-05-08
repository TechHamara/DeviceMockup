<div align="center" >
<h1><kbd>🏃‍♂️ DeviceMockup</kbd></h1>
An extension for MIT App Inventor 2.
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.devicemockup
💾 **Size:** 111.86 KB
⚙️ **Version:** 1.0
📱 **Minimum API Level:** 7
📅 **Updated On:** [date=2025-05-08 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small>
* **

### 🤝 Multi-Components
1. [DeviceMockup](#kbd-devicemockupkbd-3)
2. [Desktop](#kbd-desktopkbd-63)
3. [Laptop](#kbd-laptopkbd-105)
4. [SmartWatch](#kbd-smartwatchkbd-166)

# <kbd>🧩 DeviceMockup</kbd>
This component is developed by th using Fast.<br>This component provides a realistic mobile device mockup with various notch types and physical buttons.<br>It is designed to simulate the look and feel of a real mobile device, allowing for a more immersive user experience.<br>The component is developed by th using Fast, ensuring a high level of detail and realism.<br>It includes a range of notch types, such as iPhone, punch hole, pill shape, slim notch, wide notch, double punch hole, dynamic island, and waterdrop, as well as physical buttons for volume and power control.<br>The component is highly customizable, allowing developers to tailor the appearance and behavior to their specific needs.<br>With its advanced features and realistic design, this component is ideal for creating engaging and interactive mobile ScreenShot Mockup.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>

## <kbd>Events:</kbd>
**DeviceMockup** has total 2 events.

### SaveSuccess
Event raised when the mockup is successfully saved to a file

| Parameter | Type
| - | - |
| filePath | text

### SaveFailed
Event raised when there is an error saving the mockup

| Parameter | Type
| - | - |
| errorMessage | text

## <kbd>Methods:</kbd>
**DeviceMockup** has total 15 methods.

### PhoneMockup
Add mockup layout to the given arrangement

| Parameter | Type
| - | - |
| arrangement | component

### DeviceDimensions
Set the device dimensions. Example: DeviceDimensions(100, 200) for a 100dp width and 200dp height.

| Parameter | Type
| - | - |
| width | number
| height | number

### ShowHomeIndicator
Show or hide the home indicator

| Parameter | Type
| - | - |
| show | boolean

### ChangeMockupType
Change mockup image (Use numbers 1-5). Example: ChangeMockupType(1) for the first mockup image.

| Parameter | Type
| - | - |
| mockupNumber | number

### BackgroundRGB
Set background color using RGB values (0-255 for each)

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### BackgroundGradient
Set a gradient background with start and end colors. Example: BackgroundGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### ScreenGradient
Set the screen background to a gradient (in light mode). Example: ScreenGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### FrameGradient
Set frame background to a gradient. Example: FrameGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### CaptionPadding
Set the padding of the caption container (in dp)

| Parameter | Type
| - | - |
| left | number
| top | number
| right | number
| bottom | number

### CustomizeVolumeButtons
Customize volume buttons position and size

| Parameter | Type
| - | - |
| topButtonMargin | number
| bottomButtonMargin | number
| buttonWidth | number
| buttonHeight | number

### CustomizePowerButton
Customize power button position and size

| Parameter | Type
| - | - |
| topMargin | number
| buttonWidth | number
| buttonHeight | number

### SaveAsPNG
Save the current mockup as a PNG image. Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveAsJPEG
Save the current mockup as a JPEG image with specified quality (1-100). Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

### SaveFrameAsPNG
Save only the phone frame portion as PNG image (without the background)

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveFrameAsJPEG
Save only the phone frame portion as JPEG image (without the background). Example: SaveFrameAsJPEG('myFrame', 'path/to/directory', 90)

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

## <kbd>Setters:</kbd>
**DeviceMockup** has total 36 setter properties.

### EnableDarkMode
Enable dark mode mockup

* Input type: `boolean`

### FrameColor
Set the frame color of the mockup. Example: '#1F2937' for a dark gray frame.

* Input type: `text`

### ScreenColor
Set the screen color of the mockup (in light mode). Example: '#FFFFFF' for a white screen.

* Input type: `text`

### CornerRadius
Set corner radius of the device frame. Example: 10 for a 10dp corner radius.

* Input type: `number`

### BezelWidth
Set the bezel width. Example: BezelWidth(10) for a 10dp bezel width.

* Input type: `number`

### DeviceName
Set the device type label that appears above the mockup. For example: SetDeviceType("iPhone 14 Pro")

* Input type: `text`

### ShowDeviceName
Show or hide the device type label

* Input type: `boolean`

### ShowNotch
Show or hide the notch

* Input type: `boolean`

### BackgroundColor
Set the background color of the mockup container. Example: BackgroundColor('#FFFFFF') for a white background.

* Input type: `text`

### NotchType
Set notch type: 1=iPhone notch, 2=punch hole, 3=pill shape, 4=slim notch, 5=wide notch, 6=double punch hole, 7=dynamic island, 8=waterdrop, 9=no notch

* Input type: `number`

### LoadScreenImage
Load an image from a URL, file path (like e.g. /storage/emulated/0/Pictures/demo.png

* Input type: `text`

### LoadBackgroundImage
Load a background image for the mockup container (like e.g. /storage/emulated/0/Pictures/demo.png

* Input type: `text`

### FramePaddingLeft
Set the left padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingTop
Set the top padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingRight
Set the right padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingBottom
Set the bottom padding of the phone frame (in dp)

* Input type: `number`

### FrameShadowElevation
Set the shadow elevation of the phone frame (in dp)

* Input type: `number`

### FrameRotation
Set the rotation of the phone frame in degrees. Example: FrameRotation(90) for a 90 degree rotation.

* Input type: `number`

### CaptionText
Set the caption text displayed above the mockup

* Input type: `text`

### CaptionSubText
Set the caption sub-text displayed below the main caption text

* Input type: `text`

### CaptionFontSize
Set the font size of the caption text (in sp)

* Input type: `number`

### CaptionSubFontSize
Set the font size of the caption sub-text (in sp)

* Input type: `number`

### CaptionTextColor
Set the color of the caption text

* Input type: `text`

### CaptionSubTextColor
Set the color of the caption sub-text

* Input type: `text`

### CaptionTextStyle
Set the text style of the caption (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionSubTextStyle
Set the text style of the caption sub-text (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionPaddingLeft
Set the left padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingTop
Set the top padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingRight
Set the right padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingBottom
Set the bottom padding of the caption container (in dp)

* Input type: `number`

### CaptionRotation
Set the rotation of the caption text in degrees. Example: CaptionRotation(90) for a 90 degree rotation.

* Input type: `number`

### ShowVolumeButtons
Show or hide the volume buttons

* Input type: `boolean`

### ShowPowerButton
Show or hide the power button

* Input type: `boolean`

### ButtonColor
Set the color of the phone buttons. Example: ButtonColor('#FF0000') for a red button.

* Input type: `text`

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Input type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Input type: `text`

## <kbd>Getters:</kbd>
**DeviceMockup** has total 2 getter properties.

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Return type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Return type: `text`

# <kbd>🧩 Desktop</kbd>
This component is developed by th using Fast.<br>This component provides a realistic desktop device mockup.<br>It is designed to simulate the look and feel of a desktop device, allowing for a more immersive user experience.<br>The component is developed by th using Fast, ensuring a high level of detail and realism.<br>The component is highly customizable, allowing developers to tailor the appearance and behavior to their specific needs.<br>With its advanced features and realistic design, this component is ideal for creating engaging and interactive desktop Screenshot Mockups.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>

## <kbd>Events:</kbd>
**Desktop** has total 2 events.

### SaveSuccess
Event raised when the mockup is successfully saved to a file

| Parameter | Type
| - | - |
| filePath | text

### SaveFailed
Event raised when there is an error saving the mockup

| Parameter | Type
| - | - |
| errorMessage | text

## <kbd>Methods:</kbd>
**Desktop** has total 11 methods.

### IMacMockup
Add iMac style desktop mockup to the given arrangement

| Parameter | Type
| - | - |
| arrangement | component

### BackgroundRGB
Set background color using RGB values (0-255 for each)

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### BackgroundGradient
Set a gradient background with start and end colors. Example: BackgroundGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### ScreenGradient
Set the screen background to a gradient (in light mode). Example: ScreenGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### CaptionPadding
Set the padding of the caption container (in dp)

| Parameter | Type
| - | - |
| left | number
| top | number
| right | number
| bottom | number

### SaveAsPNG
Save the current mockup as a PNG image. Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveAsJPEG
Save the current mockup as a JPEG image with specified quality (1-100). Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

### SaveFrameAsPNG
Save only the desktop frame portion as PNG image (without the background)

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveFrameAsJPEG
Save only the desktop frame portion as JPEG image (without the background). Example: SaveFrameAsJPEG('myDesktop', 'path/to/directory', 90)

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

### LoadIMacScreenImage
Load an image into the iMac mockup screen

| Parameter | Type
| - | - |
| imagePath | text

### CustomizeIMacMockup
Customize the iMac mockup dimensions and appearance

| Parameter | Type
| - | - |
| screenWidth | number
| screenHeight | number
| standWidth | number
| standHeight | number
| screenBorderColor | text
| chinColor | text
| standColor | text

## <kbd>Setters:</kbd>
**Desktop** has total 21 setter properties.

### IMacName
Set the device type label that appears above the mockup. For example: IMacName("iMac 24-inch")

* Input type: `text`

### ShowIMacName
Show or hide the device type label

* Input type: `boolean`

### BackgroundColor
Set the background color of the mockup container. Example: BackgroundColor('#FFFFFF') for a white background.

* Input type: `text`

### LoadBackgroundImage
Load a background image for the mockup container (like e.g. /storage/emulated/0/Pictures/demo.png

* Input type: `text`

### ShadowElevation
Set the shadow elevation of the desktop frame (in dp)

* Input type: `number`

### CaptionText
Set the caption text displayed above the mockup

* Input type: `text`

### CaptionSubText
Set the caption sub-text displayed below the main caption text

* Input type: `text`

### CaptionFontSize
Set the font size of the caption text (in sp)

* Input type: `number`

### CaptionSubFontSize
Set the font size of the caption sub-text (in sp)

* Input type: `number`

### CaptionTextColor
Set the color of the caption text

* Input type: `text`

### CaptionSubTextColor
Set the color of the caption sub-text

* Input type: `text`

### CaptionTextStyle
Set the text style of the caption (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionSubTextStyle
Set the text style of the caption sub-text (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionPaddingLeft
Set the left padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingTop
Set the top padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingRight
Set the right padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingBottom
Set the bottom padding of the caption container (in dp)

* Input type: `number`

### CaptionRotation
Set the rotation of the caption text in degrees. Example: CaptionRotation(90) for a 90 degree rotation.

* Input type: `number`

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Input type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Input type: `text`

### DarkMode
Set to true for dark mode, false for light mode

* Input type: `boolean`

## <kbd>Getters:</kbd>
**Desktop** has total 3 getter properties.

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Return type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Return type: `text`

### DarkMode
Set to true for dark mode, false for light mode

* Return type: `boolean`

# <kbd>🧩 Laptop</kbd>
This component is developed by th using Fast.<br>This component provides a realistic laptop device mockup with customizable screen content.<br>It is designed to simulate the look and feel of a real laptop, allowing for a more immersive user experience.<br>The component is highly customizable, allowing developers to tailor the appearance and behavior to their specific needs.<br>With its advanced features and realistic design, this component is ideal for creating engaging and interactive laptop ScreenShot Mockup.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>

## <kbd>Events:</kbd>
**Laptop** has total 2 events.

### SaveSuccess
Event raised when the mockup is successfully saved to a file

| Parameter | Type
| - | - |
| filePath | text

### SaveFailed
Event raised when there is an error saving the mockup

| Parameter | Type
| - | - |
| errorMessage | text

## <kbd>Methods:</kbd>
**Laptop** has total 10 methods.

### LaptopMockup
Add laptop mockup layout to the given arrangement

| Parameter | Type
| - | - |
| arrangement | component

### DeviceDimensions
Set the device dimensions. Example: DeviceDimensions(100, 200) for a 100dp width and 200dp height.

| Parameter | Type
| - | - |
| width | number
| height | number

### BackgroundRGB
Set background color using RGB values (0-255 for each)

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### BackgroundGradient
Set a gradient background with start and end colors. Example: BackgroundGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### ScreenGradient
Set the screen background to a gradient (in light mode). Example: ScreenGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### CaptionPadding
Set the padding of the caption container (in dp)

| Parameter | Type
| - | - |
| left | number
| top | number
| right | number
| bottom | number

### SaveAsPNG
Save the current mockup as a PNG image. Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveAsJPEG
Save the current mockup as a JPEG image with specified quality (1-100). Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

### SaveFrameAsPNG
Save only the phone frame portion as PNG image (without the background)

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveFrameAsJPEG
Save only the phone frame portion as JPEG image (without the background). Example: SaveFrameAsJPEG('myFrame', 'path/to/directory', 90)

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

## <kbd>Setters:</kbd>
**Laptop** has total 36 setter properties.

### EnableDarkMode
Enable dark mode mockup

* Input type: `boolean`

### TouchpadWidth
Set the touchpad width (in dp)

* Input type: `number`

### TouchpadHeight
Set the touchpad height (in dp)

* Input type: `number`

### TouchpadColor
Set the touchpad color. Example: '#E0E0E0' for a light gray touchpad.

* Input type: `text`

### ShowKeyboardSection
Show or hide the laptop keyboard base section

* Input type: `boolean`

### ShowWebcam
Show or hide the laptop webcam

* Input type: `boolean`

### FrameColor
Set the frame color of the mockup. Example: '#1F2937' for a dark gray frame.

* Input type: `text`

### ScreenColor
Set the screen color of the mockup (in light mode). Example: '#FFFFFF' for a white screen.

* Input type: `text`

### CornerRadius
Set corner radius of the device frame. Example: 10 for a 10dp corner radius.

* Input type: `number`

### BezelWidth
Set the bezel width. Example: BezelWidth(10) for a 10dp bezel width.

* Input type: `number`

### DeviceName
Set the device type label that appears above the mockup. For example: SetDeviceType("iPhone 14 Pro")

* Input type: `text`

### ShowDeviceName
Show or hide the device type label

* Input type: `boolean`

### BackgroundColor
Set the background color of the mockup container. Example: BackgroundColor('#FFFFFF') for a white background.

* Input type: `text`

### LoadScreenImage
Load an image from a URL, file path or asset to display on the laptop screen

* Input type: `text`

### LoadBackgroundImage
Load a background image for the mockup container (like e.g. /storage/emulated/0/Pictures/demo.png

* Input type: `text`

### FramePaddingLeft
Set the left padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingTop
Set the top padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingRight
Set the right padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingBottom
Set the bottom padding of the phone frame (in dp)

* Input type: `number`

### FrameShadowElevation
Set the shadow elevation of the phone frame (in dp)

* Input type: `number`

### FrameRotation
Set the rotation of the phone frame in degrees. Example: FrameRotation(90) for a 90 degree rotation.

* Input type: `number`

### CaptionText
Set the caption text displayed above the mockup

* Input type: `text`

### CaptionSubText
Set the caption sub-text displayed below the main caption text

* Input type: `text`

### CaptionFontSize
Set the font size of the caption text (in sp)

* Input type: `number`

### CaptionSubFontSize
Set the font size of the caption sub-text (in sp)

* Input type: `number`

### CaptionTextColor
Set the color of the caption text

* Input type: `text`

### CaptionSubTextColor
Set the color of the caption sub-text

* Input type: `text`

### CaptionTextStyle
Set the text style of the caption (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionSubTextStyle
Set the text style of the caption sub-text (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionPaddingLeft
Set the left padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingTop
Set the top padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingRight
Set the right padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingBottom
Set the bottom padding of the caption container (in dp)

* Input type: `number`

### CaptionRotation
Set the rotation of the caption text in degrees. Example: CaptionRotation(90) for a 90 degree rotation.

* Input type: `number`

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Input type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Input type: `text`

## <kbd>Getters:</kbd>
**Laptop** has total 8 getter properties.

### EnableDarkMode
Enable dark mode mockup

* Return type: `boolean`

### TouchpadWidth
Set the touchpad width (in dp)

* Return type: `number`

### TouchpadHeight
Set the touchpad height (in dp)

* Return type: `number`

### TouchpadColor
Set the touchpad color. Example: '#E0E0E0' for a light gray touchpad.

* Return type: `text`

### ShowKeyboardSection
Show or hide the laptop keyboard base section

* Return type: `boolean`

### ShowWebcam
Show or hide the laptop webcam

* Return type: `boolean`

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Return type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Return type: `text`

# <kbd>🧩 SmartWatch</kbd>
This component is developed by th using Fast.<br>This component provides a realistic smartwatch device mockup with customizable properties.<br>It is designed to simulate the look and feel of a real smartwatch, allowing for a more immersive user experience.<br>The component is developed by th using Fast, ensuring a high level of detail and realism.<br>It includes features for customizing the watch face, buttons, and bands.<br>The component is highly customizable, allowing developers to tailor the appearance and behavior to their specific needs.<br>With its advanced features and realistic design, this component is ideal for creating engaging and interactive smartwatch mockups.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>

## <kbd>Events:</kbd>
**SmartWatch** has total 2 events.

### SaveSuccess
Event raised when the mockup is successfully saved to a file

| Parameter | Type
| - | - |
| filePath | text

### SaveFailed
Event raised when there is an error saving the mockup

| Parameter | Type
| - | - |
| errorMessage | text

## <kbd>Methods:</kbd>
**SmartWatch** has total 15 methods.

### SmartWatchMockup
Add smartwatch mockup layout to the given arrangement

| Parameter | Type
| - | - |
| arrangement | component

### WatchDimensions
Set the smartwatch dimensions. Example: WatchDimensions(188, 193) for a 188dp width and 193dp height.

| Parameter | Type
| - | - |
| width | number
| height | number

### ShowHomeIndicator
Show or hide the home indicator

| Parameter | Type
| - | - |
| show | boolean

### ChangeMockupType
Change mockup image (Use numbers 1-5). Example: ChangeMockupType(1) for the first mockup image.

| Parameter | Type
| - | - |
| mockupNumber | number

### BackgroundRGB
Set background color using RGB values (0-255 for each)

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### BackgroundGradient
Set a gradient background with start and end colors. Example: BackgroundGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### ScreenGradient
Set the screen background to a gradient (in light mode). Example: ScreenGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### FrameGradient
Set frame background to a gradient. Example: FrameGradient('#FF0000', '#0000FF', true) for a horizontal gradient from red to blue.

| Parameter | Type
| - | - |
| startColorHex | text
| endColorHex | text
| isHorizontal | boolean

### CaptionPadding
Set the padding of the caption container (in dp)

| Parameter | Type
| - | - |
| left | number
| top | number
| right | number
| bottom | number

### SaveAsPNG
Save the current mockup as a PNG image. Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveAsJPEG
Save the current mockup as a JPEG image with specified quality (1-100). Returns the full path to the saved file or empty string if failed.

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

### SaveFrameAsPNG
Save only the phone frame portion as PNG image (without the background)

| Parameter | Type
| - | - |
| fileName | text
| directory | text

### SaveFrameAsJPEG
Save only the phone frame portion as JPEG image (without the background). Example: SaveFrameAsJPEG('myFrame', 'path/to/directory', 90)

| Parameter | Type
| - | - |
| fileName | text
| directory | text
| quality | number

### CustomizeSideButtons
Customize side buttons position and size on the smartwatch

| Parameter | Type
| - | - |
| topButtonMargin | number
| bottomButtonMargin | number
| buttonWidth | number
| buttonHeight | number

### CustomizeCrownButton
Customize the crown button position and size on the smartwatch

| Parameter | Type
| - | - |
| topMargin | number
| buttonWidth | number
| buttonHeight | number

## <kbd>Setters:</kbd>
**SmartWatch** has total 36 setter properties.

### EnableDarkMode
Enable dark mode mockup

* Input type: `boolean`

### FrameColor
Set the frame color of the smartwatch mockup. Example: '#1F2937' for a dark gray frame.

* Input type: `text`

### ScreenColor
Set the screen color of the smartwatch face (in light mode). Example: '#FFFFFF' for a white screen.

* Input type: `text`

### CornerRadius
Set corner radius of the smartwatch frame. Example: 40 for a 40dp corner radius (more rounded look).

* Input type: `number`

### BezelWidth
Set the bezel width of the smartwatch. Example: BezelWidth(5) for a 5dp bezel width.

* Input type: `number`

### WatchName
Set the device type label that appears above the mockup. For example: DeviceName("Apple Watch")

* Input type: `text`

### ShowWatchName
Show or hide the device type label

* Input type: `boolean`

### ShowNotch
Show or hide the notch

* Input type: `boolean`

### BackgroundColor
Set the background color of the mockup container. Example: BackgroundColor('#FFFFFF') for a white background.

* Input type: `text`

### NotchType
Set notch type: 1=iPhone notch, 2=punch hole, 3=pill shape, 4=slim notch, 5=wide notch, 6=double punch hole, 7=dynamic island, 8=waterdrop, 9=no notch

* Input type: `number`

### LoadScreenImage
Load an image from a URL, file path (like e.g. /storage/emulated/0/Pictures/demo.png

* Input type: `text`

### LoadBackgroundImage
Load a background image for the mockup container (like e.g. /storage/emulated/0/Pictures/demo.png

* Input type: `text`

### FramePaddingLeft
Set the left padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingTop
Set the top padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingRight
Set the right padding of the phone frame (in dp)

* Input type: `number`

### FramePaddingBottom
Set the bottom padding of the phone frame (in dp)

* Input type: `number`

### FrameShadowElevation
Set the shadow elevation of the phone frame (in dp)

* Input type: `number`

### FrameRotation
Set the rotation of the phone frame in degrees. Example: FrameRotation(90) for a 90 degree rotation.

* Input type: `number`

### CaptionText
Set the caption text displayed above the mockup

* Input type: `text`

### CaptionSubText
Set the caption sub-text displayed below the main caption text

* Input type: `text`

### CaptionFontSize
Set the font size of the caption text (in sp)

* Input type: `number`

### CaptionSubFontSize
Set the font size of the caption sub-text (in sp)

* Input type: `number`

### CaptionTextColor
Set the color of the caption text

* Input type: `text`

### CaptionSubTextColor
Set the color of the caption sub-text

* Input type: `text`

### CaptionTextStyle
Set the text style of the caption (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionSubTextStyle
Set the text style of the caption sub-text (0=normal, 1=bold, 2=italic, 3=bold italic)

* Input type: `number`

### CaptionPaddingLeft
Set the left padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingTop
Set the top padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingRight
Set the right padding of the caption container (in dp)

* Input type: `number`

### CaptionPaddingBottom
Set the bottom padding of the caption container (in dp)

* Input type: `number`

### CaptionRotation
Set the rotation of the caption text in degrees. Example: CaptionRotation(90) for a 90 degree rotation.

* Input type: `number`

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Input type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Input type: `text`

### ShowSideButtons
Show or hide the side buttons on the smartwatch

* Input type: `boolean`

### ShowCrownButton
Show or hide the crown button on the smartwatch

* Input type: `boolean`

### ButtonColor
Set the color of the smartwatch buttons. Example: ButtonColor('#FF0000') for red buttons.

* Input type: `text`

## <kbd>Getters:</kbd>
**SmartWatch** has total 2 getter properties.

### ImageQuality
Set the image quality for JPEG format (1-100). Only applies when saving as JPEG.

* Return type: `number`

### SaveDirectory
Set the default directory to save images to. If empty, will use the external storage Pictures directory

* Return type: `text`

### Thank
  TechHamara
