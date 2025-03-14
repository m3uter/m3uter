[![image](https://github.com/user-attachments/assets/bde94e84-1db4-49d9-91e6-6939857a96e4)](https://app.m3uter.com/)

# A simple (hopefully) easy to use M3U editor and EPG assignment tool.

A few ways to interact with this project:
- Here (of course)
- https://www.reddit.com/r/m3uter_com/
- https://www.youtube.com/@M3Uter

## Disclaimer

This app is in very early stages and still needs a ton of work.

It's entirely possible things are broken, functionality missing, incorrect assumptions made, etc.  

In effect, it's a very early alpha release.

## Feedback

Any feedback would be welcomed and appreciated.

Please open an [!issue](https://github.com/m3uter/m3uter/issues) here, post on the [!subreddit](https://www.reddit.com/r/m3uter_com/), or comment on [!youtube](https://www.youtube.com/@M3Uter).

## Legal Disclaimer: Unauthorized Streaming of Copyrighted Content

The use of Internet Protocol Television (IPTV) services to access, distribute, or stream copyrighted content without proper authorization is illegal and may result in severe legal consequences. Copyright laws, including but not limited to the Digital Millennium Copyright Act (DMCA) in the United States, the Copyright, Designs and Patents Act in the United Kingdom, and similar statutes in other jurisdictions, strictly prohibit the unauthorized reproduction, distribution, or public performance of copyrighted works.

Engaging in the unauthorized streaming of copyrighted content via IPTV services may constitute copyright infringement, which can lead to civil penalties, fines, and potential criminal prosecution. Legal consequences may include but are not limited to:

- Civil Liability – Content owners may pursue legal action, leading to significant financial damages and court-ordered injunctions.
- Criminal Charges – In some jurisdictions, willful copyright infringement, especially when done for commercial gain, can result in criminal prosecution, fines, and even imprisonment.
- ISP Actions – Internet Service Providers (ISPs) may monitor and restrict access to illegal streaming services, issue warnings, or terminate service agreements.

To ensure compliance with copyright laws, users should only access IPTV services that have obtained proper licensing agreements from content owners and rights holders. Engaging with unverified IPTV providers that offer unauthorized access to copyrighted material carries substantial legal and financial risks.

If you are unsure about the legality of an IPTV service, consult with a legal professional or verify its licensing status with relevant copyright authorities.

## Why?

Have you noticed the TV programming information is frequently missing?  That's because the channel in your list (M3U file, Xtreme codes, etc) is NOT found in whatever EPG you're using.  One of two things is probably happening.

The channel ID value is mis-matched, or missing altogether.

![image](https://github.com/user-attachments/assets/e135a74b-ad79-4bad-9374-c31cda054f64)

This app will map the channel to the EPG.

![image](https://github.com/user-attachments/assets/967e7ea9-69f1-4af9-ab03-08fb854b0519)

## EPG Source

At the moment, the EPG sourced from https://epgshare01.online/, using their full source.  This EPG contains more than 20K channels and more than 2M programming entries.

Future plans will allow uploading your own EPGs.

## How to Use

### Register (requires valid email)

Registration with a valid email is required, check your spam box if you don't see the email confirmnation.

### Load your lists 

A physical m3u file, Xtreme codes, or a link to your M3U file can be uploaded.

M3U Urls are tested for Xtreme codes compatibility and converted to Xtreme codes automatically if possible.

![image](https://github.com/user-attachments/assets/cca37dcc-a128-45a1-89e4-ff63e315c88b)

Upon uploading a M3U file, the app automatically maps any matches in your list and the EPG.  It also attempts to automap all sports League channels.

**There are a few output links to consider.**

- M3U (Favs Only) - This link only contains your edited list
- EPG - This link contains all channels mapped to the EPG
- Link Below your Edited M3 list item - This is a complete reworked M3U file, since the app assigns channel ids where one doesn't exist

### Editor

Left column will contain all detected groups.  By selecting a group, all the channels within that group will be shown in the middle column.

The search box will also be enabled.  Alternatively, select "ALL GROUPS" to perform global searches.

**Note**: Search at the moment is single term.  Wildcard searches will be implemented soon.

![image](https://github.com/user-attachments/assets/53fd886d-a58a-4103-9799-a1bcb32ebddd)

Selecting a channel (in middle column) will display EPG search form, typing in a channel name will search through the EPG and present options (if found).

**Note**: Search at the moment is single term.  Wildcard searches will be implemented soon.

![image](https://github.com/user-attachments/assets/8da9052f-d9eb-4fe7-82c3-a1038de3aaf3)

Selecting an EPG item will map the EPG channel to the selected Channel:

![image](https://github.com/user-attachments/assets/b1421efc-867c-4528-aa12-4c7d19268f17)

Press the >> button to add to your Edited List, channels added to Edited List will appear in the "MyFavorites" group.

![image](https://github.com/user-attachments/assets/4679fdb1-435c-4b2b-a2ba-0903d58936d1)

Drag and drop channels in the Edited List to reorder.


## Output to player

Load your list output link and EPG to your favorite IPTV player:

![image](https://github.com/user-attachments/assets/4447ce2c-d93b-48a6-8fbb-4adfc1c9f1be)







































