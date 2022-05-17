# sum_test

Error:
Launching lib/main.dart on Pixel 5 in debug mode...
Running Gradle task 'assembleDebug'...
e: /Users/LudwigBolling/.pub-cache/hosted/pub.dartlang.org/flutter_idensic_mobile_sdk_plugin-1.19.4/android/src/main/kotlin/com/sumsub/idensic/mobile/sdk/plugin/Extensions.kt: (9, 37): Object is not abstract and does not implement abstract member public abstract fun error(p0: String, p1: String?, p2: Any?): Unit defined in io.flutter.plugin.common.MethodChannel.Result
e: /Users/LudwigBolling/.pub-cache/hosted/pub.dartlang.org/flutter_idensic_mobile_sdk_plugin-1.19.4/android/src/main/kotlin/com/sumsub/idensic/mobile/sdk/plugin/Extensions.kt: (12, 9): 'error' overrides nothing
e: /Users/LudwigBolling/.pub-cache/hosted/pub.dartlang.org/flutter_idensic_mobile_sdk_plugin-1.19.4/android/src/main/kotlin/com/sumsub/idensic/mobile/sdk/plugin/MethodCallHandler.kt: (192, 39): Type mismatch: inferred type is BinaryMessenger? but BinaryMessenger was expected

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':flutter_idensic_mobile_sdk_plugin:compileDebugKotlin'.
> Compilation error. See log for more details

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 4s
Exception: Gradle task assembleDebug failed with exit code 1

Flutter doctor:

Doctor summary (to see all details, run flutter doctor -v):

[✓] Flutter (Channel stable, 3.0.0, on macOS 12.3.1 21E258 darwin-x64, locale en-SE)

[✓] Android toolchain - develop for Android devices (Android SDK version 31.0.0)

[✓] Xcode - develop for iOS and macOS (Xcode 13.4)

[✓] Chrome - develop for the web

[✓] Android Studio (version 2021.2)

[✓] VS Code (version 1.55.2)

[✓] VS Code (version 1.55.2)

[✓] Connected device (4 available)

[✓] HTTP Host Availability

