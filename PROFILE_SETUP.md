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

- `assets/guild-card.svg` is a custom anime fantasy guild-card banner.
- `assets/hunter-sigil.gif` is a tiny generated animated GIF used as profile flair.

Both assets are custom and intentionally avoid official game artwork or borrowed anime GIFs.
