# Minecraft

## Install Mods

### OpenJdkのインストール
[OpenJDK](https://jdk.java.net/)

```
$javaPath = Get-Location
[Environment]::SetEnvironmentVariable("JAVA_PATH", $javaPath, 'User')
$path = [Environment]::GetEnvironmentVariable('Path', 'User')
$newPath = $path + ';%JAVA_PATH%'
[Environment]::SetEnvironmentVariable("Path", $newPath, 'User')
```

### Optifineのインストール
[Optifine](https://optifine.net/downloads)

```
java -jar .\OptiFine_1.18_HD_U_H3.jar
```

### BSL SHADERS のインストール
[BSL SHADERS](https://bitslablab.com/bslshaders/)

```
%APPDATA%\.minecraft\shaderpacks
```

#### Texturepackのインストール
- [Faithful](https://resourcepack.net/faithful-32x32-resource-pack/)
```
%APPDATA%\.minecraft\resourcepacks
```