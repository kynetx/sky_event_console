# Kynetx Event Console

a console for raising and debugging events with the Sky API.

## Permissions Breakdown:

* Your tabs and browsing activity: The only access to tabs we need is for launching the oAuth Authorization page to the 3rd party oAuth provider.

* Your data on all websites: This is somewhat misleading, we ask for `*://*/*` access so that developers can make API calls to ANY URL ...

we don't collect any personal data and we don't want access to your data on all websites, we simply have to use that permission so developers can use the App on all urls.


## Features:

## Hat Tip:

* This was forked from Code in Chaos' RestConsole
