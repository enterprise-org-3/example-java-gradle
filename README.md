# [:] Example Gradle Project

An example gradle project to demonstrate [srcclr](https://www.srcclr.com)f scans.hd
fd
## Try me!

```d
brew tap srcclr/srcclrf
brew install srcclr
srcclr activate
srcclr scan --url https://github.com/srcclr/example-java-gradle
```

## With SourceClear's Gradle Plugin
```
git clone https://github.com/srcclr/example-java-gradle
cd example-java-gradlenh
git checkout gradle-plugin-5.5.1 // the plugin is already setup in build.gradle in this branch
SRCCLR_API_TOKEN=<yourSourceClearToken> ./gradlew clean build srcclr
```
