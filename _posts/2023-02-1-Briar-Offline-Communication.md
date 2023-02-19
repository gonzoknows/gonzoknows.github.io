---
title: Utilizing Briar for Offline Communications
date: 2023-02-1 05:00:00 -0800
categories: []
tags: [briar, encryption, security] #tags should always be lowercase
---

## Introduction
Offline communication is a valuable tool as it doesn't depend on internet connectivity. This makes it more reliable and secure compared to online communication.

In scenarios where personal, face-to-face interaction is not possible, such as while snowboarding in a remote area or traveling on a flight without access to stable Wi-Fi, offline communication becomes a convenience or even necessity for some. For example, during a flight, if you are seated away from your friends or family, offline communication can be used to communicate with them.

### What Is Briar?
[Briar](https://briarproject.org/) is a free, open-source, secure, and decentralized messaging app designed for use in environments where the internet is unavailable or unreliable. It uses a mesh network to route messages between users, meaning that messages can be sent even if no direct connection exists between the sender and the recipient. Briar is intended for use by journalists, activists, and other people who need secure and private communication, especially in areas where the internet is censored or monitored.

### Technology Behind Briar
A full breakdown of Briar's technology can be found here: [https://briarproject.org/how-it-works/](https://briarproject.org/how-it-works/)

![Briar's Technology Breakdown By Briar Project](/assets/img/offline%20communication/diagram_sharing.png)

Briar uses both Bluetooth and Wi-Fi to route messages between users in its mesh network. The Bluetooth feature is used for short-range communication, allowing for direct communication between two devices that are close to each other. Distance varies device to device view limitations of this post.

The Wi-Fi feature is used for longer-range communication, allowing messages to be sent between devices that are further apart. Briar uses Wi-Fi Direct, a Wi-Fi standard that allows devices to communicate directly without the need for a central router. When two Briar devices are within Wi-Fi range of each other, they can exchange messages directly, without relying on an internet connection.

By using both Bluetooth and Wi-Fi, Briar provides a robust and versatile communication network that can work in a variety of situations, from crowded public spaces to remote areas with limited infrastructure. This makes it a valuable tool for individuals and organizations that need secure and private communication in challenging environments.

## Use Cases
While Briar is mainly designed for activists, journalists, and anyone else who needs a safe, easy and robust way to communicate. I've identified some practical use cases that are a result of Briar being designed this way.

- Camping
- Airplanes
- Ski Resorts
- Natural Disasters
- Search and Rescue
- Concrete Buildings 
- Underground Buildings 
- Saving Data or Using Fewer Amounts of Data

## Limitations
Currently, as of writing this post, Briar is a great instant messaging app... if you are running an android device. It does many things right such as reliability, Briar will work no matter if you have an internet connection or not which is huge for communication reliability. Though it doesn't come with its downsides listed below

- Features:
    - Messaging Only
        - No Audio Calls
        - No Video Calls/FaceTime

- Platform Support:
    - Android (Windows & Linux in beta)

- App Requirements:
    - Must be running in the background on all devices. 

- Hardware Limitations:
    - Bluetooth & Wi-Fi Direct offer limited range.

### Apple
Short Answer: As mentioned above, Briar doesn't support Apple's mobile platform iOS, this is mostly due to Apple and their restrictions they have on their apps. I've gone ahead and linked some open issues on Briar's developer platform [GitLab](https://code.briarproject.org/briar/briar)

"iOS and iPhone (#445)" - [https://code.briarproject.org/briar/briar/-/issues/445](https://code.briarproject.org/briar/briar/-/issues/445)

"iOS feasibility study (#2282)" - [https://code.briarproject.org/briar/briar/-/issues/2282](https://code.briarproject.org/briar/briar/-/issues/2282)

### Desktop
Briar is currently in beta phase on Windows and Linux with macOS support soon to come. 
If you plan on using the beta release which can be downloaded [here,](https://briarproject.org/download-briar-desktop/) be sure to expect bugs.