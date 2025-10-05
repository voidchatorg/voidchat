# [Voidchat: Free Anonymous Chat Rooms with File Sharing](https://voidchat.org)

Voidchat is an [anonymous chat](https://voidchat.org/chat) platform that doesn't require registration or an account. Match with random strangers based on common interests (similar to Omegle) or create your own chat room for private & group chats.

Voidchat retains messages, enabling conversations to be resumed later exactly where they left off. It also supports file uploads and media sharing, including images, documents, and other types of content.

![omegle alternatives](/images/voidchat-talk-to-strangers.png)
*random chat is still wip*

## Features

  - **Persistent Chat History** - Conversations are saved, allowing you to continue discussions even after disconnecting.
  - **File Uploads & Image Sharing** - Share images, video & voice clips, or other files during conversations. Max upload size is 10MB (per file).
  - **Ephemeral File Storage** — Files/images shared in a room expire after 3 days.
  - **Custom Emojis** - Supports most Discord emojis ([Twemoji](https://github.com/jdecked/twemoji)) and emoji shortcodes (e.g., `:joy:` `:eyes:` `:sob:`) and a selection of popular meme emojis (`:kekw:` `:gigachad:`)
  - **Emoji Reactions** (testing) - React instantly to messages with fun and expressive emojis.
  - **Message Replies** (testing) - Keep track of context by replying directly to specific messages.
  - **Temporary Chat Rooms** (testing) - Create rooms that automatically expire after a set time, perfect for short-term conversations.
  - **Omegle Style Random Chat** (wip) - Match with strangers randomly and anonymously based on shared interests.
  - **Password Protected Rooms** (wip) - Secure private rooms with a password so only invited users can join.
  - **Customizable Chat UI** – Personalize chat rooms with custom themes, background images, and colors.
  - **Community Rooms** – Join public chat rooms for countries, topics, or general discussions with strangers worldwide.

<img src="/images/voidchat.org_iphone_12_pro.png" width="240" alt="mobile chat">

*mobile ui*

## [Temporary Chat Rooms](https://voidchat.org/temporary-chat)

Voidchat now supports temporary chat rooms for ephemeral conversations.
Messages and uploaded files in these rooms are automatically deleted 10 minutes after they are sent.
Each room is assigned a random name for better privacy.

[Read more in the blog post](https://voidchat.org/blog/introducing-temporary-chat-rooms-on-voidchat)

## Public Chat Rooms

  - [General Chat](https://voidchat.org/v/general)
  - [Vent Chat](https://voidchat.org/v/vent) - [A chat for anonymous venting](https://github.com/voidchatorg/voidchat/wiki/A-Chat-for-Anonymous-Venting)
  - [UK Chat](https://voidchat.org/v/uk)
  - [Russia Chat](https://voidchat.org/v/russia)
  - [Germany Chat](https://voidchat.org/v/germany)
  - [France Chat](https://voidchat.org/v/france)
  - [Hungary Chat](https://voidchat.org/v/hungary)
  - [Denmark Chat](https://voidchat.org/v/denmark)

## Privacy and Data Handling

  - **No Registration Required**: Users can join chat rooms without creating an account.
  - **Data Collection**: Minimal data is collected, such as IP addresses and timestamps, primarily for abuse prevention.
  - **Data Retention**: Access logs are retained for a maximum of seven days.
  - **Data Security**: All data is encrypted with SSL/TLS during transmission, file uploads and database backups are also encrypted in cold storage.

## Credits

Voidchat is built on open-source software:

  - [Astro](https://astro.build) - fast and lightweight web framework
  - [Svelte](https://svelte.dev) - reactive UI components
  - [uWebSockets](https://github.com/uNetworking/uWebSockets) - high-performance networking
  - [SQLite](https://www.sqlite.org) - simple, efficient database
  - [Bun](https://bun.com) - modern JavaScript runtime
