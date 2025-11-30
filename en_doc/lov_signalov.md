---
layout: default
title: Signal Hunting
lang: en
---

# Signal Hunting

* TOC
{:toc}

Signal hunting is one of the advanced activities and is suitable for players who already have some experience with the game, have at least basic mining, processing, and component production running. Signal hunting is relatively simple if the player has a properly built and equipped ship.

> **Warning:**  
> New players basically *do not need* to hunt signals to kick-start their career, earn money, and stop suffering from shortages.  
> Players can get everything they need (at least for the first weeks of play) even *without hunting signals* (e.g. buying on NPC stations or from other players).  
> Signals are usually hunted for blueprints of *advanced* or otherwise unavailable modules, weapons, and other items that new players can safely ignore during their first days and weeks.

---

## A tip to start with

The best modules for signal hunting are, without debate, the *Scioplex Lambda* antennas. Very often, complete newcomers ask experienced players for blueprints to produce them, or even for finished modules.

**DON'T DO THAT!!!**

You can get to Lambdas on your own, through your own effort and step by step. It won’t be immediate, it’ll be a bit more demanding, but that’s what Outspace is about. The only thing you’d save is your own gameplay and the joy coming from it. Getting Lambdas by your own means is relatively simple and fast.

---

## Building and equipping the ship

A ship for signal hunting must be able to scan signals in space and download as many of them as possible, in the shortest possible time. It also needs to travel relatively long distances to reach distant signals. In this case, the flight speed (and length) is not critical.

This means that a signal hunting ship must be *lightweight*, have *enough energy* for long flights, and at the same time must carry *as many antenna modules as possible* for downloading signals.

### Basic modules

- **Command module:**  
  Pathfinder MPCM

- **Propulsion:**  
  Scioplex nuclear propulsion, or Heidberg H1

- **Warps:**  
  The lightest you have available (ideally Scioplex Terminal MK3) and only as many as needed to enable warp on the ship.  
  Usually 1–2 warp modules are enough. I recommend checking [Source](https://source.outspacegame.com/en/spacecraft/modules/list/&tag=warp) and comparing the mass of warp modules you have available so you can pick the lightest ones.

- **Batteries:**  
  One, ideally two TransPlan battery modules (they are light). If you don’t have these modules yet, QFE modules will do as well (but they are heavier).

- **Solar panels:**  
  Since we’re taking only a few heavy batteries, we must recharge them during flight. So add 2–4 solar panels to the ship (Scioplex Solar M1 or later Scioplex Solar M2).

### Antenna modules

Antennas are modules that allow you to scan space and download signals. Better modules allow you to scan more distant signals and see weaker ones.

With weaker antennas, you will only see strong signals (usually containing basic or not very rare blueprints), and scanning will only work on nearer signals. A larger number of antennas makes it possible to download signals in parallel (for example, with five antennas, you can download 5 different signals or 5 copies of the same signal *at once*).

Each signal download needs its own free *production slot* (keyboard shortcut `W`). So if you have 5 antennas on the ship but only 3 free production slots, you can only download 3 signals at the same time.

As mentioned above, the goal is to obtain *Scioplex Lambda* antennas. These are fairly rare and can only be bought occasionally. On the other hand, regular Scioplex antenna arrays or, even better, Scioplex double antenna arrays can be commonly purchased at NPC stations (you can find them via Tradelink, keyboard shortcut) for affordable prices.

A ship equipped with 6× Scioplex double antennas will definitely be enough to let you find and download a signal that contains the blueprints for building Scioplex Lambda antennas yourself.

### Astronauts

Astronauts are the main bottleneck when searching for signals. You need *many* astronauts who are *trained* in *science* (science modifier – that’s the last number in the TES stat) at least up to the maximum level of the antenna. This is exactly why it’s recommended to start with simpler antennas (they require **fewer** astronauts) and work your way up to Lambda gradually.

**Example:**  
A Lambda antenna has a maximum science modifier limit of 96, which means that *each* module should be staffed with **four** astronauts with `S >= 96`!

> **Warning:**  
> Only mount antennas on the ship that are **fully staffed with astronauts**!  
> That means if you have an antenna module staffed with only a partial number of astronauts, it’s better to *temporarily remove it* and only mount it once you can fully staff it!

> _**Big warning:**_  
> Robots are made – surprise – of metal, and metal **DISRUPTS** most signals.  
> Robots should be forbidden from even approaching a signal-hunting ship!  
> On such a ship, do not staff **ANY** position in any module with a robot, and do not even *transport* a robot on such a ship (even unassigned to a station).  
> Naturally, this only applies if you plan to hunt and download signals.

> **Tip:**  
> No one knows why, but it seems astronauts with the profession **MEDIC**, assigned to antenna modules, do their job better than other professions…

---

## Searching for and scanning a signal

Signals can also be hunted ad-hoc. Just fly a “bit” away from the station (the station is also made of metal!) and look at the list of signals you can detect. Such a signal can be downloaded immediately.

The problem is that, in most cases, you have a specific reason for hunting a signal – you need to find a blueprint for a specific module, weapon, or other item. Therefore, you first need to find such a signal and then get to it.

We always search for and scan signals while docked at a station where we’re allowed to recharge energy. Scanning is very energy-intensive and the ship’s energy supply (in battery modules) is limited.

> **Tip:**  
> Personally, I scan while docked at my own station, which has plenty of energy.  
> Before I start scanning, I *temporarily* throw about 8–10 battery modules onto the ship, which I keep in storage.  
> This is **ONLY** for scanning purposes; afterwards I *return* the batteries to storage!

### Scanning procedure

1. Dock at the station, mount the batteries, and fully recharge the ship.
2. Switch to the Sector Map (spacebar).
3. Adjust the view so you can see something (zoom out and rotate, e.g. towards the center of the system).
4. Turn on signal display (the top icon from the trio on the left side).

   ![](../assets/images/lov_signalov_images/2025-11-27-12-10-53.png)

5. After the signals appear, move the *bottom slider* until *smaller data* signals are shown.

   ![](../assets/images/lov_signalov_images/2025-11-27-12-13-40.png)

   As you move the slider, the currently shown signal types are displayed at the top of the screen.  
   We’re looking for this:

   ![](../assets/images/lov_signalov_images/2025-11-27-12-15-40.png)

6. Use the top slider to set the display intensity.  
   For weak signals isolated in deep space, you’ll need to turn the level almost to maximum, but within a solar system this view will be overexposed.
7. We can only fully scan a signal (i.e. see “what it contains”) when our ship detects it at 100%.  
   Anomalies weaker than 100% cannot be properly scanned by our astronauts, and we won’t learn what blueprints are hidden in them.  
   This means that when you move your cursor over one of the “dots” (these are anomalies the signals consist of), you must see something like this:

   ![](../assets/images/lov_signalov_images/2025-11-27-12-29-32.png)

8. Right-click on the dot and select **Scan anomaly** from the context menu.  
   At the same time, pay attention to the distance to the anomaly to check whether it’s actually realistic to fly there.

   ![](../assets/images/lov_signalov_images/2025-11-27-12-40-47.png)

9. The following window will open, where we’ll scan the anomaly (or, more precisely, the signal).

   ![](../assets/images/lov_signalov_images/2025-11-27-12-42-52.png)

10. It’s important to notice the following details:

    - the anomaly contains a data signal (the tall vertical light-blue bar in the histogram),
    - when you hover the cursor over this signal, a small window appears where you can see:
      - the number of signals passing through this anomaly (two in our case),
      - the energy cost to scan each signal (665 EU in our case).

11. We scan the first and every subsequent signal in this anomaly (we cannot choose the order) by simply clicking on the given histogram bar.  
    After each click, the signal is scanned, the ship loses the specified amount of energy, and the scan result is shown.

    If we hover over the individual components of the signal (in our case just one), we see the name of the item whose blueprint the given signal contains:

    ![](../assets/images/lov_signalov_images/2025-11-27-12-50-13.png)

    > **Tip:**  
    > If there are still unscanned signals left in the anomaly:
    >
    > ![](../assets/images/lov_signalov_images/2025-11-27-12-54-57.png)
    >
    > but the ship no longer has enough energy to scan them:
    >
    > ![](../assets/images/lov_signalov_images/2025-11-27-12-55-21.png)
    >
    > you’ll appreciate the fact that you’re still docked at the station.  
    > **KEEP THE SCAN WINDOW OPEN** and do the following to recharge the ship and finish scanning all remaining signals:
    >
    > - press `Esc` (don’t worry, the window won’t close) and the view will switch from the Sector Map back to the standard view,
    > - you can grab the open scan dialog window with the mouse and move it to the side so it doesn’t get in the way (don’t close it!),
    > - enter the Hangar and recharge the ship,
    > - then drag the scan window back to the center of the screen and finish scanning,
    > - you can repeat this process again and again.

12. Once you finally find what you were looking for, we need to create a *WAYPOINT* to the given anomaly, otherwise you’d have to search for it again.  
    While still in the scan window, there is a button at the *bottom right* to **Create waypoint**.

    After pressing it, a window appears where you can enter your own name.  
    I **RECOMMEND** including the signal number that is still shown in the content window of that signal (87553 in our case), so I’ll save the waypoint under the name `87553_HLO-HIVE`. Leave the waypoint as private for now, because it shows only the *anomaly*, not the exact optimal place for *downloading the signal*.

    ![](../assets/images/lov_signalov_images/2025-11-27-13-10-21.png)

13. The last step of preparation is *planning* the route, i.e. choosing the station from which it’s optimal to start.  
    Close all open scan windows, switch off signal display, and open the Sector Map.
14. Open your list of waypoints (the circled icon in the right-hand list), find your waypoint, and click it:

    ![](../assets/images/lov_signalov_images/2025-11-27-13-21-47.png)

15. The Sector Map will automatically *center* on the waypoint.  
    Your task is, by rotating (right mouse button) and panning (left mouse button) the map, to find the station of your region that is closest to the waypoint.

    If you’re not sure, feel free to find several candidates; we’ll test them later.  
    The goal is to find a station to which you can instantly jump using a stasis card and from which the waypoint is the closest (we’re optimizing flight length).

    ![](../assets/images/lov_signalov_images/2025-11-27-13-26-46.png)

**Done**, the preparation for the hunt is complete.  
Don’t forget to **remove** and **offload** the extra battery modules (leave at most 1–2 on the ship) and **fully recharge** the ship!

---

## Beginning the flight to the signal

If you have a waypoint created, the signal number written down (ideally in the waypoint name), no unnecessary batteries or robots on the ship or in its cargo hold, and the ship is fully charged, you’re ready to start the hunt.

1. Use a stasis card (or something else, if you want more realism) to travel to the station you chose as the starting point.  
   If you have several candidate starting stations, visit them one by one.  
   Don’t dock at the station, just stay somewhere nearby.
2. Open the Sector Map again, open your waypoint list, and click your waypoint.  
   In the context window that opens, notice the distance to the waypoint from the current station.

   ![](../assets/images/lov_signalov_images/2025-11-27-13-37-55.png)

   If you have multiple candidates, repeat these two steps for each one and find the station closest to your waypoint.
3. If the signal is strong enough, or not too far away, there’s a chance you’ll see it in the list of signals.  
   If your current signal-hunting ship is selected (keyboard shortcut `M`), click the antenna icon in the bottom menu:

   ![](../assets/images/lov_signalov_images/2025-11-27-13-41-53.png)

4. A list of signals detected by your ship (i.e. by the astronauts on board) will open on the right:

   ![](../assets/images/lov_signalov_images/2025-11-27-13-43-23.png)

   Try to find your signal in the list by its number.  
   If the station’s interference is too strong, it’s worth flying (without warp!) “a few kilometers” away (in any direction) and trying again.
5. If you manage to find the signal, use the `>>` icon in that window and the ship will automatically fly towards the *optimal spot for downloading the signal*.

   > **Warning:**  
   > This spot can differ significantly from your waypoint, but don’t panic.  
   > In most cases, it’s more accurate (though still not perfect) than your waypoint.

6. If you can’t find the signal in the list, that’s fine. It’s either too weak or too far away.  
   Simply start flying directly towards your waypoint and we’ll fine-tune the final target over time.

---

## Monitoring the signal during flight

### Changing the target during flight

Changing the target only applies if you’re flying from the starting station directly towards the waypoint. In that case, it’s likely you won’t hit the position where you could download the signal at an optimal rate.

Therefore, while flying towards the waypoint, *regularly* check the signal list and watch for your signal to appear there. At that moment, I recommend waiting until the current “warp jump” finishes, or stopping warp near the end of it (watch the remaining time in the top-left corner), so you don’t waste energy unnecessarily.

Once your signal appears in the list and the current warp jump is about to finish (around 10–20 minutes remaining), stop the ship and use the `>>` icon in the signal list to send the ship to a more precise position for the signal. Then continue with regular checks as described in the “Ending the flight early” chapter.

### Ending the flight early

For most signals, it’s not necessary to fly straight “into the signal”.  
You need to keep in mind that even the best antennas need time to download a large amount of data.

Under **ideal conditions**, **1 MB** of signal takes **at least 12 minutes** to download.  
This means that downloading a signal of, say, 12 MB will (without card help) take at least `12 MB * 12 min = 144 min = 2 h 24 min`.

Once you see that your signal can be downloaded in such an “optimal” time, there’s no point in flying any further.  
At that moment, you should immediately stop the ship and start downloading.

It may even happen that continuing the flight would actually *increase* the download time!

The signal size and its download time from your current position (you can check this any time while warping!) can be seen in the signal list:

![](../assets/images/lov_signalov_images/2025-11-27-14-09-57.png)

For example, this signal can be downloaded immediately at optimal speed (20 MB in 4 hours), even though the ship is still more than 5.8 AU away from the signal!

If the download speed doesn’t reach at least 1 MB / 12 minutes, I recommend continuing the flight, or upgrading your antenna modules and/or staffing them with better-trained astronauts.

## Bonus: Signals in the Discord channel 'adura-channel'

A.D.U.R.A is a Discord chat bot that automatically displays important events in the game. At irregular intervals, it posts approximate positions of interesting signals in space. Each such message contains a link to a page that generates a private waypoint for that position.

> **Warning:**  
> Such a waypoint is also only approximate, so during the flight you will need more precise navigation according to the previous chapters.

Of course, the prerequisite for following these messages is to register and join the game's [Official Discord server](https://discord.com/invite/xrVe4fB) for Outspace.

1. Open Discord (either via a web browser or the Discord app) and find the `adura-channel`.
2. Look for relatively recent messages about detected signals.  
   A message looks approximately like this:

   ![](../assets/images/lov_signalov_images/2025-11-30-12-07-26.png)

   It’s important to notice the following details:
     - The signal ID number
     - The system in which the signal is located (for a beginner this is definitely **Sol** – the Solar System). Only look for signals in systems where you have stations and can actually get to them!
     - The contents of the signal – that is, the name of the item whose blueprint the signal contains.
     - The link to create the waypoint (*SAVE WAYPOINT*)

3. If a signal interests you, click the *SAVE WAYPOINT* link.  
   A new browser window (or tab) will open.  
   **DON'T CLICK ANYTHING**, just wait a moment and watch the screen.
4. After a while, information about the successful creation of the waypoint will appear in the upper middle part of the screen:

   ![](../assets/images/lov_signalov_images/2025-11-30-11-37-33.png)

5. You can close this window (or tab) and return to the original game window.
6. Open the Sector Map and display the list of waypoints.  
   At the very top you should see your new waypoint:

   ![](../assets/images/lov_signalov_images/2025-11-30-11-40-53.png)

7. I recommend clicking on the waypoint and using the context menu to *rename* it, for example in our case to *87854_Fasteners-GR5*.
8. From here, continue in the standard way as described above.
