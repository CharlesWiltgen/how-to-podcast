# Secrets to great VoIP/Skype calls

This section describes popular options and resources for VoIP ([“Voice over IP”](https://en.wikipedia.org/wiki/Voice_over_IP)) calls, and includes hard-won tips for getting the highest quality, most reliable calls possible for a given internet connection.

## Call quality and reliability

In general, the VoIP solution you use isn't going to influence call quality or reliability — everything's mostly converged on using [WebRTC](https://en.wikipedia.org/wiki/WebRTC) and (excellent!) the [Opus](https://en.wikipedia.org/wiki/Opus_(audio_format) audio codec or a variation thereof (i.e. Skype's SILK).

With any VoIP solution, a poor or too-slow internet connection will hurt call quality and reliability or even cause call failure. High-quality, reliable calls means that _you’re responsible_ for providing enough network and other (CPU, free recording space, etc.) resources to make that possible.

## Pre-call checklist

1. Use a **wired connection** to the internet if at all possible, and ask other participants to do the same. Connect your PC or laptop to your router or cable modem with an Ethernet cable to \(1\) prevent wireless interference and other issues from ruining your interview, and \(2\) improves the odds of Skype being able to use its highest-quality mode.

2. If you're using Skype call recording software to record the call, confirm that it's set **record to an uncompressed WAV or AIFF file** \(and not MP3 files\). The only time you should create an MP3 file is before you upload your final episode to your podcast host.

3. Ask participants to **pause any background file transfers** during the call, because it can interrupt calls or make them sound like drunk robots. Things that might do this include sync solutions like Dropbox, backup solutions like Carbonite, and BitTorrent clients like µTorrent.

4. Change your Skype status to **"Do Not Disturb"** during the call, and suggest that your guest do the same. This will keep another call from coming in, which can throw off the conversation and create unwanted noises in your recording.

5. If you’re using Skype, check that everything’s working correctly with the “Skype Test Call” service before talking with your guest. If you’re not using Skype, you can call a friend or even your own mobile phone.

## Tips and tricks

* **DO** use routers that support “QoS”, which can ensure that Skype and other VoIP traffic is always given precedence. If you don't know if the router you're using supports QoS (Quality of Service) data prioritization, find out — if it doesn’t, you’re at the mercy at literally anything sharing the same network that decides to send data during your call.

* **DO** strongly suggest that remote participants use a mic or headset. A perfectly good headset is amazingly inexpensive — the **[Plantronics .Audio 326](http://www.amazon.com/gp/product/B001S2RCXW)** is 9 bucks as I write this.

* **DO NOT** record video unless you must. It almost inevitably impacts audio quality because Skype is working with a finite \(and usually small\) amount of upstream bandwidth.

* **DO NOT** have lots of browser tabs open, since web pages can be serious CPU and bandwidth hogs. If you need a few web pages for show notes, scripts, etc. but don't want to lose your other tabs, consider using a separate browser just for shows. (Related tip: Safari is by far the most efficient browser to use on macOS.)

## Processing Skype recordings

Use a [high-pass filter](https://en.wikipedia.org/wiki/High-pass_filter) to remove anything under 300Hz \(which is junk\), and a [low-pass filter](https://en.wikipedia.org/wiki/Low-pass_filter) to remove all of the distortion and hiss above 3400Hz.

You can also use EQ in the 1kHz–3kHz range to make male voices “pop”, and to make female voices a bit “warmer”.
