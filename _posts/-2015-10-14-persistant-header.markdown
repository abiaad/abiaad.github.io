---
layout: post
title:  "Persistant header"
date:   2015-10-14 10:30:53
categories: ios
---
Some applications reveal some persistant UI components through the user navigation (aka across all the navigation stack). For one project, this header would completely replace the navigation bar. I want this header fully customisable (transparent, components, ...)
One solution is to add an UIView directly to to the navigation controller view but there's a cleaner way to do that. Few lines of code and the use of Storyboard.
Let's me explain !

Usually navigationController is your rootViewController. Apple provides a great component : UIViewContainer.
