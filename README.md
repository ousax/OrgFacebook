# Overview

Sometimes you wanna leave Facebook for your own reasons and you decide to delete it permanently but you don't wanna get rid of all those pictures you sent and received while using it.
Like Twitter and Google, Facebook also has this awesome feature to download a (html, json) file with all the folders (inbox, contacts, posts, stories ...) a complete copy of your Facebook account's activity. 
So all you need to do is open your browser and go to [here](https://accountscenter.facebook.com/info_and_permissions/dyi) .
After that you'll need  to submit and wait for it will take from hours to a day maximum depends on your Facebook account if it's an old account with a lot of groups, and media shared (videos). 
The script is so basic its just using a for loop to find (messages/inbox/folder/photos) folder then copies and renames (joins the conversation where that picture came from) all it's content (pictures) to another folder with only pictures.
- Uses regexp to find some pattens (Emails, Phone Numbers) inside specific conversation
- Extracts specific conversation to a txt file
- Extracts contacts

# Requirements 
bs4

# Installation

# Usage

python orgfacebook.py -f facebook-userId.zip 
