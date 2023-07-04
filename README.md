# email-automations
Useful email automation scripts.

My email process is to flag messages that are important to me.  I get a lot of emails that I can safely ignore, and since there are more unimportant ones than important ones, it takes less time to mark the important ones.

I wrote these 2 scripts to automate the process of cleaning up old unimportant emails.

They log into the IMAP server and remove unimportant emails (ones that are unmarked and old).

Each takes command line parameters for the IMAP server, username, password, and some optional paremeters for the destination folder and other IMAP params.

Feel free to use them and, if modifications are needed or they inspire any other similar scripts, pull requests are welcome.

I'm not sure what the future of this repo is, but perhaps making this a service at some point in the cloud would be useful to a less technical audience.
