Error: spawn adb ENOENT

> Solução via Linux

1
```bash
sudo apt-get install android-tools-adb
```

2. instalação do adb
```bash
sudo apt-get install android-tools-adb
```

3 create file: .bash_profile
```bash
export PATH="~/Library/Android/sdk/platform-tools":$PATH
export ANDROID_HOME="~/Library/Android/sdk/platform-tools"
```

5
```
yarn expo start --tunnel
```

[stackoverflow](https://stackoverflow.com/questions/38835931/react-native-adb-reverse-enoent)
