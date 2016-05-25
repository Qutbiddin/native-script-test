# native-script-test

    1. Install Node.js
	2. Install nativescript: npm install -g nativescript
	3. verify tns : tns —version
	4. Install iOS and Android requirements
        a) Windows: @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://www.nativescript.org/setup/win'))"
        b) Mac: ruby -e "$(curl -fsSL https://www.nativescript.org/setup/mac)"
	5. Verify NativeScript: tns doctor
    6. Create app: tns create [my-app-name] --ng
    7. cd to [my-app-name]
    8. Add target development platforms:
        a) iOS: tns platform add ios
        b) Android tns platform add android.
    9. Run App :) tns run ios —emulator
    10. Development workflow:
        a) iOS: tns livesync ios --emulator --watch
        b) Android: tns livesync android --emulator --watch