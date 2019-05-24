# Error-Build-a-navigation-app-for-Android
 When you try to start selecting the point for navigation, errors occur

build gradle project

// Top-level build file where you can add configuration options common to all sub-projects/modules.

buildscript {
    repositories {
        google()
        jcenter()
        
    }
    dependencies {
        classpath 'com.android.tools.build:gradle:3.4.1'
        
        // NOTE: Do not place your application dependencies here; they belong
        // in the individual module build.gradle files
    }
}

allprojects {
    repositories {
        google()
        jcenter()
        mavenCentral()
        
    }
}

task clean(type: Delete) {
    delete rootProject.buildDir
}
