# slackleford
slackleford is a modified version of my other bot [MUMfoRd](https://github.com/HuggableSquare/MUIMfoRd)  
but, this bot's job is to bridge mumble chat into slack  
it also will pm you a list of people in the mumble server when it get the message "users"
how do use
---------
your first job is to create a realtime messaging api bot on your slack team and get the api key  
once that's done plug it into the script appropriately  
other than that just make sure you have a "#mumble" channel on your slack team for the bot to message into  
dependencies
---------
- [ruby](https://www.ruby-lang.org/en/)
- [mumble-ruby](https://github.com/mattvperry/mumble-ruby)
- [slack-api](https://github.com/aki017/slack-ruby-gem)
TODO
----
- make a better readme
- setup a gemfile
- fix image base64 issue
