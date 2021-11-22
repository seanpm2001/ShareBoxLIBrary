
***

# Service list for ShareBox

This directory houses XML data related to the various sites that ShareBox supports. These lists are to be retrieved by the ShareBox library itself.

The goal is to document each site as well as possible. Currently there are only 8 fields of metadata, which include:

`<name>` - The name of the service

`<url>` - The link to the service (webpage only, the sharing link has not been implemented yet)

`<privacyFriendly>` - Info on if the site respects user privacy or not

`<owner>` - The current owner of the site

`<ctype>` & `<vctype>` - The content type of the site (`<vctype>` is in use for software development sites, it stands for Version Control Type. It was replaced with `<ctype>` which stands for content type)

`<active>` - A yes, no, or unknown for if the site is still active or not

`<start>` - The start year of the site (when it was first launched)

`<end>` - The end year of the site (this should remain `nil` for newer entries, and should be removed when the site is no longer active for 1 year or longer, and should be commented out/put in an area people can't access as easily)

More tags will be added in the future.

## Volunteers needed

I can't maintain all the XML data here. A lot of entries are currently only plain text, and this project needs an additional maintainer to help out.

***

***This file was last edited on 2021 November 21st at 10:20 pm***

***
