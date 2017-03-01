
# Ruby API Wrappers

<p>This is just a small set of limit scope API wrappers I use on a regular basis for tasks related to data mining and web scraping. These wrappers are by no means all-inclusive in terms of implemented features, I have only created classes & methods for the API functions I use. </p>

<h3> Reddit (reddit.rb) </h3>

Before using this module, you'll need to get an app ID and secret from https://www.reddit.com/prefs/apps (click "Are you a developer?").  

Example:

```
client = Reddit::Client.new(options = {
  :user => "JohnDoe", 
  :pass => "MyPassword123", 
  :id => "App-ID", 
  :secret => "App-Secret"
})

```
