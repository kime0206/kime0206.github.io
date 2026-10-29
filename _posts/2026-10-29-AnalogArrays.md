---
layout: post
title: Analog Arrays
author: Eunchae Kim
cover-img: /assets/img/VibeBoard.jpeg
thumbnail-img: /assets/img/VibeBoard.jpeg
share-img: /assets/img/VibeBoard.jpeg
---
Description of Analog Array Assignment:
This program turns on a random PWM pin to a random value every second, or turn that pin off, when appropriate.

Tip:
A tip I would give my past self is to remember that the array index is not the same as the physical pin number. For example, pin 10 is at index 4 in the array, so using states[10] would access the wrong location and could cause problems. Instead, use the same index to access both the pin and its on/off state.

![VibeBoard](/assets/img/VibeBoard.jpeg)

