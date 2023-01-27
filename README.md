# rocketchat.chatgpt##
# This is a test dev at the moment. I am using rocketchat outgoing webhook to trigger a python script. Then, I am storing the rocketchat request in a MONGO ATLAS db that then exports the user's last 20 interactions with chatgpt and key information about the user so the interaction seems natural. I export this doc into a python object so its available to chatgpt without any searching. Once chatgpt responds, i take the response and add to the db. The resposne then is sent back via rocketchat rest api to the original user. ##

## Any feedback let me know.##

