# Send Mail
> Send email with Gmail and Python using OAuth, to protect your password


# Why OAuth?

Use the OAuth flow to sign into your Gmail account in the browser and then do requests using a token, so that your Gmail password does not have to be entered in a config file or stored somewhere on your machine.

Based on Gmail dev docs tutorial:

- https://developers.google.com/gmail/api/quickstart/python


## Instructions

1. Make sure to follow the step to enable API for Gmail and download a JSON file.
1. Install dependencies in virtual environment.
1. Run the script.
1. Follow the auth flow once to sign into Gmail.
1. Run the script again and your previous details will be referenced from the store.


## Other

See also tutorial which uses a less secure approach and requires you to allow less secure apps.

- https://realpython.com/python-send-email/

See other sample scripts for Google suite.

- https://github.com/gsuitedevs/python-samples
