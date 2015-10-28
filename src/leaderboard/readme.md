<!--
Include Base: /Users/jtsm/Chukong-Inc/pr/en/src/leaderboard/v3-cpp
-->

#Leaderboard

##Prerequisites
* Only support `Android` now

supported backend:
- playphone

##Integration
Open a terminal and use the following command to install the SDKBOX Leaderboard plugin. Make sure you setup SDKBOX installer correctly.
```bash
$ sdkbox import leaderboard
```

Add backend.
```
$ sdkbox import playphone
```

<<[../../shared/notice.md]

<!--## Configuration
<<[../../shared/sdkbox_cloud.md]
<<[../../shared/remote_application_config.md]

<<[sdkbox-config-encrypt.md]-->

##Usage

<<[usage.md]

<<[api-reference.md]

<<[manual_integration.md]

<<[manual_ios.md]

##Manual Integration For Android and Android Studio
Both __Android__ development using a command-line and using __Android Studio__ are supported. `proj.android` will be used as our `<project_root>` for __command-line__ development, while `proj.android-studio` will be used as our `<project_root>` for __Android Studio__.
<<[manual_android.md]

<<[extra-step.md]

<<[proguard.md]