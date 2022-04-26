# Sakura Room 
![SakuraLogo](https://user-images.githubusercontent.com/104222482/165376125-fc8f7719-8a64-4754-aa31-fbdb1623dafd.png)

## Task One Introduction 
This room is designed to test a wide variety of different OSINT techniques. With a bit of research, most beginner OSINT practitioners should be able to complete these challenges. This room will take you through a sample OSINT investigation in which you will be asked to identify a number of identifiers and other pieces of information in order to help catch a cybercriminal. Each section will include some pretext to help guide you in the right direction, as well as one or more questions that need to be answered in order to continue on with the investigation. Although all of the flags are staged, this room was created using working knowledge from having led and assisted in OSINT investigations both in the public and private sector. 

In addition to the TryHackMe points, if you are able to complete this room you may also request a special badge at the OSINT Dojo by submitting proof of your accomplishment. (Note: You may only request this special THM badge if you have already obtained at least the OSINT Dojo Student level first.)

Once you have completed this room you may submit a badge request here.

NOTE: All answers can be obtained via passive OSINT techniques, DO NOT attempt any active techniques such as reaching out to account owners, password resets, etc to solve these challenges.

If you have any other questions, comments, or suggestions, please reach out to us at @OSINTDojo on Twitter.

## Task Two Tip-Off
The OSINT Dojo recently found themselves the victim of a cyber attack. It seems that there is no major damage, and there does not appear to be any other significant indicators of compromise on any of our systems. However during forensic analysis our admins found an image left behind by the cybercriminals. Perhaps it contains some clues that could allow us to determine who the attackers were? 

We've copied the image left by the attacker, you can view it in your browser here.
## Instruction
Images can contain a treasure trove of information, both on the surface as well as embedded within the file itself. You might find information such as when a photo was created, what software was used, author and copyright information, as well as other metadata significant to an investigation. In order to answer the following question, you will need to thoroughly analyze the image found by the OSINT Dojo administrators in order to obtain basic information on the attacker.

This is the image that was left by the attacker. 

![Sakurapwnedletter](https://user-images.githubusercontent.com/104222482/165377362-4bd3bf2d-1232-4dd7-bc9f-0254a26847f5.png)

The first question asks us the username that the attacker goes by.

Utulizing the development tools in the browser we were able to find the username of the attacker

![Username](https://user-images.githubusercontent.com/104222482/165377908-acef432c-03bc-4c04-8cac-4c6e37716e9c.png)

## Task Three Reconnaissance
It appears that our attacker made a fatal mistake in their operational security. They seem to have reused their username across other social media platforms as well. This should make it far easier for us to gather additional information on them by locating their other social media accounts.

Most digital platforms have some sort of username field. Many people become attached to their usernames, and may therefore use it across a number of platforms, making it easy to find other accounts owned by the same person when the username is unique enough. This can be especially helpful on platforms such as on job hunting sites where a user is more likely to provide real information about themselves, such as their full name or location information.

A quick search on a reputable search engine can help find matching usernames on other platforms, and there are also a large number of specialty tools that exist for that very same purpose. Keep in mind, that sometimes a platform will not show up in either the search engine results or in the specialized username searches due to false negatives. In some cases you need to manually check the site yourself to be 100% positive if the account exists or not. In order to answer the following questions, use the attacker's username found in Task 2 to expand the OSINT investigation onto other platforms in order to gather additional identifying information on the attacker. Be wary of any false positives!
