---
layout: help
title: "Live Streaming"
---

# Live Streaming

SideoutCam can stream the game live, with the scoreboard and sponsors, to **YouTube**, **Facebook**, or any **RTMP / RTMPS** service (Twitch, Restream, ...). Streaming is separate from recording: you can stream, record, or both.

The stream goes out over whatever internet connection the camera phone has, like any other app:

- **Joined to a Wi-Fi network** (the school's Wi-Fi, or a **Personal Hotspot** from another phone): the stream uses that Wi-Fi.
- **Not joined to any network:** the stream uses the camera phone's **cellular** connection. Keep Wi-Fi switched on anyway: the two phones need it to talk to each other, even without joining a network.
- **Joined to a Wi-Fi network that asks you to sign in** (a sign-in or "accept terms" page) or has no internet: the stream may fail to start or keep dropping. Sign in first in Safari, or forget that network and use cellular or a hotspot.

You need a good connection: about 3.5 Mbps upload for 720p, or 6 Mbps for 1080p. The quality adjusts automatically on a weak connection. Choose the quality in Home ▸ **Live Streaming ▸ Quality**. Streaming makes the phone work hard: over a long game, a Wi-Fi network or another phone's Personal Hotspot keeps the camera phone cooler than its own cellular ([Keeping the Camera Phone Cool](12-Keeping-the-Phone-Cool.md)).

## Setting up

Home ▸ **Live Streaming** shows each team's setup (use **Team** at the top to switch between your teams).

### YouTube

1. In **Accounts**, sign in to YouTube with the account that manages the channel.
2. The channel must be enabled for live streaming. The first time, YouTube can take up to 24 hours to approve it (YouTube Studio ▸ Create ▸ Go live).

That's all. When you go live, Sideout creates the broadcast for you (Unlisted, Sports category, titled like "20261004 Westview vs. Eastside") and gives you a link to share. No stream key needed.

An optional **YouTube backup key** (YouTube Studio ▸ Create ▸ Go live ▸ Stream) is only used if creating the broadcast fails.

### Facebook

1. In Facebook **Live Producer**, choose where to post (your profile, a Page, or a Group), pick **Streaming software**, and turn on **Persistent stream key**.
2. Copy the key. In Sideout, go to **Accounts ▸ Stream Keys ▸ Add Stream Key**, choose **Facebook**, and paste it.
3. In **My Teams ▸ the team ▸ Live Streaming** (or Home ▸ Live Streaming), pick the key for the team.

A persistent key stays the same every time, so you only do this once. Facebook may show a preview first: tap **Go Live** in Facebook to make it public.

### Other services (Custom RTMP)

Add a **Custom RTMP** stream key with the service's **server address** (e.g. `rtmps://…/app`) and **stream key**, then pick it for the team.

## Going live

Tap **Go Live** on the camera screen. If the team has more than one destination set up, **Go Live…** lets you pick YouTube, Facebook or Custom.

In SideoutTally it works the same way: with one destination set up, **Go Live** shows which one and goes live there. With more than one, **Go Live…** opens a list (YouTube, Facebook, Custom RTMP) with a tick on the one you used last; tap where to go live. (An older SideoutCam on the camera phone always uses the destination you last went live with.)

- **Between sets**, the stream stays up and shows a card: "Starting soon", "Waiting for Set 2 to start", or "Final". These cards are only on the stream, never in your recordings.
- **When you pause**, viewers see "Stream paused momentarily" with the game and the reason (e.g. "Westview timeout") or your message.
- **Share link** (YouTube) gives you the link to send to family and friends, on either phone.
- **End Stream** finishes the broadcast. Recording isn't affected.

## Weak signal and dropped connections

- **Weak signal:** when the connection can't keep up, the stream lowers its quality by itself, and viewers see a notice across the top: *"Weak network signal. Stream may appear choppy and could stop. Stream will remain active in case signal strength improves."* It disappears once the signal recovers. Both phones show **Weak signal** next to LIVE. Your recording is never affected.
- **Connection lost:** Sideout keeps trying to reconnect every 10 seconds, and both phones show **Reconnecting — signal lost**. On YouTube the broadcast stays open, so viewers keep the **same link** and the stream picks up where it left off when the signal returns. Tap **End Stream** to stop trying.
- If SideoutCam has to restart mid-game, **Go Live** again for the same game continues the same YouTube broadcast and link.
- **YouTube's view of the stream:** while you're live on YouTube (signed in through Accounts), the Live row on both phones shows how YouTube rates the stream and how many are watching, e.g. "YouTube: Good · 23 watching", checked every 30 seconds (the same rating as Stream health in YouTube Studio, so you don't need Studio open). It turns orange or red with YouTube's reason ("YouTube says: Video bitrate is low") when YouTube rates it OK or Bad. If it says Good while a viewer sees a spinner, the stream is fine and the hold-up is on their connection: they can pick a lower quality (gear icon) or rewind a few seconds. Not shown for Facebook or stream-key streams.
- **Phone too hot:** pause the stream with a message for viewers, then resume on the same link once it cools. See [Keeping the Camera Phone Cool](12-Keeping-the-Phone-Cool.md).
- If the stream can't start at all (for example, a stream key was rejected), Sideout tells you why instead of retrying.
