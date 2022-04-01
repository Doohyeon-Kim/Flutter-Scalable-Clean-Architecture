# scalable_clean_architecture

Flutter scalable clean architecture made by Doohyeon Kim.

![dooadex_scalable_flutter_architecture](https://user-images.githubusercontent.com/92246475/161221352-4b03a406-9c17-4d15-bcfc-f768892baeb3.png)

## Directory Structure

``` bash
.
├── README.md
├── analysis_options.yaml
├── android
├── assets
│   ├── fonts
│   │   └── font.file
│   ├── icons
│   │   └── icon.file
│   └── images
│       └── image.file
├── ios
├── lib
│   ├── components
│   │   └── component.dart
│   ├── configs
│   │   ├── app_config.dart
│   │   ├── palette.dart
│   │   └── themes
│   ├── constants
│   │   ├── api_path.dart
│   │   ├── app_constants.dart
│   │   ├── asset_path.dart
│   ├── main.dart
│   ├── modules
│   │   ├── module01
│   │   │   ├── models
│   │   │   ├── presenters
│   │   │   ├── repositories
│   │   │   ├── usecases
│   │   │   └── views
│   │   └── module02
│   │       ├── models
│   │       ├── presenters
│   │       ├── repositories
│   │       ├── usecases
│   │       └── views
│   ├── services
│   │   ├── error
│   │   │   └── error_message_handler.dart
│   │   ├── firebase
│   │   ├── native_api
│   │   │   ├── local_notifivation.dart
│   │   │   └── shared_preference.dart
│   │   └── network
│   │       ├── http
│   │       └── rest_api
│   └── utilities
│       └── logger.dart
├── pubspec.lock
├── pubspec.yaml
└── test
    └── widget_test.dart
```
