# Archiving the Internet Before it All Rots Away

Slides and video for my talk about Internet Archiving.

[Nick Sweeting](https://docs.sweeting.me/s/blog) (Co-Founder @ https://monadical.com)
[@theSquashSH](https://twitter.com/theSquashSH) / [@pirate](https://github.com/pirate)

---

## About

Could you imagine an internet where all links stopped working after 4 years? All the old blogs from the 90’s… gone, all your hot takes on Twitter… gone, all the news and reporting… gone.

Some of that decay is good, no one wants the entire internet to be preserved for eternity, but most of that decay leads to great content disappearing forever, and future generations being deprived of access to the most important medium for knowledge in the last half century. If no one worked on preserving that information, the human race would be facing a loss of knowledge many times greater than the burning of the Library of Alexandria.

Luckily organizations like Archive.org and the Internet Preservation Consortium work tirelessly every day to save what they can. But archiving doesn’t have to be exclusive to big organizations, we can all play a part by archiving the stuff that matters to us locally. Learn about the internet archiving community, the tools of the trade, and how to save content you care about in this talk!

<a href="https://www.youtube.com/watch?v=7eoz_EU6-wQ"><img src="https://i.imgur.com/X7j5H5H.jpg" width="400px"/></a>

## Slides

- [HTML](https://pirate.github.io/internet-archiving-talk/Archiving%20Talk%20Long/assets/player/KeynoteDHTMLPlayer.html)
- [PDF](https://pirate.github.io/internet-archiving-talk/Archiving%20Talk%20Long.pdf)
- [Keynote](https://github.com/pirate/internet-archiving-talk/raw/master/Archiving%20Talk%20PyCon%20Colombia%202020.key)
- [SlideShare](https://www.slideshare.net/NickSweeting1/archiving-the-internet-before-it-all-rots-away-229406385)

## Video

- [PyCon Colombia 2020 @ Medellin](https://www.pycon.co/en/talks/5/): Video coming soon...
- [PyGotham 2019 @ NYC](https://2019.pygotham.org/talks/archiving-the-internet-before-it-all-rots-away/): [Video](https://www.youtube.com/watch?v=7eoz_EU6-wQ)
- [Our Networks 2019 @ Toronto](https://ournetworks.ca/program/#mesh-lightning-talks): [Video](https://www.youtube.com/watch?v=ZYPA_jDAxJY)
- [RC Never Graduate Week @ NYC](https://recurse.com): No video available.

## Rough Outline

- 2 min: Self intro
    - name, company
    - founded in Colombia
    - poker -> consulting, fully remote in MTL and NYC now

- 5min: what got me into internet archiving
    - grew up with unreliable internet
    - censored internet
    - hostile environment for journalism and content
    - discovered wget
    - created pocket-archive stream

- 5min: equifax story
    - equifax breach announced, site launched
    - cloned with pocket-archive-stream
    - rehosted and forgot about it
    - notified of equifax misposts
    - goes viral, 2mil hits
    - only 2nd mention of wget in NYTimes history

- 5 min: Intro to internet archiving tooling
    - wget is powerful
    - wget has mny options and tunables
    - heres the ones I chose for ArchiveBox
    - demo
    
- 5 min: Intro to internet archiving ecosystem
    - Why is preserving information important? why does humanity create libraries and museums?
    - How has it been done so far?
    - what types of archives end up surviving?
    - What are the benefits of decentraliced vs centralized archives?
    
- 5 min: Why is internet archiving hard
    - Dynamic and interactive content
    - Private and paywalled content
    - Content ID and discovery, Base32 is hard
    - Dealing with the huge amount of data directly vs curating a smaller amount
    - Archive format longevity tradeoffs (WARC vs html / pdf)

- 5 min: Setting up a Wikipedia clone
    - Setup Kiwix server
    - Download your collections
    - Create an index and rehost it

- 1 min: What can you do today to help save the internet?
    - Joining the ArchiveTeam task force & archive.org community
    - Running a local internet archive

**Old outline:**
https://docs.sweeting.me/s/internet-archiving-talk

## Resources

- **[Big index of all the software and web archiving communities](https://github.com/pirate/ArchiveBox/wiki/Web-Archiving-Community)** (ArchiveBox Wiki)
- https://archivebox.io
- https://github.com/pirate/wikipedia-mirror
- https://kiwix.org
- https://archive.org
- https://netpreserve.org
- https://reddit.com/r/ArchiveTeam
- https://webrecorder.io
