<!--
topic: Tech
date: 29 August 2022
-->

# My Experience with using a cheap extra chinese monitor

- [Cost](#orgbbaad19)
- [Review](#orgbf329fe)
- [Quality hack](#orgdd3b8a3)


After a lot of *fanboyism* / *evangelism* by my senior mentor and looking at some reviews on internet, I decided to get a second monitor to have my own dual monitor setup. Finally, I got a chinese off-brand monitor and have a dual monitor setup, its cheap, it works, I have had some issues and most importantly I discovered a secret trick to boost the quality by **a lot**. In this article i've recounted my experience with dealing with this *new* monitor.


<a id="orgbbaad19"></a>

# Cost

The price of monitors is quite expensive if you look at decent options, the least expensive branded option I could find was of Dell S21hn monitor, a 21 inch worth 21K NRS, whose 24 inch version is about 24k NRS.

Luckily, for just coding, I didn't need a decent monitor, just the one that worked and lasted at least 1 year.

I got a chinese "Zillion 19 inch" at just 6k. I was kinda impressed with the size given the price, the reason was that the price of monitor gets steep for size more than 19 inch.


<a id="orgbf329fe"></a>

# Review

My struggle began from putting it together, the monitor holder was pretty unconventional and minimal due to the price point so my youtube search didn't help, took me an hour to put it in place successfully, but there is no flexibility of angle, the holder looks like it was designed to support it but maybe it's my incompetence in putting it together idk.

The options were quite good, there are presets of brightness, contrasts and you can customize details yourself as well but it lacks the auto adjusting features so if you want to tweak the options you need to do a course on color and graphics i guess lol. I just switch the presets now and then and don't bother with other options.

One of my worrying part is the charging junction/regulator box. Compared to my laptop charger's one its looks very risky and heats up badly, I do have fears of it blasting up sometimes xd, tho i guess the worst that can happen is it getting overheated and ruining the inside circuits. This fear is partly why I religiosly remember to shut off the power completely when not in use, there is another reason in the next section.


<a id="orgdd3b8a3"></a>

# Quality hack

This was one of my greatest discovery with the monitor, I boosted the quality by a lot just by only turning the monitor's power on **after** logging in to Operating system (Windows and Linux).

When I initially used the monitor, I was kinda ok with the quality (I mean its 6k and for coding so meh). But i struggled too much in trying to set the resoulution settings. The texts would cut off from the left side when using programs at full screen and also desktop icons at the leftmost row only being half visible.

The resolution setting 1920x1080 would appear only rarely, The setting would not let me bump off more than 1440x900. I started this weird hack hunt messaging myself weird tricks just to get perfect monitor setup everytime.

Finally i got it, when the windows properly recognized the monitor a long monitor name came up in display settings,

-   Display Name: LinkG H2VA001 (Windows)
-   Display Name: LinkG Tech HG H2VA001 (Linux)

Otherwise,

-   Display Name: SJS 19"

The Linux one's is more longer and i found the quality to be (suprisingly) better as well (I tried Fedora and PopOS distro).
However, i was quite with state of fractional display scaling in Linux distros (didn't try KDE, only gnome).

Now, all i had to do was figure out how to get OS to recognize the display properly (having long display name). Turns out if i just power on the monitor after logging into the OS, it does the trick. I also tried powering on after OS bootup at the login screen but it wasn't cosistent. I don't know the internal details but its most consistent with this hack.

The quality difference is great, specially text rendering and watching at hd quality feels pretty decent. The resolution effect is also fixed I can setup 1920x1080 and not have left side display cutoff. I **have to** reboot my computer if I can't get the display to work in this configuration, can't live without this imporovement hack now.
