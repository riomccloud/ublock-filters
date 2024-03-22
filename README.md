# uBlock filters
My personal list of uBlock Origin's filters, made with the purpose of debloating the web and improving user experience. Some were made to work together with [Redirector](https://github.com/einaregilsson/Redirector)'s rules, look at them on the correspondent items.

## Installation
1. Copy the raw file URL(s) of the filter(s) you want to use
2. Open uBlock Origin's settings, go to "Filters lists" tab, roll down to "Import..." and paste the URLs, one per line
3. (Optional) Install the Redirector web browser extension and setup the suggested redirect rules

## Available filters

### Bluesky
Made for artists and anyone that just use the service for posting content, and don't want to waste time into timelines and social network nonsense. Removes access to the main page and superfluous buttons, leaving alone only notifications, moderation, profile and settings. Posts can be done with the button at the left.

#### Redirector's rules
**Example URL:** `https://bsky.app/`\
**Include pattern:** `https://bsky.app/`\
**Redirect to:** `https://bsky.app/profile/your.profile`\
**Apply to:** Main window (address bar), HistoryState

![Bluesky interface example with filters enabled](https://raw.githubusercontent.com/riomccloud/ublock-filters/testing/screenshots/bluesky.jpg)

### Facebook
Removes the large banners in header and footer that beg for the user to login or create an account, covering large parts of the screen.

![Facebook interface example with filters enabled](https://raw.githubusercontent.com/riomccloud/ublock-filters/testing/screenshots/facebook.jpg)

### GitHub
Removes unwanted content blocks from the right side of the homepage.

### Instagram
Removes good chunks of visual pollution from profiles and posts, alongside overlays and banners that beg for the user to login or create an account, covering large parts of the screen.

![Instagram interface example with filters enabled](https://raw.githubusercontent.com/riomccloud/ublock-filters/testing/screenshots/instagram.jpg)

### Mastodon
Made for artists and anyone that just use the service for posting content, and don't want to waste time into timelines and social network nonsense. Removes access to the main page and superfluous buttons, leaving alone only notifications, private mentions and settings. Posts can be done with the widget at the left.

> [!IMPORTANT]
> Since there are a multitude of instances, you need to manually paste the filter list content into your uBlock Origin's "My filters" and replace your.instance with your instance's URL.

#### Redirector's rules
**Example URL:** `https://your.instance/home`\
**Include pattern:** `https://your.instance/home*`\
**Redirect to:** `https://your.instance/@yourprofile`\
**Apply to:** Main window (address bar), HistoryState

![Mastodon interface example with filters enabled](https://raw.githubusercontent.com/riomccloud/ublock-filters/testing/screenshots/mastodon.jpg)

### X/Twitter
Made for artists and anyone that just use the service for posting content, and don't want to waste time into timelines and social network nonsense. Removes access to the main page and superfluous buttons, leaving alone only notifications, private messages, profile and settings. Posts can be done with the button at the left.

#### Redirector's rules
**Example URL:** `https://twitter.com/home`\
**Include pattern:** `https://twitter.com/home*`\
**Redirect to:** `https://twitter.com/yourprofile`\
**Apply to:** Main window (address bar), HistoryState

![X interface example with filters enabled](https://raw.githubusercontent.com/riomccloud/ublock-filters/testing/screenshots/x.jpg)

### YouTube
Removes unrelated content from searches.
