# ProPresenter Library

A Mac app for organizing and tidying ProPresenter 7 libraries. Browse every presentation, check them against a house style, archive what you no longer use, and clean up titles and section names across the whole library, with a backup and undo for every change.

**Download ProPresenter Library 0.1.0:** [Apple silicon](https://github.com/youngkwangk/propresenter-library-downloads/releases/download/v0.1.0/ProPresenter-Library-0.1.0-arm64.zip) · [Intel](https://github.com/youngkwangk/propresenter-library-downloads/releases/download/v0.1.0/ProPresenter-Library-0.1.0-x86_64.zip) · [Release notes](https://github.com/youngkwangk/propresenter-library-downloads/releases/tag/v0.1.0) · [Report an issue](https://github.com/youngkwangk/propresenter-library-downloads/issues)

## Download and install

| Computer | Download |
| --- | --- |
| Mac with Apple silicon (M1 or later) | [ProPresenter-Library-0.1.0-arm64.zip](https://github.com/youngkwangk/propresenter-library-downloads/releases/download/v0.1.0/ProPresenter-Library-0.1.0-arm64.zip) |
| Mac with an Intel processor | [ProPresenter-Library-0.1.0-x86_64.zip](https://github.com/youngkwangk/propresenter-library-downloads/releases/download/v0.1.0/ProPresenter-Library-0.1.0-x86_64.zip) |

Open the ZIP and drag **ProPresenter Library** to **Applications**. **Apple menu → About This Mac** shows your chip or processor. The app needs macOS 14 Sonoma or later, and is signed and notarized by Apple.

## Updates

The app checks for updates every six hours. Choose **ProPresenter Library → Check for Updates…** to check now. It shows what's new and installs only when you say so.

## What it does

- **Browse** every library in your ProPresenter workspace. Search by title, author, CCLI number or lyrics, and preview slides.
- **Check a house style**: fonts, text size, lines per slide, CCLI numbers, section names and colors. Apply the style to many presentations at once, after seeing every change.
- **Archive or move** presentations to another library. Playlists that use them follow to the new location.
- **Last used** dates from your dated playlists and ProPresenter's own records, with lists of what hasn't been used in a while.
- **Categories** such as worship songs, hymns and sermons, sorted by Apple Intelligence on your Mac.
- **Clean Up** titles and section names with the Codex CLI, if you have it. You approve each suggestion.
- **Find duplicates** by title or CCLI number.
- **Live view**: with ProPresenter's network setting on, see what's live and follow along.

## Your library is safe

- Nothing changes until you choose to apply it, and you see each change first.
- Every change backs up the original files first. **History** undoes any batch.
- The app won't change files while ProPresenter is open, so quit it first.

## Privacy

Your library stays on your Mac. Categories use Apple Intelligence on your Mac, and the live view talks only to your own ProPresenter. The one exception is **Clean Up**, which sends titles or section names, never lyrics, to OpenAI through the Codex CLI, and only when you click **Get Suggestions**.

## Requirements

- macOS 14 Sonoma or later, and ProPresenter 7
- **Categories**: macOS 26 or later, Apple silicon, and Apple Intelligence turned on
- **Clean Up**: the [Codex CLI](https://github.com/openai/codex), installed and signed in

ProPresenter Library is an independent app. It isn't made by or affiliated with Renewed Vision, the maker of ProPresenter.
