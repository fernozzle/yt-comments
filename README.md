# yt-comments
YouTube comment getter. Currently very bad!

* 7 levels of indents bad!
* Everything in one file bad!
* Doesn't request more than one page of replies bad!
* And much more!

## What it does

This page uses the YouTube API to get the content and author channel ID of every last comment on a YouTube video, regardless of its moderation status *or* YouTube's unreliable website UI.

It attempts to retrieve all comments that are:

* Published
* Held for review
* Likely spam

If you're not logged in or the video you're requesting doesn't belong to the account you're logged into, only published comments will be counted.

As listed above, it doesn't count more than one page of replies to a top-level comment (100 replies). That is an obvious bug, but for our purposes it was okay.
