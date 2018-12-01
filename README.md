# Slack Me

## Usage

Send a message passed as an argument, or in stdin, to a single Slack
account.

`sleep 300; slackme -m '5 minutes have passed'`

`slackme < id_rsa.pub`

## Link to your account

This is a little Go project, link in your Slack API creds and the
community+user where you want to be notified, and compile a binary
that you can then toss onto whatever computer(s) you want.

It is extremely important that you create an API token which only has
permissions to create the message!

