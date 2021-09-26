## SimpleTweet
SimpleTweet is an Android app that permits users to view their Twitter timeline using Twitter REST API.
Time spent: 5 hours
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
