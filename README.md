# qa_guru_3_21_hw
1. Установить jdk

2. Установить android studio https://developer.android.com/studio

3. Прописать path:

Параметры Path:

Windows:

%ANDROID_HOME%\tools

%ANDROID_HOME%\tools\bin

%ANDROID_HOME%\platform-tools

Одной строкой, можно скопировать и добавить в конец Path: ;%ANDROID_HOME%\tools;%ANDROID_HOME%\tools\bin;%ANDROID_HOME%\platform-tools

Mac:

$ANDROID_HOME/tools

$ANDROID_HOME/tools/bin

$ANDROID_HOME/platform-tools

Одной строкой, можно скопировать и добавить в .bash_profile:

export PATH=”${PATH}:/$ANDROID_HOME/tools:/$ANDROID_HOME/tools/bin:/$ANDROID_HOME/platform-tools”

4. Установить appium desktop https://github.com/appium/appium-desktop

5. Установить appium ispector https://github.com/appium/appium-inspector

6. В android studio -> SDK Manager скачать 11 андроид (если не скачан по умолчанию)

7. В AVD Manager скачать образ Pixel 4 для 11 андроида (если не скачан по умолчанию)