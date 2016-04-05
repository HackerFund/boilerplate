# aribot
Simple tweepy scripts for automated Twitter interactivity.

In the spirit of Twitter, [follow me](http://twitter.com/imariari)!

__I'll be making some base use-case templates for you to use...stay tuned!__

## requirements

To run any of these scripts, you'll need:
- [python](https://www.python.org/downloads/)
- [tweepy](https://github.com/tweepy/tweepy) (`pip install tweepy`)
- [Twitter app and keys](https://apps.twitter.com/), with appropriate permissions (usually read and write)

## templates

__samplekeys.py__ is the place for your Twitter keys. If you put your project on Github, remember to .gitignore.

__autotweet.py__ reads lines from a text file and tweets from your bot's account at specified intervals. To run: `python autotweet.py yourtextfile.txt`
