# AV-Foundation-SwiftUI

Recording Audio in ios requires to use the AVFoundation framework 
Av foundation lets you record video and audio 

This project will only cover the audio part using AVFoundation 

---
Key Terms used: 

Audio Category :  category defines a set of audio behaviors
Audio session: 

## What you need to add audio 

- Audio Settings
- Audio File
-AVAudioRecorder
------------------------------
In this project i will create a project where the penguin is talking 

##STEPS 
1. Enable AVAudio Session , you may want to add this in the app delegate 
```swift
class AppDelegate: NSObject, UIApplicationDelegate {
  func application(_ application: UIApplication, didFinishLaunchingWithOptions launchOptions: 
  [UIApplication.LaunchOptionsKey : Any]? = nil) -> Bool {
  
  return true
```
2. Import AVFoundation
```swift
import AVFoundation
```
3. Get a refrence to the current AVAudio session 
```swift
let session = AVAudioSession.sharedInstance()
```
4. Set the  Audio Category

