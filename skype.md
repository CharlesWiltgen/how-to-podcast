# Skype and VoIP

[“Voice over IP”](https://en.wikipedia.org/wiki/Voice_over_IP) is internet telephony — a great way to conduct remote interviews, and include remote co-hosts and guests in your podcast.

**However:** With any VoIP solution, a poor or too-slow internet connection will hurt call quality and reliability or even cause call failure. High-quality, reliable calls means that _you’re responsible_ for providing enough network and other (CPU, free recording space, etc.) resources to make that possible.

This section describes popular options and resources for VoIP calls, and includes hard-won tips for getting the highest quality, most reliable calls possible for a given internet connection.

## Background

In general, the VoIP solution you use isn't going to influence call quality or reliability — everything's mostly converged on using [WebRTC](https://en.wikipedia.org/wiki/WebRTC) and (excellent!) the [Opus](https://en.wikipedia.org/wiki/Opus_(audio_format) audio codec or a variation thereof (i.e. Skype's SILK).

## Options

Skype is by far the most popular VoIP solution for podcasters — you can use it not only with Skype users, and with anybody else with a phone number.

* **[Skype](http://skype.com/)**
* **[Google Hangouts](https://hangouts.google.com/)**
* Slack
* Discord
* Zoom

Some VoIP solutions also help automate “multi-enders” — a workflow where high-quality call recording is done on each participant’s side as well and then merged after.

* Zencastr
* Ringr
* Cleanfeed

## Pre-call checklist

1. Use a **wired connection** to the internet if at all possible, and ask other participants to do the same. Connect your PC or laptop to your router or cable modem with an Ethernet cable to \(1\) prevent wireless interference and other issues from ruining your interview, and \(2\) improves the odds of Skype being able to use its highest-quality mode.

2. If you're using Skype call recording software to record the call, confirm that it's set **record to an uncompressed WAV or AIFF file** \(and not MP3 files\). The only time you should create an MP3 file is before you upload your final episode to your podcast host.

3. Ask participants to **pause any background file transfers** during the call, because it can interrupt calls or make them sound like drunk robots. Things that might do this include sync solutions like Dropbox, backup solutions like Carbonite, and BitTorrent clients like µTorrent.

4. Change your Skype status to **"Do Not Disturb"** during the call, and suggest that your guest do the same. This will keep another call from coming in, which can throw off the conversation and create unwanted noises in your recording.


## Tips and tricks

* **DO** use routers that support “QoS”, which can ensure that Skype and other VoIP traffic is always given precedence. If you don't know if the router you're using supports QoS (Quality of Service) data prioritization, find out — if it doesn’t, you’re at the mercy at literally anything sharing the same network that decides to send data during your call.

* **DO** strongly suggest that remote participants use a mic or headset. A perfectly good headset is amazingly inexpensive — the **[Plantronics .Audio 326](http://www.amazon.com/gp/product/B001S2RCXW)** is only 9 bucks as I write this.

* **DO NOT** record video unless you must. It almost inevitably impacts audio quality because Skype is working with a finite \(and usually small\) amount of upstream bandwidth.

* **DO NOT** have lots of browser tabs open, since web pages can be serious CPU and bandwidth hogs. If you need a few web pages for show notes, scripts, etc. but don't want to lose your other tabs, consider using a separate browser just for shows. \(Related tip: Safari is by far the most efficient browser to use on macOS.\)


## Processing Skype recordings

Use a [high-pass filter](https://en.wikipedia.org/wiki/High-pass_filter) to remove anything under 300Hz \(which is junk\), and a [low-pass filter](https://en.wikipedia.org/wiki/Low-pass_filter) to remove all of the distortion and hiss above 3400Hz.

You can also use EQ in the 1kHz–3kHz range to make male voices “pop”, and to make female voices a bit “warmer”.

## Recording

### With hardware

#### Mix-minus

A “mix-minus” setup allows you to record Skype calls.

(TBD)

### With software

#### Skype plug-ins \(Mac\)

* **[Ecamm Call Recorder for Skype](http://www.ecamm.com/mac/callrecorder/)** \(Mac, $30\) — This Skype plug-in can record your own microphone input and the output of your Skype call as separate tracks in a single QuickTime movie. An included utility allows you to split that file into separate files for each track, and convert them to other formats.

* **[Soundflower](https://github.com/mattingalls/Soundflower)** \(Mac, free!\) — This open source software allows apps to send audio to other apps. \(A pre-built installer is available at the top of the description.\) For example, you can use Soundflower to send Skype output to apps like QuickTime Player, Audacity, etc. for recording.

* **[Audio Hijack](https://www.rogueamoeba.com/audiohijack/)** \(Mac, $49, records for 10 minutes without a serial number) — It does Skype recording and a *lot* more, and as such it’s a crucial tool for many podcasters. Rogue Amoeba is a great developer and has been making great, award-winning audio software for the Mac since 2002.

#### Skype plug-ins \(Windows\)

* **[Amolto](http://amolto.com/)** ($30, free for audio-only) — A Skype call recorder that supports audio and video.

* **[CallGraph](https://scribie.com/free-skype-recorder)** (free!) — An easy-to-use, audio-only Skype call recorder.

* **[Evaer](http://www.evaer.com/)** ($20, trial available) — A Skype call recorder that supports audio and video.

* **[MP3 Skype Recorder](http://voipcallrecording.com/)** (free!) — Only records to compressed MP3 files, which will result in lower quality recordings compared to alternatives which can record to uncompressed WAV or AIFF files. Try to avoid, but if you must use be sure to set "Recording BitRate" to 128.

* **[Pamela Call Recorder](http://www.pamela.biz/)** (15€) — Paid version supports unlimited recording, can record up to 15 minutes for free. <span style="color:red">**Note: Pamela has a mixed reputation reliability, and is listed here mostly for completeness’ sake.**</span>

* **[Virtual Audio Cable](http://vb-audio.pagesperso-orange.fr/Voicemeeter/banana.htm)**[, ](http://vb-audio.pagesperso-orange.fr/Voicemeeter/banana.htm)**[Voicemeeter](http://vb-audio.pagesperso-orange.fr/Voicemeeter/banana.htm)**[, ](http://vb-audio.pagesperso-orange.fr/Voicemeeter/banana.htm)**[Voicemeeter Banana](http://vb-audio.pagesperso-orange.fr/Voicemeeter/banana.htm)** \(donation requested\) — This "virtual mixer" software allows you to route audio between applications, meaning that you can send Skype output to a "virtual input" to record with Audacity or your [DAW](https://en.wikipedia.org/wiki/Digital_audio_workstation) of choice.

### iOS

(TBD)

