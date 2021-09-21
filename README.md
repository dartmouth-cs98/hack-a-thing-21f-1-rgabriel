# Hack Technology / Project Attempted


## What you built? 

For this assignment, I wanted to get a sense for Flutter, a development kit intended to produce cross-platform mobile applications. Using it, I developed a random name generator. More specifically, the app displays an infinitely scrollable list with random startup names. The user can save suggestions that they like. In addition, I tried to build a portion of a habit tracker (the homescreen) up until I developed my opinion on the tool.

[Name Generator](img/NameGen.png)
[Generator Saved Page](img/SavedSuggestions.png)
[Habit Tracker Homescreen](img/HabitTracker.png)

## Who Did What?

I worked on this assignment individually.

## What you learned / Why I'd Rather use React + Expo

Flutter treats everything within your application as a widget. Quite literall everything, from containers
and stateful wrappers to text, colors and icons. To construct an app, you have to compose it out of these 
much more fundamental components. As such, the tool encourages a modular design pattern. Personally, I think
other tools (i.e. React Native) do this style much better. It is incredibly easy to have a nested mess, at 
which point basic syntax issues arise (like matching your parens). My IDE added comments to help visualize
the nesting levels, but the Dart code itself comes off as jumbled. 

Google markets the tool as being intended for cross-platform development. There are aspects about Flutter that I
find appealing for this purpose. Plenty of the widgets Flutter contains already have a good style to them
(in line with Google's material design). Naturally, that looks well for Android. However, an application will
exhibit different behaviors depending on the platform it is run on. That is to say, the same code could be compiled
for IOS and Android and the app, to some extent, will already abide by the design patterns typically followed in the platform.
However, as far as I'm aware, Flutter applications are much larger than their native counterparts, even for simple programs
like this tutorial one. 

While the styling is convenient, I think I'd rather use CSS. I felt restricted while using Flutter for the simplest of things, like
moving text and buttons around. If I wanted to do so, I had to wrap my code within widgets (such as Padding or Container) that were
specifically designed to serve as generic containers like div. Simply put, I'd rather have the freedom to manipulate those without having to rely on
on yet another nested layer of widgets and hot-reloading to see if my change matches what I wanted.

Speaking of hot-reloading, it certainly does. But like, other tools do the same thing...And while it does speed up the development cycle,
I found that my computer would just slow down after having the same instance run, so often I had to stop using hot-reloading so Chrome could
stop murdering my memory. 

Lastly, to touch on some misc things: the documentation for Flutter is amazing and they feature guides for people who
have prior mobile dev experience, the installation process was a hassle and they do not yet feature Android emulation
for people with AMD CPUs, the community is still growing so it is bound to receive community extensions and it does feature
a lot more out-the-box than other cross-platform options. Using dependencies was also really easy, just had to add it to 
pubspec and import it in main.dart.

## Authors

Roberto Gabriel Brito

## Acknowledgments

[Part One](https://flutter.dev/docs/get-started/codelab)
[Part Two](https://codelabs.developers.google.com/codelabs/first-flutter-app-pt2)