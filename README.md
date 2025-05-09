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

![SaveSuccess_Event](https://github.com/user-attachments/assets/09b82407-e96f-448b-8a8d-28e8c3419b5b)
![SaveFailed_Event](https://github.com/user-attachments/assets/d358e88f-08b4-4be4-87fd-b0c062873faf)


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

![BackgroundRGB_Method](https://github.com/user-attachments/assets/0a898922-8ca5-4b4d-9380-466088962558)
![BackgroundGradient_Method](https://github.com/user-attachments/assets/5ee9970c-16eb-4c2f-8d02-2eb115969a0c)
![ShowHomeIndicator_Method](https://github.com/user-attachments/assets/6a75fdbb-cd7d-4375-bdfa-e9cb381598bc)
![ScreenGradient_Method](https://github.com/user-attachments/assets/0109f997-81e7-4eb7-a23d-b8d0b096a0bc)
![SaveFrameAsPNG_Method](https://github.com/user-attachments/assets/554bdcc6-a023-47d1-ac20-73061f164a0e)
![SaveFrameAsJPEG_Method](https://github.com/user-attachments/assets/941d057f-6afd-4777-9f41-5eb26487f36b)
![SaveAsPNG_Method](https://github.com/user-attachments/assets/cdd148be-330c-4661-b50c-a2e67af35182)
![SaveAsJPEG_Method](https://github.com/user-attachments/assets/d5486f12-5f78-4258-88db-e1c421e60400)
![PhoneMockup_Method](https://github.com/user-attachments/assets/1bbd3cbf-fb42-48bf-9e62-9294fcff29ad)
![FrameGradient_Method](https://github.com/user-attachments/assets/a253fcd4-c934-490d-8046-06328078c595)
![DeviceDimensions_Method](https://github.com/user-attachments/assets/38a0fbd7-eb95-48f4-ad2d-f028ca6e5163)
![CustomizeVolumeButtons_Method](https://github.com/user-attachments/assets/e74b7488-3946-418a-8ef5-dc2fd70b83b5)
![CustomizePowerButton_Method](https://github.com/user-attachments/assets/77872545-1099-4ef2-b383-c338facfd88f)
![ChangeMockupType_Method](https://github.com/user-attachments/assets/48a80b64-4a6f-4b28-a15a-9588e65c85f5)
![CaptionPadding_Method](https://github.com/user-attachments/assets/d351bd8d-273b-457f-a415-64d3571a7365)


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

![LoadScreenImage_Set_Property](https://github.com/user-attachments/assets/410e14ec-126e-4b15-bed5-0d05168f559a)
![LoadBackgroundImage_Set_Property](https://github.com/user-attachments/assets/5d19272c-ad50-4f8e-bdec-48c67b7a5360)
![ImageQuality_Set_Property](https://github.com/user-attachments/assets/b4165a69-41e4-4fcb-b357-ffcc3ce05ad7)
![FrameShadowElevation_Set_Property](https://github.com/user-attachments/assets/577dddc7-1666-4cda-9d22-fea0c8c4308a)
![FrameRotation_Set_Property](https://github.com/user-attachments/assets/d3e854ae-67f4-4e24-b069-14abddb83dc8)
![FramePaddingTop_Set_Property](https://github.com/user-attachments/assets/479f59bb-b747-4266-9350-3d401eb60597)
![FramePaddingRight_Set_Property](https://github.com/user-attachments/assets/775ccb00-a88a-4a85-8520-7ca9a13b8465)
![FramePaddingLeft_Set_Property](https://github.com/user-attachments/assets/790e35e0-21ba-4c0a-90b8-cf15118a2503)
![FramePaddingBottom_Set_Property](https://github.com/user-attachments/assets/32cbc0f3-5571-464c-af5c-80d5e0721bff)
![FrameColor_Set_Property](https://github.com/user-attachments/assets/5b329ef1-87ae-44e0-8353-5bd4fbbd40d8)
![EnableDarkMode_Set_Property](https://github.com/user-attachments/assets/ebfe37a2-93cf-47f9-907e-06d6c5171717)
![DeviceName_Set_Property](https://github.com/user-attachments/assets/e2976ee2-e797-4042-82aa-d7bab31e282c)
![CornerRadius_Set_Property](https://github.com/user-attachments/assets/30cd8147-6065-4d10-bc73-400bef7d3dbc)
![CaptionTextStyle_Set_Property](https://github.com/user-attachments/assets/83f38108-be81-4e3b-bc37-0638b07ba9e3)
![CaptionTextColor_Set_Property](https://github.com/user-attachments/assets/d21adbb3-7d0e-4c75-a7a4-a7d77ec67768)
![CaptionText_Set_Property](https://github.com/user-attachments/assets/cce227e8-fe93-4b4d-b264-36bd8e91d26e)
![CaptionSubTextStyle_Set_Property](https://github.com/user-attachments/assets/8a00ae0f-fb93-4628-ad86-5daa2587a34e)
![CaptionSubTextColor_Set_Property](https://github.com/user-attachments/assets/5dac6ca7-6aad-4c33-aae3-acf3f80d2e48)
![CaptionSubText_Set_Property](https://github.com/user-attachments/assets/b6c3b2c7-a1c3-4394-8d1e-6ce66e20533f)
![CaptionSubFontSize_Set_Property](https://github.com/user-attachments/assets/cf953665-f9e6-48d3-b28d-4ac8e8950ac3)
![CaptionRotation_Set_Property](https://github.com/user-attachments/assets/087b07e4-5fc3-413f-ad51-8e89dc3c9d34)
![CaptionPaddingTop_Set_Property](https://github.com/user-attachments/assets/258e5a9b-a46e-4bd5-a5e2-7a1bd0dd374d)
![CaptionPaddingRight_Set_Property](https://github.com/user-attachments/assets/baedba01-cd6b-4b13-ac1c-993baa06407d)
![CaptionPaddingLeft_Set_Property](https://github.com/user-attachments/assets/7777fcb3-da36-4fad-98a0-c9b662bfa445)
![CaptionPaddingBottom_Set_Property](https://github.com/user-attachments/assets/6fc5e58e-d44d-4b26-a950-a48c649664a8)
![CaptionFontSize_Set_Property](https://github.com/user-attachments/assets/45fd5741-76ab-4c84-a127-094aa83e80ca)
![ButtonColor_Set_Property](https://github.com/user-attachments/assets/21c4005d-56de-44b2-b1be-56411b8cd325)
![BezelWidth_Set_Property](https://github.com/user-attachments/assets/52266590-e3da-4809-b658-37b5d04be151)
![BackgroundColor_Set_Property](https://github.com/user-attachments/assets/601abbf7-79e6-4905-a72d-8fab18871262)
![ShowVolumeButtons_Set_Property](https://github.com/user-attachments/assets/0f112c09-74a0-4dba-9120-c94ac1c87351)
![ShowPowerButton_Set_Property](https://github.com/user-attachments/assets/0741c192-fa70-40c8-baee-1e85e7e70bb7)
![ShowNotch_Set_Property](https://github.com/user-attachments/assets/7bd269c5-1274-44ac-b124-6d55a76d98f5)
![ShowDeviceName_Set_Property](https://github.com/user-attachments/assets/43005bbc-1f9c-4590-af52-d5499b33deca)
![ScreenColor_Set_Property](https://github.com/user-attachments/assets/180fbd06-b875-4ac2-92b9-cf2d0920b95c)
![SaveDirectory_Set_Property](https://github.com/user-attachments/assets/d030054b-d8a0-4eab-b3d4-b4b85943faf6)
![NotchType_Set_Property](https://github.com/user-attachments/assets/2b78cd01-f47d-4f0e-b22b-f3f528696b8c)


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


![ImageQuality_Get_Property](https://github.com/user-attachments/assets/b8456b8e-fb30-4635-9e12-4e98112367e1)
![SaveDirectory_Get_Property](https://github.com/user-attachments/assets/f6f3ff0b-1d67-430a-a555-5bb9981e7970)

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
