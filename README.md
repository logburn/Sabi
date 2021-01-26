# Sabi
A self-hostable, federated, and encrypted Snapchat alternative. The app will be open source and private. Hopefully publishing to F-Droid/IzzyOnDroid and Play Store. Currently, I plan to use PGP for encryption.
**Please note**: Do not hold your breath for this to be released, I am learning Android development to create this.

## Guiding principles
 1. user-friendly and simple UI
 2. "hide" the encryption for ease of use
 3. "Minimum Viable Centralization" - only store information on a server as a midpoint to increase stability
 4. federation and self-hostability
 5. no reinventing the wheel

## Planned resources
 - the [Undraw](https://undraw.co/) library of SVGs
 - PGP for both encryption and user verification, using [KotlinPGP](https://github.com/Tlaster/KotlinPGP)
 - [iconmonstr](https://iconmonstr.com/) icons
 - either a custom backend or [ActivityPub](https://activitypub.rocks/) if I decide to "officially" federate
 - [Parse](https://parseplatform.org/) application stack
 - IF ads are encorporated, (which will always be fair and optional in some way), [Carbon](https://www.carbonads.net/) looks the best to me. options for ad models include:
   - free ad-supported model with donation-based add-free version on play store (freemium) with ad-free F-Droid app
   - opt-in ads (ads off by default, can turn on to support project)
   - "pro" features (such as black-theme in addition to the free dark-theme)

## Planned features
#### Text chat
 - messaging
 - encryption
 - robust texting (link previews etc)
 - file uploads (images, maybe documents)
 - delete after x time
 - sending/send/viewed visual
 - picture editing (markers and such, maybe filters)

#### Picture chats
 - picture chats
 - picture editing (markers and such, maybe filters)
 - content warnings (nsfw, custom?)
 - show for x time
 - replays
 - stories
 - send to multiple people
 - text labels
 
#### Accounts
 - accounts
 - account sharing via link and QR code
 - profile info
 - online status (green, yellow, white)
 - account backup/moving (online and local)
 - deletion
 - account age
 - profile info (short paragraph)
 
 #### Misc
 - custom app color
 - lowercase/uppercase letters
 - streaks
 - allow/disallow screenshots at conversation level

## Under consideration

#### Likely, but not guaranteed
 - location sharing (live?)
 - save to gallary
 - profile pictures (unsure how to implement)
 - multiple stories with limits on who can view
 - opt-in, privacy-friendly, ads
 - group chats
 - website companion 
 - time delayed sending

#### Unlikely, but possible
 - public stories
 - account locking
 - P2P/Bluetooth messaging
 - sort contacts (friends, acquaintances, family, etc)
 - multi-person viewing, must view at same time to see message
 - multiple accounts
 - iOS support (very unlikely)
 
 ## Project roadmap (likely to change)
 #### 0.1
  - messaging
  - encryption
  
 #### 0.2
  - robust texting
  - custom deletion time
  
 #### 0.3
  - accounts
  - account sharing via link
  - account deletion
  - account age in profile
  
 #### 0.4
  - picture chats
  
 #### 0.5
  - streaks
  - sending/sent/viewed visual
  
 #### 0.6
  - account sharing via QR code
  - profile info (short paragraph)
  - content warnings (nsfw, custom?)
  
 #### 1.0
  - changeable time picture/chats are viewable for
  - replays
  - file uploads (images, maybe documents)
  
 #### 1.1
  - stories
  - custom app color
  - lowercase/uppercase letters
  
 #### 1.2
  - online status (green, yellow, white)
  - account backup/moving (online and local)
  - send to multiple people
