# Reddit Video Maker Bot 🎥

All done WITHOUT video editing or asset compiling. Just pure ✨programming magic✨.


</picture>

</a>

## Video Explainer

## Motivation 🤔

These videos on TikTok, YouTube and Instagram get MILLIONS of views across all platforms and require very little effort.
The only original thing being done is the editing and gathering of all materials...

... but what if we can automate that process? 🤔

## Disclaimers 🚨

- **At the moment**, this repository won't attempt to upload this content through this bot. It will give you a file that
  you will then have to upload manually. This is for the sake of avoiding any sort of community guideline issues.

## Requirements

- Python 3.9+
- Playwright (this should install automatically in installation)

## Installation 👩‍💻

1. Clone this repository
2. Run `pip install -r requirements.txt`

3. Run `python -m playwright install` and `python -m playwright install-deps`

**EXPERIMENTAL!!!!**

On MacOS and Linux (debian, arch, fedora and centos, and based on those), you can run an install script that will automatically install steps 1 to 3. (requires bash)

`bash <(curl -sL https://raw.githubusercontent.com/elebumm/RedditVideoMakerBot/master/install.sh)`

This can also be used to update the installation

4. Run `python main.py`
5. Visit [the Reddit Apps page.](https://www.reddit.com/prefs/apps), and set up an app that is a "script". Paste any URL in redirect URL. Ex:google.com
6. The bot will ask you to fill in your details to connect to the Reddit API, and configure the bot to your liking
7. Enjoy 😎
8. If you need to reconfigure the bot, simply open the `config.toml` file and delete the lines that need to be changed. On the next run of the bot, it will help you reconfigure those options.

(Note if you got an error installing or running the bot try first rerunning the command with a three after the name e.g. python3 or pip3)

If you want to read more detailed guide about the bot, please refer to the [documentation](https://luka-hietala.gitbook.io/documentation-for-the-reddit-bot/)

## Video

https://user-images.githubusercontent.com/66544866/173453972-6526e4e6-c6ef-41c5-ab40-5d275e724e7c.mp4

## Contributing & Ways to improve 📈

In its current state, this bot does exactly what it needs to do. However, improvements can always be made!

I have tried to simplify the code so anyone can read it and start contributing at any skill level. Don't be shy :) contribute!

- [ ] Creating better documentation and adding a command line interface.
- [x] Allowing users to choose a reddit thread instead of being randomized.
- [x] Allowing users to choose a background that is picked instead of the Minecraft one.
- [x] Allowing users to choose between any subreddit.
- [x] Allowing users to change voice.
- [x] Checks if a video has already been created
- [x] Light and Dark modes
- [x] NSFW post filter

Please read our [contributing guidelines](CONTRIBUTING.md) for more detailed informat
