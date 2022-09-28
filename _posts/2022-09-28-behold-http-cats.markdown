---
layout: post
title: "My First AppStore App - Update"
date: 2022-09-28 20:00:00 +0100
categories: swift swiftui xcodecloud xcode appstore ios app httpcodes
---

A write up of getting an app into the App Store...

## Why?

So, if you're a keen reader of this blog, you'll not have failed to notice that I've been learning SwiftUI. (If you're not a keen reader of this blog...where have you been?! ;-) )

I'm fortunate to be part of the native app development teams at SkyBet. We're always looking to make our apps better and innovate in the latest technologies. As a leader I think it's important to "practice what you preach" and be at least familiar with the ecosystem in which you play a (small) part.

It's been a while since I've written any production code (they'll be plenty of people who are happy about this...) but I do like to practice every now and again. Learning a new language & framework seemed like a good excuse.

Those who know me will be aware that I'm an Android user. You might be wondering why this wasn't Jetpack Compose... watch this space. :-)

## How?

- Get access to a Mac laptop (seems obvious, but I'm fortunate to have this - I'm aware it's a high barrier to entry. You can learn and compile Swift online here http://online.swiftplayground.run/ without a Mac)
  
- Learnt SwiftUI - following the Apple tutorials. (https://developer.apple.com/tutorials/swiftui)
  
- Thought up a simple idea for an app; it helped that the images had an API of sorts to download them (credit to Fili Wiese for putting these sites together)
  
- Developed the app (complete with _some_ Unit and UI tests - you can see them for yourself in the code; I need to add more.)
  
- Became a fully fledged Apple developer (https://developer.apple.com/)
  
- I was already familiar with the App Stores processes, but I still had to fill out my own Privacy Policy and generate App Store assets (this is hard work for a non-designer!).
  
- Submitted to Apple after frequent Testflight releases
  
- Dealt with 3 app review rejections (I'd forgotten to include the *required* capabilities section https://developer.apple.com/support/required-device-capabilities/) (`<rant>`why, Apple, if it's a required element, don't you prompt before wasting your review team's time? Or prevent installation of the app on a simulator? `</rant>`)


## What have I learnt?

Lots!

- Swift (a small fraction I'm sure)
  
- SwiftUI (scratched the surface!)
  
- Xcode Cloud (this is an amazing *free* provision from Apple!)
  
- Bitrise (although I didn't use it for the majority of the builds)
  
- Refamiliarised myself with Github (especially around tracking a project)
  
- The Apple ecosystem - resources, communities
  
- Dealing with frustration and set back (and keeping on)
  
- More about using Xcode (a tiny proportion of it - I'm still very much a beginner)
  
- Design (_I'm definitely not a designer_)
  
- Making connections with people
  
- Building an app is fun!
  
- ... & probably more that I've already forgotten

## Where next?

The source code is open source and available to peruse at your leisure at https://github.com/adrenalinehit/CatCodes.

There are many ways to improve and further develop the app. Take a look at the issues list here: https://github.com/adrenalinehit/CatCodes/issues.

Get in touch if you'd like to get involed. I will review all PRs submitted. (https://github.com/adrenalinehit/CatCodes/pull/30 for example)

I definitely need an artist to create some art work for this app - I'm *not* a designer or artist. Please get in touch.

## Thanks & Acknowledgements

Matt Glover for his contributions and beta testing & also for creating Code Club.

Matt Gallagher for his beta testing and encouragement.

Jennifer Munro-Brown for encouraging me to write this up.

Many other colleagues who have had to put up with me talking about the app for a few months now.

My employer for providing time dedicated to Learning and Development. (we're hiring - https://www.skybetcareers.com)

Fili Wiese for the images from https://httpcats.com https://http.dog and https://http.garden.

https://unsplash.com/@anushabarwa for the logo photo https://unsplash.com/photos/ppKcYi1CXcI

## Would you like to download the app?

![Download on App Store]({{"/assets/images/download-on-appstore.svg"}})(https://apps.apple.com/us/app/http-codes/id1626500016)

## Anything else you'd like to know?

Please, reach out. Get in touch. 

If you've got an app idea, get started... see where it goes.