# yung innanet archive

## Download

Everything is in this repo as plain files, so you can browse it and grab single tracks. For the whole thing,
`git clone` it (5.3 GB), or use the green Code button and Download ZIP. `SHA256SUMS.txt` lets you verify files.

**yung innanet** (Kayos Danger Johnson, also known as kayos, sedoyak, synrst) was a hackcore / nerdcore rapper,
producer, and the founder of tcp.direct. He died in October 2025. This is an attempt to collect everything he
released, in the best quality that still exists, so it doesn't disappear with his accounts.

193 tracks, 5.3 GB (4.95 GiB, so Windows will show it as about 4.95 GB). Everything is tagged and has cover art, so it drops straight into Jellyfin, Plex, Navidrome,
foobar2000, iTunes, or whatever you use.

## Official releases

All released on his own label "queed squad" and still on Spotify and Apple Music (most on Deezer too).

| folder | type | released | tracks |
|---|---|---|---|
| trash | album | 2019-05-14 | 6 |
| the nano tapes | album | 2019-11-09 | 7 |
| privnote (stylized ρrіνηօtе) | album | 2019-12-17 | 7 |
| unstable | album | 2020-04-24 | 14 |
| protocols | EP | 2020-08-11 | 6 |
| traverse | album | 2020-12-03 | 10 |

He also put out eight streaming singles (0x3b, 5G, traffic, VLAN, tinnitus, 0x36ft, /issues/trust, postman).
Those are in the non-album folder below, in upload order, and marked as singles in the comment tag.

## Everything else

- **SoundCloud (non-album tracks)** (85) - every other track from his main SoundCloud (soundcloud.com/queed-inc)
  plus the 11 from his alt account (soundcloud.com/synrst), sorted by upload date, 2017 to 2022. This is the bulk
  of his catalogue: loose songs, freestyles, instrumentals, bootlegs, skits, and the singles.
- **sedoyak (early work 2011-2016)** (49) - his first SoundCloud (soundcloud.com/emailextraordinaire), from before
  the yung innanet name. Glitch and hip-hop beats, remixes, and mashups as "sedoyak" / "DJ Kayos" / "KayoMash".
- **Unreleased & Posthumous** (9) - songs he deleted or never released, preserved by friends and re-uploaded to
  their own SoundCloud accounts, most of them in the weeks after his death: storm control, othacide, sealegs, port
  closed, an early postman snippet, a postman prerelease, domain reference, throwtocols (a 28-minute mix), and
  "It's over" (uploaded alongside his tracks as a memorial; not confirmed to be his). Quality is whatever the
  uploaders had.

## Not included: his appearances on other people's releases

These are other artists' records, so they aren't redistributed here. Worth tracking down:

- **ytcracker - *A Side Quest for Fractional Cents* (2022)** - netblocc, real ones (with freeced), since i was bummy,
  and MSCOMCTL.OCX all feature him. On streaming services and ytcracker's SoundCloud.
- **Ohm-I - Domain (Remix) feat. yung innanet (2021)** - on Ohm-I's Bandcamp (lossless, name your price) and on the
  DEF CON 29 official soundtrack. The two later traded diss tracks: his "-j DROP (Ohm-I diss)" is in this archive,
  Ohm-I's "Beneath Me" is on Ohm-I's Bandcamp.
- **freqyXin - NOC (yung innanet x freqyXin)** and **smartwater (prod. by yung innanet)** - freqyXin's SoundCloud.
- **Juji - Grep The Loot**, **We Love The Internet (ft. Atmos & yung innanet)**, **netbios.c (prod. yung innanet)**,
  **For Emmi (prod. yung innanet)** - Juji's SoundCloud.
- **0xdade - BOT NET (ft. yung innanet)**, **farmgoth - oppstation (ft. yung innanet)**,
  **morbid - Bruhhv Leak V2 (ft. yung innanet, kennet antinora)** - each on the uploader's SoundCloud.

Also not included: other people's remixes, sped-up edits, and tribute tracks built on his songs. Search SoundCloud
for "yung innanet" if you want them.

## Quality

Every file carries a `SC_QUALITY` tag saying what it is:

- **original** (150 files) - the exact file he uploaded to SoundCloud. He left original downloads enabled on almost
  everything, so all six albums and most of the loose tracks are here as his own WAVs, stored losslessly as FLAC.
  Where the upload was an MP3, that MP3 is kept untouched.
- **aac256** (33 files) - SoundCloud's 256 kbps AAC stream, used where no original was offered or its download
  quota had run out (icecoldwater on unstable, the synrst tracks).
- **aac160** or untagged (10 files) - 160 or 128 kbps, the best SoundCloud has for that track: seven of the
  posthumous re-uploads and three of the early sedoyak tracks.

## Lyrics

132 of the 193 tracks have a synced `.lrc` file next to the audio with the same name. Jellyfin (10.9+), Plex,
Navidrome, Symfonium, foobar2000, and most other players show these as timed lyrics. Each file says in its `[re:]`
header which of the two kinds it is:

- **82 tracks: real lyrics, machine-timed.** The words are the lyrics he posted in his own SoundCloud descriptions
  or that fans transcribed on Genius. The timestamps were produced by forced alignment: vocals separated from the
  beat with Demucs, then each line aligned to the vocal stem with Meta's MMS aligner. Line timing is usually within
  a few tenths of a second. On a handful of heavily processed tracks the aligner was less sure; the words are still
  right, the timing may drift.
- **50 tracks: machine transcription, uncorrected.** Nobody has transcribed these, so they were run through
  ElevenLabs Scribe v2 (the best speech-to-text available in 2026) with word timestamps. Rap over 808s with hacker
  slang is about the hardest input there is, so expect wrong words, especially technical terms and names. These are
  drafts to make the songs searchable and to give anyone correcting them a head start, not his words. If you know
  a song, fix its file and send a pull request.

The 61 tracks without a file are instrumentals, beats, skits, and the early sedoyak material, which have no
lyrics to sync. Nothing here was machine-generated without saying so.

## Tags

- Artist / album artist is `yung innanet` throughout, except the early-work folder where the artist is `sedoyak`
  and the album artist stays `yung innanet` so it groups under him.
- Titles are his own SoundCloud titles. Where he used homoglyph or stylized Unicode (e.g. `ՏΙԌΚΙⅬⅬ`, `ｈ ｏ ｌ ｌ ｏ ｗ`),
  the title tag is the plain readable version and the original spelling is in the comment tag. The four tracks
  whose streaming release title differs (5G, traffic, postman, crosstalk) use the streaming title, SoundCloud title
  in the comment.
- Dates are the release date for album tracks and the upload date for everything else.
- `SOURCE_URL` on every file is `https://api.soundcloud.com/tracks/<id>`, the permanent id of the upload it came from.
- Two of his tracks (heuristics, true colors) originally shipped with the EICAR antivirus test string in their tags
  as a joke. That has been replaced with normal tags so the files don't trip scanners.

## Known gaps

If you have any of these, please pass them along:

- Original-quality files for the synrst tracks and icecoldwater (their SoundCloud download quotas were used up).
- Anything he sent people privately, or anything from the deleted synrst uploads that isn't listed above.
- Alternate versions: the original uncut postman snippet with the empty verse space, live recordings, stems.

He never had a Bandcamp page of his own.

rip kayos.
