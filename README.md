#Hide Facebook News Feed
An add-on designed for Firefox on Android to block the Facebook news feed in the mobile website.

If you're like me and hate wasting time scrolling mindlessly through Facebook's news feed, but still want to access Facebook for events/photos/messaging etc, this might be helpful.

It's a very basic app that uses the Firefox Add-On SDK with the "page-mod" module. It simply finds the news feed div and sets its display attribute to 'none'. 

It's probably not very efficient, I'm not sure if it still downloads images etc in the background, but meh.

## Building instructions
To build and run this app, run the following command:

`jpm-mobile run --adb path/to/adb -b firefox`

I used ideas (and a tiny bit of code) from [News Feed Eradicator](https://github.com/jordwest/news-feed-eradicator/).
