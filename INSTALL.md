# 빌드 설치

```bash
xcode-select --install
sudo xcode-select -switch /Applications/Xcode.app/Contents/Developer

git clone --recursive https://github.com/jwise/HoRNDIS.git
cd Development/HoRNDIS/
xcodebuild -sdk macosx -configuration Release
sudo cp -rv build/Release/HoRNDIS.kext /Library/Extensions/
```

## REF

* https://github.com/jwise/HoRNDIS/issues/146
