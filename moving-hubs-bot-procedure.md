# Moving the Hubs Bot
*For Hubs Foundation (Volunteer) Staff*

Having Discord and logging into a Discord account is currently a **requirement** for participants attending a Hubs Foundation-hosted meetup. We have a Discord bot interacting with our Hubs called "Hubs Bot". We find many benefits from our Hubs Bot including participant attendance tracking and chat routing to a channel in Discord.

Occasionally, there are reasons to *not* meet in a Hubs Foundation meeting space or we receive requests from participants who want to attend a meeting but *do not want to use a Discord account*. Sometimes, Hubs Foundation meetings are held in non-Hubs Foundations-hosted spaces. These procedures help move Hubs Bot in whole or in part.

The Hubs Bot has three possible states:
1. Bridged but not bound
2. Bound but not bridged
3. Both bound and bridged

The default state for a bound room is that third state, to be both bound and bridged.

## To Move Hubs Bot to a Non-Bound Room
1. Receive a request fron a non-Discord-having attendee.
2. Non-Discord meetup room *on the same server* could be used.
3. Email back to the user, including a link to the non-Discord room.
4. Post announcement of change of location.
5. Update the header link in the Meetup channel. This allows for the Hubs Bot chat notifications/messages.
6. Edit the even in Hubs Events if there is time to add the new link.
7. Post an extra announcement within the Discord meetup channel.

## To Move to a Non-Bound but Bridged Room on Another Server
1. Receive a request fron a non-Discord-having attendee.
2. Select a non-bound, bridged room *on another server* for the meetup.
3. Email back to the user, including a link to the room.
4. Post announcement of change of location.
5. Update the header link in the Meetup channel. This allows for the Hubs Bot chat notifications/messages.
6. Turn off Hubs Bot.
7. Switch configuration at backend to use new/other instance, bridged to new room.
8. Edit the even in Hubs Events if there is time to add the new link.
9. Post an extra announcement within the Discord meetup channel.


Sources:

[GitHub Hubs Foundation hubs-discord-bot repository](https://github.com/Hubs-Foundation/hubs-discord-bot)