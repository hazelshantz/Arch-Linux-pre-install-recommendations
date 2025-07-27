# Arch-Linux-pre-install-recommendations
General advice about what to do, before switching from Microsoft Windows to Arch Linux/Linux in general

On this document, you'll find general recommendations, to get the best experience out of Arch Linux/Linux in general.

# 1. Pre-installation advice
Before diving into Arch, or Linux in general, I highly advice to do your research. 

the most important thing that I advice, is to make your own IRS profile, so you get same or better audio on Linux. 

I already wrote an extensive guide on https://github.com/hazelshantz/Easyeffects-IRS-profiles-database that you should check out.

You Also should copy your Windows color profiles, so your screen colors don't look "washed out" or weird, when compared to Windows. this is a well known issue, that can be fixed, on KDE Plasma by providing WIndows color profiles to it.
I don't know about other DE/WM, but by having those files backed up, you ensure your screen colors are the right ones, same for the audio.

to get the color profiles off Windows, go to `C:\Windows\system32\spool\drivers\color`. You'll find several files there. look for the .ICM files, and backup them.

then, on KDE plasma, open screen settings, and import the files. your screen will adjust itself to match Windows colors.

Another important thing: copy the entire Font folder from Windows, so you can read text on any language. it is known that, Arch, doesn't come with the proper fonts to render emojis/asian languages.
the fonts are located on `C:\Windows\Fonts`
