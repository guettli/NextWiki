# Goal of NextWiki

NextWiki should be a Wiki that can be easily integrated into [Nextcloud](//nextcloud.com).

It should provide the usual "Term --> Content" mapping which Wikis provide.

Every term should automatically be a hashtag that can be used in different places (chat, markdown, ...).

This way it should be very easy to link between wiki pages and between chat messages and wiki pages.

## Example

Alice is new at Foo Company and she asks Bob in the chat:

Alice> Hi Bob, how are holiday requests handled at Foo Company?

Bob> See #Vacation

The hashtag "#Vacation" should be rendered as a hyperlink to the wiki page "Vacation". There Alice can read how holiday requests are handled at Foo Company.

## Per #Term

For every term/page:

* The URL should be nice.  
 Example: `https://example.com/wiki/Vacation` (not `https://example/wiki?page=37a8b992e9ff`)
* Changes are versioned: a log of "who edited what" exists
* It should be possible to see the difference between two versions.
* A version can get a label (example "version 1.0")

## Use cases

* Company/Family wide knowledge base
* Defining Responsibilities/Ownership (for example for an ISO-9001 certification)
* ...

## Combine file-tagging with #hashtags?

NextCloud already provides [file-tagging](https://docs.nextcloud.com/server/18/user_manual/files/access_webgui.html#tagging-files) maybe it would simplify a lot if both lists of terms get combined.

In personal context: Imagine you have a dog called "Wuffi". You could create a wiki page "Wuffi". This automatically makes a tag "Wuffi" available. Then you could tag your foto of your dog with the tag "Wuffi". If you show your friend a foto with the tag "Wuffi" (via Nextcloud), the user could click on the tag and he gets to the wiki page of the dog. There you can add more details. Like dog breed, date of birth, ...

In a business context: Imagine there is an import project. Let's call it master-plan. You could tag files with "master-plan" and simultaneously create a wiki page for it. All employees involved can find and share #master-plan easily. The wiki pages contain all a list of all files with the tag (auto-created) and the manual content created by users.

## Related

* [Intranet Wiki Guidelines](https://github.com/guettli/intranet-wiki-guidelines)

## Problem: I can't programm PHP

I have no clue who to implement this in PHP/Nextcloud.
