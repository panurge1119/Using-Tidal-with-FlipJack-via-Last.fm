# Using Tidal with FlipJack via Last.fm

FlipJack displays your currently playing song using **Last.fm scrobbling**. Tidal supports Last.fm natively — once connected, FlipJack will automatically show whatever you're listening to in Tidal.

This guide walks you through every step, from creating accounts to seeing your first track on the board.

---

## What You'll Need

- An Apple TV with the FlipJack app installed
- A Tidal account (any plan)
- A free Last.fm account
- The Tidal app installed on at least one device (iPhone, iPad, Mac, Windows PC, or Android)

---

## Step 1 — Create a Last.fm Account (skip if you already have one)

1. On your phone or computer, open a browser and go to **[last.fm/join](https://www.last.fm/join)**.
2. Enter a username, email address, and password, then click **Create account**.
3. Verify your email address if prompted.
4. Make a note of your **Last.fm username** — you'll need it in Step 3.

> **Important:** Your Last.fm profile must be set to **Public**. If it is private, FlipJack cannot read your scrobbles.
>
> To check: go to [last.fm/settings/privacy](https://www.last.fm/settings/privacy) and make sure **"Hide recent listening information"** is turned **off**.

---

## Step 2 — Connect Tidal to Last.fm

This tells Tidal to report every song you play to Last.fm (called "scrobbling").

### On iPhone or iPad
1. Open the **Tidal** app.
2. Tap your **profile icon** in the top-left corner.
3. Tap **Settings** (gear icon).
4. Scroll down and tap **Integrations**.
5. Tap **Last.fm**.
6. Tap **Connect** and sign in to your Last.fm account when prompted.
7. After signing in, you should see a green checkmark or "Connected" confirmation.

### On Mac or Windows (Tidal desktop app)
1. Open the **Tidal** desktop app.
2. Click your **profile name** in the top-right corner.
3. Click **Settings**.
4. Click **Integrations** in the left sidebar.
5. Under **Last.fm**, click **Connect**.
6. A browser window will open — sign in to Last.fm and click **Allow access**.
7. Return to the Tidal app. You should see "Last.fm: Connected".

### Verify it's working
1. Play any song in Tidal.
2. After 30–60 seconds, go to **[last.fm/home](https://www.last.fm/home)** and check your **Recent Tracks**.
3. If your song appears there, scrobbling is working correctly.

---

## Step 3 — Set Up Last.fm in FlipJack

1. On your Apple TV, open **FlipJack**.
2. From the Main Menu, select **Settings**.
3. Select **Music Source**.
4. Select **Last.fm**.
5. A setup screen will appear. Using the on-screen keyboard, enter your **Last.fm username** (the one you created in Step 1).
6. Select **Test & Save**.
   - If you see **"✓ Connected!"** — you're all set. FlipJack will return to the Main Menu automatically.
   - If you see an error, see the [Troubleshooting](#troubleshooting) section below.

---

## Step 4 — Launch the Display

1. From the Main Menu, select **Launch**.
2. Play a song in Tidal on any of your devices.
3. Within **5–30 seconds**, the song title, artist, and album will appear on the split-flap board.

> **Why the delay?** Last.fm typically takes 5–30 seconds to reflect a new track after Tidal starts playing it. This is a Last.fm server delay, not a FlipJack issue. Once the track registers, FlipJack will pick it up on its next 3-second poll.

---

## Troubleshooting

### "Username not found or profile is private"
- Double-check that you typed your Last.fm username correctly (usernames are case-sensitive on some systems, though Last.fm is generally forgiving).
- Make sure your profile is **public**: [last.fm/settings/privacy](https://www.last.fm/settings/privacy) → turn off **"Hide recent listening information"**.

### FlipJack shows the wrong song or a previous song
- Last.fm has a 5–30 second reporting delay. Wait a moment — the display will update on the next poll.
- If the display is stuck on an old song, make sure Tidal is actually playing (not paused).

### FlipJack shows nothing even though Tidal is playing
1. Confirm Tidal is connected to Last.fm (go back through Step 2).
2. Go to [last.fm/home](https://www.last.fm/home) and check **Recent Tracks** — if your song isn't appearing there, the issue is with Tidal's scrobbling, not FlipJack.
3. Some songs (podcasts, DJ mixes, or very short tracks) are not scrobbled by Tidal. Try a standard album track.
4. Make sure you've played the song for at least **30 seconds** — Last.fm only scrobbles a track after you've listened to a meaningful portion of it.

### FlipJack shows "nothing playing" after I stop Tidal
- This is expected behavior. Last.fm only marks a track as "now playing" while it's actively being scrobbled. Once you pause or stop, FlipJack will return to the idle animation within a few seconds.

### I changed my Last.fm username
- In FlipJack, go to **Settings → Music Source → Last.fm** and tap **Change Username** to update it.

---

## Notes for Other Streaming Services

Last.fm scrobbling works the same way for many other services. The setup steps in Tidal above apply equally to:

| Service | Where to find the Last.fm setting |
|---------|----------------------------------|
| **Qobuz** | Profile → Connections → Last.fm |
| **Spotify** | Settings → Social → Connect to Last.fm |
| **Apple Music** | Use the [Scrobbler for Last.fm](https://apps.apple.com/app/scrobbler-for-last-fm/id1299887439) app on iPhone, or the macOS Last.fm desktop app |
| **Deezer** | Settings → Connected Apps → Last.fm |
| **Amazon Music** | Not supported natively — use a third-party scrobbler |

Once any of these services is connected to Last.fm and scrobbling, FlipJack will display your now-playing track automatically — no additional setup needed.
