# Profile Setup

This profile is ready for dynamic stats. GitHub widgets work immediately after the repository is public. WakaTime needs one extra secret.

## Enable Daily Time Tracking

1. Create or log in to a WakaTime account.
2. Install the WakaTime plugin in VS Code.
3. Copy your WakaTime API key from WakaTime account settings.
4. In this GitHub repo, add a repository secret:

```text
Name: WAKATIME_API_KEY
Value: your WakaTime API key
```

5. Go to Actions, open `Profile Metrics`, and run it manually once.

After that, the README section between:

```text
<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
```

will update every day with coding time, languages, editors, operating system, projects, commits by time of day, and days-of-week activity.

## Visual Assets

- `assets/profile-banner.png` is the main GitHub profile banner with text on the left and the poster artwork as the background/right-side visual.
- `assets/data-runner-poster.gif` is the low-fi anime data-runner poster artwork.
- `assets/data-runner-poster.png` is the higher-quality source version of the poster.

The visual direction is custom and uses the dark teal/orange print-poster palette without using official game artwork or borrowed anime GIFs.
