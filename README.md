# Project 2 - *SimpleTweet*

**Name of your app** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **2** hours spent in total

## User Stories

The following **required** functionality is completed:

- [v] User can **compose and post a new tweet**
  - [v] User can click a “Compose” icon in the Action Bar on the top right
  - [v] User can then enter a new tweet and post this to twitter
  - [v] User is taken back to home timeline with **new tweet visible** in timeline
  - [v] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
  - [v] User can **see a counter with total number of characters left for tweet** on compose tweet page

The following **optional** features are implemented:

- [ ] User is using **"Twitter branded" colors and styles**
- [ ] User can click links in tweets launch the web browser 
- [ ] User can **select "reply" from detail view to respond to a tweet**
- [ ] The "Compose" action is moved to a FloatingActionButton instead of on the AppBar
- [ ] Compose tweet functionality is build using modal overlay
- [ ] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [x] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
- [ ] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft. If saved, the draft should then be **persisted to disk** and can later be resumed from the compose view.
- [ ] Enable your app to receive implicit intents from other apps. When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet. 

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src=![SimpleTweetPart2](https://user-images.githubusercontent.com/80604127/135705223-403fae55-9670-416e-94ca-e027dd245f7d.gif)
width=250><br>



## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


### User Stories

#### REQUIRED (10pts)

- [v] User can sign in to Twitter using OAuth login.
- [v] User can view the tweets from their home timeline.
	- [v] For each tweet, show the relevant information: the tweet body along with the author's username and name
	- [v] User should be displayed the relative timestamp for each tweet "8m", "7h"
- [v] User can refresh tweets timeline by pulling down to refresh (i.e pull-to-refresh) 
#### BONUS

- [v] User can view more tweets as they scroll with infinite pagination.
- [ ] Improve the user interface and theme the app to feel "twitter branded".
- [ ]Replace all icon drawables and other static image assets with vector drawables where appropriate.
- [ ] Links in tweets are clickable and will launch the web browser.
- [ ] User can tap a tweet to display a "detailed" view of that tweet. (1 point)
- [ ] User can watch embedded video within the tweet.
- [ ] User can open the twitter app offline and see last loaded tweets.
	- [ ] Tweets are persisted into sqlite and can be displayed from the local DB
- [ ] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.

### App Walkthough GIF

<img src="https://user-images.githubusercontent.com/80604127/134796505-effa0dd3-0dff-498d-8cc2-46eba6cbec0a.gif" width=250><br>

### Notes

Describe any challenges encountered while building the app.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android!
