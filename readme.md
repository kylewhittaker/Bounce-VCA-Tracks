# Bounce VCA Tracks in a Pro Tools session

This script will go through each VCA in a Pro Tools session, solo it, bounce it, and then move on to the next. The current version is customized for my setup (_theExcluded_, _getStemName_) but it's easily modified to work with yours.

## Requirements

- Solo setting must cancel out previous solo
- Edit window needs to be the main window at the time of bounce. (This can be adapted to your setup though.)
