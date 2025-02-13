# Send Mail
> Send an email with Gmail and Python, use OAuth flow


# Why OAuth?

Use the OAuth flow to sign into your Gmail account in the browser and then do requests using a token, so that your Gmail password does not have to be entered in a config file or stored somewhere on your machine. 

Also, once you authenticate the first time, your credentials will be cached for future runs.

## Instllation

1. Make sure to follow the step to enable API for Gmail and download a JSON file.
1. Clone the project.
1. Install Python.
1. Install dependencies in virtual environment.
    ```sh
    $ pip install requirements.txt
    ```

## Usage

1. Run the script.
    ```sh
    $ python -m sendmail
    ```
1. Follow the auth flow.

## Links

Based on Gmail dev docs tutorial:

- https://developers.google.com/gmail/api/quickstart/python

See also tutorial which uses a less secure approach and requires you to allow less secure apps.

- https://realpython.com/python-send-email/

See other sample scripts for Google suite.

- https://github.com/gsuitedevs/python-samples
