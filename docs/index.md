---
# https://vitepress.dev/reference/default-theme-home-page
layout: home
title: Home
hero:
  name: "Posture Reminder"
  text: "App"
  tagline: Open source posture reminder for Android
  image:
    src: "logo.webp"
    alt: "logo"
  actions:
    - theme: brand
      text: Get the app
      link: https://play.google.com/store/apps/details?id=com.puntogris.posture
    - theme: alt
      text: See the code
      link: https://github.com/puntogris/posture-reminder

features:
  - title: Multiple Reminders
    details: Create reminders for differents ocations, you can also choose a sound an a vibration pattern.
  - title: Level up & Statistics
    details: Gain experience and climb to get the highest level fixing your posture, you can see in the graphs how well you are doing.
  - title: Themes
    details: Pick between Light and Dark theme or your system default one.
---

# Screens

<div :class="$style.container"> 
<img src="/1.webp" width="350" height="350"/>
<img src="/2.webp" width="350" height="350"/>
<img src="/3.webp" width="350" height="350"/>
</div>




<style module>
.container {
    display: flex;
    place-items: center;
    justify-items: center;
    width: 200;
    margin-left: auto;
    margin-right: auto;

}
</style>