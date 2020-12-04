---
marp: true
title: Building you own Keyboard
description: Why and how?
theme: itlt
paginate: true
_paginate: false
footer: CC BY-NC-SA 4.0
---
<style>
    section.wp-slide h3 {
        font-size: 0.9em;
        font-style: italic;
    }
</style>

# Building your own keyboard

### Pedro Ferreira

<style scoped>
h3 {
    color: #aaa;
    font-size: 0.8em;
    font-weight: normal;
}
img {
    vertical-align: middle;
}
</style>


---
# Why?

---
<!-- _footer: '' -->
## You can have that key you always dreamed of

![](assets/anykey.jpg)

---
<!-- _footer: '' -->
## You can have the layout you<br/> always dreamed of

![bg right](assets/sphere-kb.jpg)

---
<!-- _footer: '' -->
## It's the ultimate hacker<br/> fashion accessory

![bg right](assets/hackerman.jpg)

---
## It's (relatively) easy

![bg right](assets/level.svg)

---
<!-- _footer: '' -->
## It's fun!

![bg right](assets/fun.png)

---
<style scoped>
em {
  color: #ccc;
}
</style>

# Let's get started!

*In a record slides/min*

---
## Step 1
Pick a design

<!-- _backgroundImage: url("assets/models.png") -->
<!-- _backgroundSize: 50% -->
<!-- _backgroundPosition: right -->

[BenRoe/awesome-mechanical-keyboard](https://github.com/BenRoe/awesome-mechanical-keyboard)

---
<!-- _footer: '' -->

## Dactyl
(Matthew Adereth)

<style scoped>
  p {
    font-size: 0.5em;
  }
</style>

![bg right](assets/dactyl.png)

[![width:300px](https://img.youtube.com/vi/uk3A41U0iO4/0.jpg)](https://www.youtube.com/watch?v=uk3A41U0iO4)

https://www.youtube.com/watch?v=uk3A41U0iO4

---
<!-- _footer: '' -->

## Variations

![width:400px](assets/manuform.jpg) ![width:400px](assets/dactyl-cc.jpg)

---
<!-- _footer: '' -->

## Winner!

![bg right](assets/dactyl-cc-half.jpg)

> The dactyl-cc keyboard takes a different approach to the structure of the code (and language) as well as being more similar in feel to the Kinesis Advantage 2.

https://github.com/mjohns/dactyl-cc

---
<!-- _footer: '' -->

## Step 2: The chassis

![width:400px](assets/dactyl-cc-thing.png) ![width:400px](assets/craftcloud.png)
![width:400px](assets/lily58-pcb.jpg)

---

<video autoplay>
  <source src="assets/timelapse.mp4" type="video/mp4">
</video>

---
![bg width:800px](assets/kinesis-dactyl-cmp.jpg)

---
## Step 3: The parts

![width:200px](assets/chinalarger.jpg)
![bg right height:90%](assets/bom.png)

---
<!-- _footer: '' -->

![bg width:400px](assets/waiting.jpg)

---
## Step 4: Let's solder!

![bg right height:90%](assets/soldering1.jpg)

---
<style scoped>
  footer {
    color: #fff;
  }
</style>

![bg](assets/no-caps.jpg)

---
## Step 5: Keycaps

---

![bg height:90%](assets/kle.png)

---
<!-- _footer: '' -->
<style scoped>
  p {
      font-size: 0.5em;
    }
</style>

![width:700px](assets/keycaps_wasd.png)

https://deskthority.net/wiki/Kinesis_Contoured#Keycaps

---

![bg width:90%](assets/wasd-order.png)

---


![bg](assets/final-kb.jpg)

---
<style scoped>
em {
  color: #ccc;
}
</style>
## Step 6: Firmware

![bg right](assets/qmk_console.png)
![width:300px](assets/qmk.png)
https://qmk.fm

https://git.io/JILZk

*Am I running late by now? It will be a miracle if I'm not.*

---
<style scoped>
em {
  color: #ccc;
}
</style>

## Main takeaways

*I most certainly will be out of time by now. Just read them during the Q&A!*

 * Building your own keyboard is **not that hard**™;
 * It's also not that expensive (~200 CHF)
 * Chassis: use professional printing when possible;
 * Next time: use STM32 instead of Teensy? (cheaper, better)
 * Keycaps are expensive and hard to get in small amounts (blanks?);
 * Details matter - e.g. nuts, rubber feet...
 * **Learn from the mistakes of others!**
 * https://codimd.web.cern.ch/QGS2Mj8hRCSxOcjlCrbbFw#

---
<style scoped>
em {
  color: #ccc;
}
</style>

## Thanks!
*Look ma, no time!*

---
## Credits

 * Artem Beliaikin (typewriter photo) (Public Domain);
 * Lcamtuf - "ANY key" (CC-BY-SA);
 * "Fun" - Helena Lopes, from Pexels ([license](https://www.pexels.com/license/));
 * Lea Tschierch - 3D printing timelapse video;
 * "Hackerman - Copyright ©2014, Kung Fury;
 * All project images are property of the authors (Dactyl, Planck, Corne, Lily58, Ergodox);
 * Dactly and Dactyl-Manuform images are licensed under CC-BY-SA 4.0 by the respective authors.
