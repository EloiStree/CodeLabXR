
# Code Lab XR

Before you try to download this application.

## Creator Guidelines

* **Learn to code by playing games.**
* The goal of this application is to teach programming directly through gameplay.
* The success of the project is measured by how many beginners become coders 😋.
* Every exercise and feature should be delivered in a working, clean, and playable state by **Thursday**.

### Progress Tracker

**Testimonials**

* Learners: 0
* Juniors: 0
* Juniors → Mediors: 0

## Player Guidelines

* Keep the creator informed about your coding progress through [Discord](https://discord.gg/YDYqKKwXAt) or [GitHub/Issue](https://github.com/EloiStree/CodeLabXR/issues).
  * Without spamming 😋
* Support the project by donating to [APInt.IO](https://buymeacoffee.com/apintio):   
  * https://buymeacoffee.com/apintio   

## Project Objectives

* Help players improve their typing skills.
* Teach coding concepts to beginners, using **GDScript** as the first programming language.
* Provide fun mini-games that introduce programming and IoT concepts.

## Career Path

The primary goal of this app is to have fun while learning code.   
That said, it is also designed to guide players toward a career in software development.   

The only career path I can confidently guarantee is **QA Tester**, thanks to all the key injection workshop and screen telemetry 😅 link to this project.   
(See documentation to understand what I means)   

## Required Hardware
 
* Meta Quest 3 (or Steam Frame)
* OTG for your
  * Keyboard   
  * Mouse   
* Bluetooth Gamepad
* Optional but recommanded:
  * A Raspberry PI or a Steam Deck
 
  
**Creator Note**

I need your help.

The APInt.IO server for Raspberry Pi and EloiCodeXR is going to become one of my main project.
My mind tends to resist staying focused on the same application for years, but I want to give it a serious try.
So please help me stay focused on the CodeLabXR application.


## 2D vs XR

I really, really, really want to create a Raspberry Pi and Android 2D version.    
However, doing so would allow my brain to escape the challenges of XR development.   

To successfully deliver a useful public application, I will focus on the XR version first.
My goal is to maintain a single XR version of this application:    
* Development builds on GitHub Releases
* Latest stable version on Itch.io
* Meta Quest 3 release
* Steam release for Steam Deck and PC VR

  
## Code Within the Headset

*I hope I never have to choose between Steam Deck and Quest 3 one day.*     
This application is primarily designed and developed from within the headset using Godot.       
Part of the goal is to prove that meaningful software can be created entirely in XR—and to embrace the challenge that comes with it.      


## No Godot XR Tools

I really enjoy using Godot XR Tools, but every toolbox comes with extra complexity and maintenance costs.   
Sooner or later, changes happen that I don't want to spend time dealing with while I am teaching somewhere.      
Godot XR Tools would probably work well for this project, but I've chosen not to depend on it.

As a result, this project may not include every XR feature or convenience tool you might expect.
Instead, we'll focus on simple interactions, minimal dependencies, and keeping the project easy to maintain.      
With only what Godot Engine provide.    



---------



# Project


## Download

From [Release](https://github.com/EloiStree/CodeLabXR/releases), [Itch.io](https://eloistree.itch.io/codelabxr), ~Meta Store~, ~Steam Frame~


Install on the Quest3 with Termux
```
cd storage/shared/documents
git clone --recursive https://github.com/EloiStree/CodeLabXR.git
```


## Conctext

### APInt.io

> Learn code by playing game with Integer.

**🕹️🎮 Input Injection Hack Tool:**   
[S2W⌨️](https://github.com/EloiStree/S2W) - [XOMI🎮](https://github.com/EloiStree/XOMI) - [PicoS2W⌨️](https://github.com/EloiStree/PicoS2W) - [XESP32🎮](https://github.com/EloiStree/XESP32)


### Godotarium

> Learn GDScript as a first programming language on Quest 3 and Steam Deck with an Amazon-style robotics experience.
   
Inspirered from the Robotarium and [the video of Fouloscopie](https://www.youtube.com/watch?v=5CaVhGTG8eA)   
[<img width="828" height="433" alt="image" src="https://github.com/user-attachments/assets/6ee6c7b1-3d3e-4e8d-ae30-9a7639d3b237" />](https://www.youtube.com/watch?v=5CaVhGTG8eA)   

[Vidéo 📼](https://www.youtube.com/watch?v=5CaVhGTG8eA)  

The concept is simple: learning electronics through kits and projects purchased on Amazon often costs anywhere from $60 to $800. While these projects help users become familiar with coding, for around $20 on the store, they could learn the same fundamentals through an interactive XR simulation while actively practicing programming.

As I am working on two project but can't take the time to publish two on the store.
APInt.io is incorporeted to this one.

This project is a Godot project and is coded from within the headset.

## Previous Courses on the Topic
* https://github.com/EloiStree/2026_05_11_workshop_hello_godot_xr
* https://github.com/EloiStree/2026_03_20_workshop_hello_micro_bit
* https://github.com/EloiStree/2026_03_23_doc_micro_bit_sensor

### Hello Godot
* [💻 Code Section](https://github.com/EloiStree/HelloGodotCode)
* [🚂 Engine Section](https://github.com/EloiStree/HelloGodotEngineKeyword)
* [🕹️🎮 Hacking Game](https://github.com/EloiStree/HelloGodotRemoteControlHub)
* [👓 XR Section](https://github.com/EloiStree/HelloGodotXR)
* [🥽 Quest 3](https://github.com/EloiStree/HelloQuest3)
* [🍺🍻 Support the project](https://buymeacoffee.com/apintio)



**Required:** The game is designed to be played with a keyboard and mouse.  
* You can use an OTG adapter and a standard Bluetooth keyboard.   
* Alternatively, you can type on your PC and send the input directly to your headset with Python or Godot.  

**No Godot XR:*
*Godot XR is an excellent framework for game jams and rapid prototyping.
However, it introduces a significant dependency that I do not control within the project.
To maintain full ownership and flexibility over the codebase, this project is built without the Godot XR Tools framework.


