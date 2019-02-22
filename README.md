### build 가 안될때
```sh
error : xcodeBuilder error occured
$> sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
```
### cordova requirement 확인
```sh
$> cordova requirements //해당 사항을 확인해서 설치를 해 주면 된다.
```
해당 사항들을 확인해서 설치하면 된다.
#### for ios
1. ios-deploy
```
    $> npm i -g ios-deploy
```
2. CocoaPods
```
    $> sudo gem install cocoapods
    $> pod setup
```
3. git