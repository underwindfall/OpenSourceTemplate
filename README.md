# OpenSourceTemplate (ANDROID)
This repository can be used as a template to create new GitHub repositories for Kotlin/Android libraries.

### Code Formatting

```gradle
./gradlew spotlessApply
```

*Make sure you update [spotless.license.kt](spotless/spotless.license.kt) author info!* Other settings for this plugin can be tweaked in [spotless/spotless.gradle](spotless/spotless.gradle).


### Publishing the Library to Bintray -> jCenter

This repository is setup to automatically publish to Bintray when you create a new release from
GitHub. You can find more in [release.yml](.github/workflows/release.yml)