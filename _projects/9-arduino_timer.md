---
layout: page

title: "⏱️ Pomodoro Alarm"
description: An alarm based on the Pomodoro Technique, dividing work into intervals signaled by melodies such as  Sweet Child of Mine and theme songs of Pirates of the Carribean , Game of Thrones.x
# img: assets/img/sp_cup_2024/sp_cup_denoising.png
importance: 1
category: fun
related_publications: false


date: 2022-08-05T14:08:51+05:30
draft: false
tags : ['Arduino','C++']
github: https://github.com/SasikaA073/arduino-pomodoro-alarm-m
---

# Arduino Alarm using Pomodro Technique

The buzzer starts to play three different melodies in differnt intervals according to the Pomodoro technique.

This technique would be highly productive for the people who lose motivation to get things done. 

This is an article about this technique if you are curious to find out more. 

[About Pomodro Technique](https://todoist.com/productivity-methods/pomodoro-technique)

---
## Default time periods :
> * __study session :__  25 mins 
> * __interval :__ 5 mins

You can change these time constraints in the _**pomodro_cycles.ino**_ file. Beware to use the *unsigned long* data type when changing the time constraints.

## Default meoldies :
> * __melody 1 :__ Sweet Child of Mine 
> * __melody 2 :__ Pirates of the Carribean theme song
> * __melody 3 :__ Game of Thrones theme song 

You can add/change the melodies on your own.

![Pomodoro Alarm Circuit](/images/Pomodoro_Alarm.png "Pomodro alarm circuit")

## Acknowledgement

> * The credit for the melodies goes to the original creators. 
> ( The links for the original melody source are mentioned in the respective header files.) 
> * Tinkercad platform as a circuit design platform
