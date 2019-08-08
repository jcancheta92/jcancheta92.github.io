---
title: "The Front Page of Reddit"
excerpt: "Using the Reddit API to collect data and analyze which subreddits appear more often on the front page of Reddit"
header:
  teaser: "/images/projects/reddit.png"
---

I wanted to experiment with using the Reddit API with the help of the Python Reddit API Wrapper(PRAW).

Reddit is a forum based community website that is broken up into even smaller communities that is dedicated to very specific topics. These smaller communities are called 'subreddits'. Within these subreddits, people around the world can post, vote, and comment. The subreddit url is always indicated by '/r/[subreddit]'

For this project, we will be exploring '/r/popular'. You could argue that this essentially the front page of Reddit as this is what a non-registed user will see when visiting the site. However, once users have registered an account, what each user see is a personalized front page that is compiled of all the subreddits that the user is subscribed to.

The '/r/popular' subreddit, while not technically a subreddit, is a collection of all popular posts of almost all subreddits. When I say 'almost,' that is because /r/popular filters out the NSFW subreddits.

I want to see what types of subreddits make it to /r/popular, so I will be exploring the submissions and its various attributes.

* [Exploring the Front Page of Reddit](https://github.com/jcancheta92/Exploring-Reddit-using-PRAW/blob/master/Exploring%20the%20Front%20Page%20of%20Reddit.ipynb)
