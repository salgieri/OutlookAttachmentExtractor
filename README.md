## Synopsis

This AppleScript is used to:

* Export files from email messages
* Update the text of the email with a local and web-based location
* Remove files from emails

## Configuation

There are five core variables to change to match your environment:

- savePathStr - The location you want the files stored locally on your disk
- uriPath - The base URI path of the web-based sync folder of the local files. Leave this blank if you don't have a web UI for the local file sync
- ignoreSuffix - Any file suffixes you want to ignore for extract
- ignorePrefix - Any file prefixes you want to ignore for extract
- minSizeforExport - The minimum filesize to extract (regardless of prefix or suffix ignore)

## Usage

Select multiple messages in Outlook that you want to strip the attachments from. Click run in the script editor.

Check that the files are in the right place, and that the messages have been updated correctly with the new locations.

## Motivation

Attachments in email messages consume the majority of space within a users quota.

Many business impose a limit on their users inbox, leading to failed message delivery.

