# KonyNativeFunctionAPI_NFC
This application will showcase KonyJSBindings feature in a way that user can use JS APIs to interact with native android NFC.

  - Beaming Text via NFC.
  - Beaming Files via NFC.
  - Reading NFC tags.

#To run this app

- Import the project.
- Go to Application Properties -> Native -> Android
- Enable Mobile First API's
- To test "Broadcast NFC URL" change the hardcoded file location to a file location available on the device.  This need to be changed in the function createndefuri() present in NFCTextandURL.js 
- Build and run the application

# Supported platforms:
**Mobile**
 * Android

**Supported KonyStudio Version:** 7.0
