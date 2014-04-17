##How To Fix Typos

You have 60 seconds to edit your last message. Hit UP arrow to edit.

Here's a detailed post on the topic: http://kato.quora.com/Dealing-with-typos-in-Kato

##Mentions

Type @Bob to get Bob's attention.

If Bob is offline, he will get an email.

If Bob replies to the email, the reply will be posted back to Kato.

Type @Everybody to get everybody's attention.

Using @Everybody in a restricted room will only be visible to members of that room.

##Room Search

The magnifying glass icon in room header reveals the search pane.



Use @@Bob to search for everything Bob said. @@Bob feature will return everything Bob said that contained the world "feature".

##Off The Record

Clicking the lock icon above text input puts the room in "off the record" mode. All messages sent in this mode bypass the database and do not cause unread counter to increase.

All parties must have the room open to see off-the-record messages.

Lock

This mode could be used to lower security risks while sharing passwords and other sensitive information.

Off-the-record messages are displayed with a red side marker:

Red marker

##Global Search

The magnifying glass icon in upper right corner of the app revleals the global search pane.

Global search

Without any search terms the pane shows the last message in 1-1s and rooms, most recent on top.

##Noise Management

###Per-room noise management

Hover over room name to reveal the settings gear. Click to open room settings, locate Notifications tab. Earch room (not 1-1) has three levels of noise control:

Enable notifications; enable unread counter
Disable notifications; enable unread counter
Disable notifications; disable unread counter
Even if a room has notifications and unread counter disabled, mentions of you will cause a red unread counter to appear.

###Sound

Sound notifications are disabled by default. To enable sound notifications, open account settings (gear in upper right area) and enable the Sound notifications checkbox.

When enabled, a light pop sound announces the arrival of private messages or mentions of you.

###Organization default noise level

When new members are added to organizations with many active rooms, it's often easier for newcomers to enable notifications in the few rooms of interest to them, as oppose to disabling notifications for all rooms that aren't so interesting.

Admin-only: to make notifications disabled by default, open organization settings, navigate to the Notifications tab, and check "Disable notifications".

To access organization settings, click on this button in the upper right corner of the app: Org settings

##Kato Roll

Turning on Kato Roll will activate your webcam and take a picture of you every minute. Kato Roll appears as small thumbnails of your coworkers who also have the feature enabled at the top of Kato.

To enable this feature, go to Account, Options, and toggle Kato Roll. You'll also see options to blur your photo, select the size of Kato Roll, and add a color effect. After enabling, you should see something like this at the top of the screen:



##Layout

Kato supports up to four simultaneous conversations on one screen (eventually this number will be configurable, à la tmux).

Rooms move from right to left, older ones getting dropped off. It's possible to "pin" a room to prevent it from disappearing — use the pin icon in the room header, next to the x, it works as a toggle.

Search

If panes in all four positions are pinned, pins do nothing.

##Room Switcher

If you have several conversations, it's possible to switch between them with Ctrl ~ (tilde, above Tab). Note that this may not work with certain keyboard layouts (e.g. Russian).

##Markdown

Use the M icon above message input to enable Markdown rendering for your messages.

See this post for more details: http://blog.kato.im/m-for-markdown/

##Code

Use the </> to enable "code" rendering for your messages. This means fixed-width font and syntax highlighting.

##File Sharing

It's possible to share files via Dropbox or Kato (both use Amazon S3).

You can use these file sharing buttons above text input: File sharing

It's also possible drag and drop files into text input.

In Google Chrome, it's possible to copy and paste images into text input.

If you're using Kato file sharing (not Dropbox), keep in mind that the resulting URLs are public, but impossible to discover (like unlisted YouTube videos).

##Message Controls

Hover over a message to reveal message controls:

Message controls

It's possible to collapse or expand a message, or change the way it is rendered (between plain text, Markdown, or code). These settings are not persistent at the moment.

##Restricted Rooms

Admin only: when creating a room, you can mark the room as restricted. Restricted rooms are only visible to those members who are explicitly listed in room access, as well as all admins.

Admin only: when inviting a new member, it's possible to limit the invitation to a set of restricted rooms only.

Note: It is not possible to convert restricted rooms into unrestricted and vice versa. This is on the roadmap.

##Public Rooms

It's possible to open a regular (unrestricted) room to the outside world with the Public Room integration.

To learn more about this feature, see this blog post.

##Ad Hoc Rooms

We make a special Support room for every new team that signs up. Having our customer support tool built into our internal communication tool is invaluable so we made it available for our customers.

To learn more about this feature, see  this blog post.

##Colorful People

Kato randomly picks a color (out of 12) and assigns it to each new member upon arrival in your organization. After the 12th person, everyone is gray (first color from the left). It's possible reassign a member's color at any time.

Colors

##Integrations

Each room could be configured to receive notifications from dozens of services.

Integrations

###HTTP Post API

To post messages to a room with HTTP POST, follow the instructions for the HTTP POST integration

##Mac App

Download Mac App

Corresponding blog post: http://blog.kato.im/announcing-kato-mac-app-beta/

##Mobile Apps

Coming soon.
