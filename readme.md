# Anki HTTP Status Cat

## What is this ?

This is a [Anki](http://ankisrs.net/) deck to learn HTTP Status Code using the
funny [HTTP Status Cats](http://httpcats.herokuapp.com/).

## Instructions

You actually only need the `.apkg` file. Download it and then import it in your
Anki application.

I had trouble importing it directly into the Android App. I had to import it in
the desktop app and then synchronize it to my Android device (be sure to check
the *Fetch media on sync* checkbox if you do so).

## How was it done ?

The pictures are [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/) and
the [website](http://httpcats.herokuapp.com/) exposes the pictures with simple
url.

I just had to use `wget` to download them all, then `convert` to crop them to
remove the text. Then I had to manually add them to a new deck using the Anki
desktop tool. All in all it took me about 2 hours, while I was waiting for my
train.
