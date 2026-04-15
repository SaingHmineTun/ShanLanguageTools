# ShanConverters

This repository contains various converters and syllable word breakers that I have developed.

## Overview

All tools are written in Java, and contributions in other languages are welcome.

### Converters (4)
1. **ShanTranslit**
2. **ShanZawgyiConverter**
3. **TaiNueaConverter**
4. **ShanAyingConverter**

### Syllable Word Breakers (2)
1. **Shan Syllable Word Breaker**
2. **Tai Nuea Syllable Word Breaker**

## Installation

You can integrate this project into your workflow in two ways:

### Option 1: Download JAR from Releases
1. Visit the [Releases](https://github.com/saimao/ShanLanguageTools/releases) page
2. Download the latest version
3. Include the JAR file in your project

### Option 2: Install via JitPack (Recommended)

#### Step 1: Add JitPack Repository
Firstly, go to the setttings.gradle and add the jitpack repository there!

**Gradle (Groovy)**
```groovy
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        mavenCentral()
        maven { url 'https://www.jitpack.io' }
    }
}
```

**Gradle (Kotlin DSL)**
```kotlin
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        mavenCentral()
        maven { url = uri("https://www.jitpack.io") }
    }
}
```

**Maven**
```xml<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://www.jitpack.io</url>
    </repository>
</repositories>
```

#### Step 2: Add Dependency

**Gradle (Groovy)**
```groovy
dependencies {
    implementation'com.github.SaingHmineTun:ShanLanguageTools:1.0.1'
}
```

**Gradle (Kotlin DSL)**
```kotlin
dependencies {
    implementation("com.github.SaingHmineTun:ShanLanguageTools:1.0.1")
}
```

**Maven**
```xml
<dependency>
    <groupId>com.github.SaingHmineTun</groupId>
    <artifactId>ShanLanguageTools</artifactId>
    <version>1.0.1</version>
</dependency>
