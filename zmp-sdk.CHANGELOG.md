## v2.48.0 (2025-09-22)
### Features
- **openDocument**: New API to open document files (PDF).

## v2.44.2 (2025-02-11)
### Bug fixes
- **nativeStorage**: Fixed a bug causing it to not work on the web.

## v2.44.1 (2024-12-26)
### Bug fixes
- **getUserInfo**: return code + message when response'

## v2.44.0 (2024-12-02)
### Features
- **downloadFile**: Save file to device external drive.
- **saveVideoToGallery**: Save video to device media gallery.

## v2.43.2 (2024-11-25)
### Bug fixes
 - **openShareSheet**: type image imageUrl to optional.

## v2.43.1 (2024-11-25)
### Bug fixes
 -  **setItem, getItem, removeItem**: Fix bug native storage params invalid.

## v2.43.0 (2024-11-20)
### Features
 - **openPostFeed**: type image support multiple urls.
 - **setItem, getItem, removeItem, clear, getStorageInfo**: added new apis to nativeStorage.
 - **setStorage, getStorage, removeStorage, clearStorage, getStorageInfo**: deprecated async storage apis

## v2.39.8 (2024-07-30)

### Bug fixes
 -  **getAccessToken**: Fix bug.
  
## v2.39.6 (2024-07-29) DEPRECATED
### REASON
 - API payment not working.
  
## v2.39.0 (2024-06-19)
### Features

- **showFunctionButtonWidget, showOAWidget** : added new apis to show widgets.
- **openShareSheet**: new type text.
- **camera SDK** : camera class that makes stream management easier, with common functions and an OnFrameCallback to handle returned frames. 

## v2.38.2 (2024-06-11)
### Features

- **getUserInfo**: Added field 'autoRequestPermission'

## v2.38.0 (2024-06-03)
### Features

- added new apis: **showOAWidget**

## v2.37.5 (2024-05-30)
### Improve

- createOrder payment android open bottom sheet
- deep link use single param zshareId

## v2.37.4 (2024-05-28)

### Bug fixes
 - **getUserInfo**: show consent when Zalo App has more than 1 MiniApp.

## v2.37.1 (2024-04-01)

### Features
- Added apis Advertising
- Update api Payment

## v2.35.4 (2024-02-23)

### Bug fixes
- Missing followedOA field declaration in getUserInfo api response

## v2.35.3 (2024-01-31)

### Bug fixes
- Correct file name interactOA in build package

## v2.35.2 (2024-01-31)
 - By default, user consent is only displayed when retrieving user information with name and avatar

## v2.35.0 (2024-01-25)

- if accessToken is obtained without user consent, the userId can only be obtained. 

## v2.33.1 (2023-11-27)

### Bug fixes

 - **requestSendNotification**: Resolving the bug related to sending notifications
 - **setNavigationBarTitle**: Resolving the issue of incorrect page titles when navigating back

## v2.32.3 (2023-11-27)

### Features

 - **getUserInfo**: Added field 'followedOA'

## v2.32.2 (2023-11-23)

### Bug fixes
 - Fixed few bugs

### Features
 - **getUserID**: Added api "getUserID"
## v2.30.4 (2023-10-31)

### Bug fixes

 - **getUserInfo**: Resolving incorrect image dimensions in responses
## v2.30.0 (2023-10-10)

### Features

 - **openWebview**: New Configuration Options for openWebview. You can now define the style of the webview when it opens, [see more](../openWebview/).
## v2.28.2 (2023-08-14)

### Bug fixes

 - **requestSendNotification**: Fixed the success return data on Android
## v2.28.1 (2023-07-26)

### Bug fixes

 - **followOA**, **unfollowOA**: Fixed the return data
## v2.28.0 (2023-07-12)

### Features

 - **addRating**: Added new api "addRating"
 - **interactOa**: Added new api "interactOa"
 - **getUserInfo**: Added sensitive info
## v2.27.2 (2023-06-21)

### Bug fixes

 - Fixed bug payment
## v2.27.1 (2023-06-01)

### Features

 - **favoriteApp**: Added new api "favoriteApp"
 - **openPermissionSetting**: Added new api "openPermissionSetting"
## v2.26.1 (2023-04-26)

### Features

 - **minimizeApp**: Added new api "minimizeApp"
 - **openMiniApp**: Can open mini app with path

### Bug fixes

 - **Data Caching**: Cannot use storage on env local fixed
## v2.25.7 (2023-04-17)

### Features

 - **openShareSheet**: Added options type: 'zmp_deep_link'
## v2.25.6 (2023-04-03)

### Bug fixes

 - **Data Caching**: Cannot use storage fixed
## v2.25.3 (2022-03-20)

### Features

  - The SDK is now treeshakable, allowing you to import only the necessary APIs from zmp-sdk/apis.
  - Added new API: **configAppView**
### Changes:

  - Renamed the 'Events' property to 'EventName' for clarity.
## v2.24.0 (2022-02-20)

### Features

  - The return data for **getLocation**, **getPhoneNumber** functions has been updated.
## v2.23.4 (2022-02-02)

### Features

  - Added new API: **chooseImage**

 - **getUserInfo**: Added field 'idByOA' 
## v2.23.3 (2023-12-09)

### Features

 - **getUserInfo**: Added field 'idByOA' 

## v2.23.2 (2022-12-02)

### Features

 - **openMediaPicker**: Added options type: 'zcamera', 'zcamera_photo', 'zcamera_video', 'zcamera_scan' 

## v2.23.0 (2022-09-20)

### Features

 - Added new APIs: **getAuthCode**, **setAccessToken**, **getDeviceIdAsync**, **getContextAsync**
 - Implemented default login for all APIs that don't require an access token.

### Bug fixes

 - **requestCamerapermission**: Fixed the return data

## v2.22.2 (2022-08-18)

### Bug fixes

 - **openShareSheet**: Updated the version of Zalo that supports sharing multiple images

## v2.22.0 (2022-08-03)

### Features

 - **getContext**: introduced a new api `getContext`

## v2.21.2 (2022-07-14)

### Bug fixes


 - **openShareSheet**: error when share image (Zalo iOS version 22.06.02)
