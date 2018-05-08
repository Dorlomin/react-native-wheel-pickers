# react-native-wheel-pickers
### Fort of https://github.com/beefe/react-native-picker
#### Add custom fontFamily for android base on **farnabaz** PR https://github.com/beefe/react-native-picker/pull/301

### Documentation

#### Params

|Key | Type | Default| Support | Description |
| --- | --- | ---- | ------ | ----------- |
|isLoop                | Boolean | false              |     Android  |   |
|pickerTextEllipsisLen | number  | 6                  |     Android  |   |
|pickerConfirmBtnText  | string  | confirm            | iOS/Android  |   |
|pickerCancelBtnText   | string  | cancel             | iOS/Android  |   |
|pickerTitleText       | string  | pls select         | iOS/Android  |   |
|pickerConfirmBtnColor | array   | [1, 186, 245, 1]   | iOS/Android  |   |
|pickerCancelBtnColor  | array   | [1, 186, 245, 1]   | iOS/Android  |   |
|pickerTitleColor      | array   | [20, 20, 20, 1]    | iOS/Android  |   |
|pickerToolBarBg       | array   | [232, 232, 232, 1] | iOS/Android  |   |
|pickerBg              | array   | [196, 199, 206, 1] | iOS/Android  |   |
|pickerToolBarFontSize | number  | 16                 | iOS/Android  |   |
|wheelFlex             | array   | [1, 1, 1]          | iOS/Android  |   |
|pickerFontSize        | number  | 16                 | iOS/Android  |   |
|pickerFontColor       | array   | [31, 31, 31, 1]    | iOS/Android  |   |
|pickerFontFamily      | string  |                    | Android      |   |
|pickerRowHeight       | number  | 24                 | iOS          |   |
|pickerData            | array   |                    | iOS/Android  |   |
|selectedValue         | array   |                    | iOS/Android  |   |
|onPickerConfirm       | function|                    | iOS/Android  |   |
|onPickerCancel        | function|                    | iOS/Android  |   |
|onPickerSelect        | function|                    | iOS/Android  |   |

#### Methods

|Key | Support | Description |
| --- | ---- | ----------- |
|init         | iOS/Android |init and pass parameters to picker      |
|toggle       | iOS/Android |show or hide picker                     |
|show         | iOS/Android |show picker                             |
|hide         | iOS/Android |hide picker                             |
|select       | iOS/Android |select a row                            |
|isPickerShow | iOS/Android |get status of picker, return a boolean  |
