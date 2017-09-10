# Android-FPVDemo

## Introduction

This FPVDemo-crack will implement the FPV view and two basic camera functionalities: **Take Photo** and **Record Video**. It uses the cracked-sdk of DJISDKLIB.

## Requirements

 - Android Studio 2.0+
 - Android System 4.1+
 - DJI Android SDK 4.1.1

## Tutorial

For this demo's tutorial: **Creating a Camera Application**, please refer to <https://developer.dji.com/mobile-sdk/documentation/android-tutorials/FPVDemo.html>.

## Changes made

The AndoidManifest.xml file in FPV-Demo crack/FPVDemo/app/src/main has empty string as app key. As the SDK is cracked, it takes any string given as app key as a valid key and allows the custom app to access the DJI SDK completely. This app only uses the live video feed and uses the APIs for camera access, capture photos, record videos.
