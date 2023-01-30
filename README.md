# jitlabtemplate

- add `jitpack.yml`
- in lib's `build.gradle`

```gradle
plugins {
    id 'com.android.library'
}
```

- Remove 
```gradle
android {
    defaultConfig {
        applicationId "com.mumayank.airlocationproject" // REMOVE THIS LINE
    }
}
