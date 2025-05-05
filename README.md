# ddns-setup-personal


pm2 start "curl https://example.com/api/startup" --name ddns-update --interpreter bash


sdkmanager "system-images;android-30;google_apis;x86_64"

avdmanager create avd -n flutter_emulator -k "system-images;android-30;google_apis;x86_64"

################################################################

ANDROID_SDK_ROOT  -> C:\android\sdk
JAVA_HOME  -> D:\Program Files\Java\jdk-21

Setup : Android SDK Command-line Tools

sdkmanager "platform-tools" "platforms;android-30" "tools" "build-tools;30.0.3"

flutter config --android-sdk "c:\android\sdk"

flutter doctor

flutter emulators

flutter emulators --launch flutter_emulator


