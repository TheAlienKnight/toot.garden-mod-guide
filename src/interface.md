## The Moderation Interface

### Reports
This is the first tab that will open when you go to the moderation menu. It's where you can see any reports that have been sent from people on toot.garden, and from other instances reporting someone on toot.garden. The tabs are pretty straightforward, they switch between reports that have been handled, and not, and it allows you to sort between local and remote reports.

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/d4f8bb51-f47b-4598-9d9b-a70cebe9386e)

An example of what a report would look like, with a resolved report being an example:

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/2edee867-c856-441e-9fc5-f64144df33d0)

Once you click on the report, you are brought into a menu for that specific report.

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/9feff8b1-8a96-4004-ab09-be0f11d8dbae)

The image above is only half the report, but it is mostly self explanitory given the helpful breakdown provided by Mastodon itself. A helpful thing to note, is that if the account is remote, it displays the "Joined" date as when toot.garden first became aware of it's existance. Last active will also be blank if the account is not local.

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/ad153f4e-63ea-474f-97cf-a329724d08fc)

The image above is the last half of the report. It allows moderators to add more posts the report for proper paper trails, and it allows notes to be written by moderators that explains the actions taken, or actions not taken. The audit log maintains a track record of what "power" actions were taken by *any* of the staff members. It should be noted, that here since I am the admin of the instance, I can see the "delete" button on the notes section. Normally, other moderators cannot delete other moderators notes- and for good reason.

_____

### Invites
This functionality in the moderation menu really just allows for moderators to create invite links (if not publicly enabled), and to deactivate anyones invites should that need to happen for whatever reason.

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/b7e45b68-4bcc-49dd-b6ff-bdd53c5dbdf6)

_____

### Follow Recommendations
This is likely something that many people are curious about, and or didn't even know existed. This section allows for manual suppression of follow recommendations on a server wide basis. Toot.garden *does not* currently have any suppressed recommendations. This action should only take place if it is an account that is not necessarily breaking rules, but is posting in some manner that is deemed detrimental to the experience of other people. Moderators on toot.garden should contact AJ first before performing this action, or to suggestion this action.

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/4c17b77b-a51a-4473-bdb6-c0495e9ccd9e)

_____

### Federation
This is a *very* powerful tool, that impacts everyone on the server. This tool allows you to add domain suspensions, limits, and so forth. This action should only be taken if a large section of a remote server is actively engaged in rule breaking actions/postings, or is continually failing to federate properly. On toot.garden, all federation actions are made public. I believe they should be, as those on the server should know what content they can and cannot view, and they should have the freedom to make a choice about whether to stay on toot.garden or not.

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/56fe35a0-e69d-4f30-a476-26aa631bda61)

In the image above, the interface is simple, and clicking on the pill-shaped entry just brings up a list of information about the remote server. 
It may be helpful to note that at the current moment, for a domain to be put on the "Unavailable" list, it has to be manually added. Generally, most remote servers recover. An example of what displays on a domain in regards to federation is below. If a domain has been failing multiple times, (ideally across 7+ consecutive days), moderators are asked to purge the domain. Additionally, if the domain has been suspended, and for some reason the account data was not deleted within the usual timeframe, moderators can purge the domain manually.

![image](https://github.com/TheAlienKnight/toot.garden-mod-guide/assets/88284489/8795cdd0-13a0-4634-86f5-0bfe1704d5ef)
