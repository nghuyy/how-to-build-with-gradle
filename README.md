# How to build with gradle (project contain gradle.kts file)

+ Using binary Gradle
Download and install binary Gradle here (May be require Java >= 11.x) 
 https://gradle.org/install/

Using command test install status:
```
gradle --version
````

Try to build:

```
gradle Release

```

+ Using gradle wrapper(project contain gradlew.bat and gradle.sh vs gradle.kts) (require Java >= 11.x or JDK >= 11.x)
```
 linux: ./gradle Release
 
 windows: gradlew Release
 
```
