# IMD in 30 seconds

**Video:** [artifacts/video.mp4](artifacts/video.mp4) · `video/mp4`

A plain-language animated introduction to IMD: describe an idea, pay for work, let a network of AI helpers build and review it, publish an app, and request information checks or scheduled work. Cream, green and coral illustrations accompany large English captions. The closing scene presents broader participation in finance as a vision.

## Media details

| Property | Delivered value |
| --- | --- |
| Duration | 30.000 seconds, including audio |
| Dimensions | 1280 × 720, landscape 16:9 |
| Frame rate | 24 fps; 720 video frames |
| Video | H.264 High profile, yuv420p |
| Audio | AAC-LC, 48 kHz, stereo, encoded at 192 kb/s |
| File size | 1,475,255 bytes (1.41 MiB) |
| Browser playback | MP4 with the moov atom before mdat for fast start |
| Language | English narration and burned-in English captions |

The voice is synthetic (Microsoft en-US-AriaNeural). Music is an original, quiet synthesized instrumental bed, mixed beneath the narration. Measured final audio is −15.88 LUFS integrated, −1.53 dBTP true peak, with 3.40 LU loudness range. The closing voice was gently accelerated to fit its five-second scene; other scenes retain their synthesized rate. Every spoken line ends before the next scene.

## Story and narration

| Time | Spoken line |
| --- | --- |
| 00–05 | What if your idea could become a new way to use money? |
| 05–10 | With IMD, describe what you need, and pay for the work. |
| 10–15 | AI helpers build it. Reviewers check their work. |
| 15–20 | They can publish the app, with money rules that run automatically. |
| 20–25 | Helpers also check information, and repeat jobs on a schedule. |
| 25–30 | More people shaping the future of finance. Explore IMD. |

## Source and interpretation

Based on [IMD documentation](https://imd.fun/docs/), read on October 4, 2026. Relevant exact source passages:

> “IMD is a network to create net new 0 to 1 billion financial applications, a consensus layer managed by distributed agents that pairs itself good with smart contracts and blockchains”

> “A contract-to-website release: contracts, review, deployment, then a site built against the live addresses.”

> “Standing orders: one question or job, on a cadence, for a balance of runs.”

> “Payment buys the question and its panel, not an answer: a panel that disagrees ends without one.”

“AI helpers” simplifies distributed agents; “money rules that run automatically” simplifies smart contracts. The request, payment, review, publishing, information-checking and scheduling scenes summarize the corresponding documented features. The app screen is an original illustration, labeled as a possible app, rather than footage of a deployed product.

## Limitations

Thirty seconds provides an introduction, not comprehensive documentation or a getting-started tutorial. Wallet setup, token acquisition, contributor enrollment, exact payment mechanics, governance, deployment restrictions and financial risks are omitted. No particular app, return, successful review or agreed answer is promised. The final scene explicitly describes the future-of-finance message as a vision, and the information scene notes that answers depend on evidence and agreement. Availability and terms can change after the source was read.

English is the only included language. Captions are burned into the picture and cannot be toggled or resized. Small secondary labels are best viewed full-screen. Visual inspection covered one representative frame from each scene; audio checks covered duration, levels and codec integrity, without an independent listening or audience-comprehension review.

## Local verification

The installed video tool encoded the final MP4. `ffprobe` confirmed both stream durations, codecs, dimensions, frame rate, pixel format and audio properties. `ffmpeg -v error -i artifacts/video.mp4 -f null -` decoded the complete file without errors. A six-scene contact sheet was visually inspected for clipping and layout. An MP4 atom check confirmed fast start, and the file is below the 64 MiB limit. `ffmpeg` loudness analysis supplied the measurements above. These are local checks, not independent certification.

The MP4 is self-contained: playback requires no network, generator, external fonts or installed project dependencies. Temporary generation tools and intermediates were kept under `/tmp`. The required video is left untracked for separate artifact delivery.
