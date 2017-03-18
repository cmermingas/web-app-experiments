# Web App Experiments

I strongly advocate progressive web apps and I have faced countless challenges configuring them,
particularly with iOS. So, I created this repo to conduct a few experiments.

# References:

https://developer.apple.com/library/content/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html#//apple_ref/doc/uid/TP40002051-CH3-SW6

# Experiment 1

- Goal: Configure a launch image
- OS: iOS 10.2.1
- Background

  [Apple's documentation](https://developer.apple.com/library/content/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html#//apple_ref/doc/uid/TP40002051-CH3-SW6)
  indicates that we can specify a launch screen image with a `<link rel="apple-touch-startup-image">` tag.
  
Add [Web App 1](https://cmermingas.github.io/web-app-experiments/web-app-1.html)
to your home screen. 

- Result: **The launch screen image does not show up.**

# Experiment 2

- Goal: Test switching between "running" web apps
- OS: iOS 10.2.1

Add Web Apps to your home screen:
 
- [Web App 1](https://cmermingas.github.io/web-app-experiments/web-app-1.html)
- [Web App 2](https://cmermingas.github.io/web-app-experiments/web-app-2.html)
- [Web App 3](https://cmermingas.github.io/web-app-experiments/web-app-3.html)
- [Web App 4](https://cmermingas.github.io/web-app-experiments/web-app-4.html)
- [Web App 5](https://cmermingas.github.io/web-app-experiments/web-app-5.html)

Open them from the home screen and switch between them in the app switcher.
**The app that opens doesn't always correspond with the app that was chosen in
the app switcher**. Here's a video:

![iOS App Switch](https://cmermingas.github.io/web-app-experiments/app-switch.gif)

