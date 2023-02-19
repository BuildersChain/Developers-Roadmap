## Flutter roadmap
# basic dart

## What is Flutter?
Flutter is a free and open-source mobile application development framework created by Google.
It was first introduced in 2017 and has since gained a lot of popularity among developers.
Advantages of Flutter
1.Provides fast development cycles and hot reload, which allows for quick iterations and reduces development time.

1. Uses a single codebase to create apps for both Android and iOS platforms, reducing the need for separate teams and resources.
1. Offers a customizable widget-based framework that allows for creating visually appealing and interactive user interfaces.
1. Provides access to a wide range of plugins and packages that can be easily integrated with the codebase, allowing for easier customization and feature additions.
1. Supports the use of popular programming languages such as Dart, which allows for easy adoption and integration with existing development processes.
1. Comes with a robust documentation and active community support, which makes it easier for developers to get help and stay up to date with the latest updates and features.
## Conclusion
Flutter is a powerful framework for mobile application development that offers many advantages to developers. Its customizable widgets, fast development cycles, and support for popular programming languages make it a popular choice among developers who want to create visually appealing and interactive mobile applications quickly and efficiently.
 # whats in this roadmap ?
->what is flutter?
->some core basic, like different types of widgets
->state topics
->advance topics

1. widgets
1. stateless widgets
1. stateful widgets
1. material(android)/cupertino(ios) widgets
1. projects->make
1. software design principles->solid,design patterns etc
1. api
1. shared preferences
1. networking in flutter,pub.dev
1. sqlite/firebase/supabase->preference
1. some advance topics and → provider or velocityx or redux
1. testing
1. packages&plugins
1. memory&performance
1. dos and donts for developer

## links 
1. https://youtu.be/j-LOab_PzzU
2. flutter.dev

# mostly setup is the most difficult so here are the steps
# flutter setup
1. install flutter, set path in enviroment variables of bin
# https://docs.flutter.dev/get-started/install
1. then install android studio
# https://developer.android.com/studio
1. install latest sdk and also cmline tools when opening android studio first time
1. setup virtual device in android studio settings->device manager->new device
1. go to environment variables -> system-> path->paste sdk path
1. run flutter doctor in cmd
see if any errors
if error of android toolchain,
go to android studio installation path by cd then run -> mklink /D "jre" "jbr" -> this will create a symbolic link so sdk will be able to run required dependancies from jbr
if any error of flutter sdk then -> make sure flutter/bin is added into path environment variables
if any error of cmake,  make sure simple visual studio is installed with cmake package