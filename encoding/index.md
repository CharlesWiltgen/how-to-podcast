# Create Your MP3 File

Once your audio is complete, the first step to publishing is to encode it to an MP3 file.

## Long story short

Use [**iTunes**](http://www.apple.com/itunes/download/), with these settings.

<img src="/images/iTunes-MP3-Encoder-Settings-96-JS.png" style="width:60%;display:block;margin: 0 auto">

To set these MP3 Encoder preferences, go to **Preferences** and click the **Import Settings** button in the **General** tab.

Once your encoding preferences are set, select your uncompressed source file and choose **File** > **Create New Version** > **Create MP3 Version**. (In older versions of iTunes, you can right-click the selected source file instead.)

<img src="/images/iTunes-MP3-Export-Menu.png" style="width:60%;display:block;margin: 0 auto">

### How low can I go?

I don’t recommend encoding at less than 96 kbps, but you can encode at 64 kbps. (Note that iTunes’s bizarre user interface requires that you select “128 kbps” in this case.)

<img src="/images/iTunes-MP3-Encoder-Settings-64-mono.png" style="width:60%;display:block;margin: 0 auto">

### Using GarageBand?

Don’t use GarageBand to create your MP3s — it’s missing several important options.

Instead, export (**Share** > **Export Song To Disk**) to AIFF using these settings, and then use iTunes to encode.

<img src="/images/GarageBand-export-AIFF.png" style="width:75%;display:block;margin: 0 auto">

## Encoder matters

The two MP3 encoders you might hear about are:

* A commercial MP3 encoder made by **Fraunhofer**, the inventor of the MP3 format

* The open source **LAME** encoder

The Fraunhofer encoder has a slight quality edge on LAME at typical podcast bitrates (64 and 96 kbps). So, use the Fraunhofer encoder.

Commercial software generally include a licensed Fraunhofer encoder. Open source software generally uses the LAME encoder, although it typically needs to be installed separately.

#### Apps known to use Fraunhofer’s MP3 encoder

* iTunes
* Audition

#### Apps known to use LAME

* Audacity
* Hindenberg
* iZotope RX 6/RX 6 Advanced

## Bitrate

In the world of digital media, size is measured in kilobits per second, or "kbps".

For audio podcasts, **96 kbps** is the best balance between quality and file size.

For some, 64 kbps can be a more practical (if lower quality) choice. People using LibSyn and other hosts that charge based on "monthly storage" often encode at a lower bitrate to meet hosting limitations. Podcasts with listeners in the millions often encode at 64 kbps to save money.

## Mono or stereo?

Trick question! Neither — use "**Joint Stereo**" (JS) encoding.

The great thing about JS encoding is that it gives you the best of both worlds — mono content encodes as efficiently as a mono-only encode, but stereo content is still reproduced (very efficiently) in glorious stereo.

JS encoding (as compared to mono) is better for your show's music, and allows you to place hosts and guests at slightly different spots on a stereo soundstage to improve the clarity and interest of your podcast.