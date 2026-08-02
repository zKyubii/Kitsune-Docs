# Privacy Policy — Kitsune Bot

**Last updated:** 2 August 2026

This document explains what data Kitsune Bot ("the bot") stores, why, and how
to have it removed. By adding the bot to a Discord server you agree to this
policy.

## What the bot stores

The bot stores the minimum needed to work. All data is tied to a Discord
server and is kept on a private server (VPS) controlled by the developer.

| Data | Why |
|---|---|
| Server, channel, role and user IDs | To know where to post and who to act on |
| Server configuration | Your dashboard settings (log channels, ticket panels, level rewards, enabled features…) |
| XP and level counters | The levelling system |
| Warnings — reason, moderator, optional proof link | Moderation history, shown with `/warnings` |
| Temporary ban expiry | To unban automatically, even after a restart |
| Ticket metadata — who opened it, when, its number, who claimed it | Ticket management and limits |
| Confessions — the text and the author's ID | Anonymous confessions are anonymous **to other members**, not to the server staff or the developer: the author is recorded so abuse can be traced |
| Content created by admins — embeds, greeting messages, scheduled messages | These are features whose whole point is to store what you wrote |
| Partnership message IDs | To delete the messages if the author leaves |

## What the bot does NOT store

- **The bot does not log or store general chat messages.** It reads message
  content in real time (for anti-spam, the counting game, levelling and
  auto-reactions) but does not save it.
- **Ticket transcripts are not stored.** They are generated in memory when a
  ticket is closed and delivered to the channel the server admin chose. No copy
  is written to disk by the bot.
- No email addresses, no IP addresses, no payment information.

## Privileged intents

The bot uses the **Message Content** and **Server Members** intents. They are
required for: anti-spam and auto-moderation, the counting game, the levelling
system, auto-reactions on keywords, welcome/leave messages, and ticket
transcripts.

## Data sharing

Data is **not** sold, shared or transferred to third parties. It is not used
for advertising or profiling.

## Retention and deletion

- Removing the bot from a server stops all collection for that server.
- To have a server's stored data deleted, contact the developer (below) with
  the server ID. Requests are handled manually.
- Individual users can ask for their own records (XP, warnings, confessions)
  to be removed from a server they are in.

## Changes

This policy may change as the bot gains features. The date at the top is
updated when it does.

## Contact

Join the [support server](https://discord.gg/gndDzYbYv3), or contact the developer on
Discord (**Kyubi**).
