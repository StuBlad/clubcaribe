# Club Caribe remake

![the Chapel Approach](https://github.com/StuBlad/clubcaribe/assets/25211663/232b02f9-bf97-400a-8574-5c18a252addd)

This project aims to be a remake of the original Club Caribe world using the [NeoHabitat](http://www.neohabitat.org) server platform.

Club Caribe was the released version of [Lucasfilm Games "Habitat" virtual world](https://en.wikipedia.org/wiki/Habitat_(video_game)). It was available on the Commodore 64 in the USA via the Quantum Link service, who later became America Online. Habitat was notable for being the worlds first massively multiplayer online roleplaying game.

Whilst Habitat was breaking new ground, Q-Link decided to strip the more esoteric elements from the world database, shipping it as "Club Caribe" where it was touted as an idyllic island getaway destination. Caribe was a heavily modified version of regions used in the original Habitat world, along with a bunch of freshly created regions especially for it.

As far as we know, there are no database backups that exist of Club Caribe out there.

We have a lot of screenshots as well as maps of Club Caribe and with that, I'd like to work on recreating that world by hand. If you would like to contribute, please join the [NeoHabitat Discord](https://discord.gg/rspcX27Vt4) and feel free to submit a pull request.

## Do you have any Club Caribe related paraphenalia or archival material?
If you have any of the following items, please get in touch with me via [e-mail](mailto:stuart@renoproject.org). It could help to make this restoration project even more accurate.
* Database backup of Club Caribe (The Holy grail. It likely doesn't exist anymore)
* Video footage of Club Caribe (Did you record your Caribe gameplay? Please get in touch!)
* Screenshots of Club Caribe (Did you take screenshots or photos of Caribe game sessions? We want to hear from you)
* Maps of Club Caribe (If you have any maps, this could be useful for helping us get the placement of regions correct)
* Any development material of Club Caribe (If you worked on Club Caribe at Q-Link and have any old documents or emails, please get in touch!)
* Scans of the Club Caribe disk, manual and map (We have seen low resolution copies of these floating around but need a higher resolution upgrade)

## How to Collaborate
Using the tools and resources below, select a region from the [screenshot library containing Club Caribe regions](https://renoproject.org/imagearchive/index.php?/category/277) and [check to see if it has already been created](https://github.com/StuBlad/clubcaribe/tree/master/db). If it hasn't been worked on, [create the region](https://frandallfarmer.github.io/neohabitat-doc/inspector/edit.html), [check it for any issues](https://github.com/frandallfarmer/neohabitat/wiki/Region-testing-procedure) and then submit a pull request. I will review all PR's and check your region out for any issues and if it's good to go, then it'll be merged into this repository.

Stubs have been made for regions that we know exist and have a screenshot of. These allow you to not only move around the world unimpeded even if a region doesn't exist yet, but you can also use it as a template to build upon as it's already hooked up to the world map.

To avoid any duplication of work, I highly recommend that you join the [NeoHabitat Discord](https://discord.gg/rspcX27Vt4) to see if anyone else is already working on that region or area.

For more detailed information, see below.

## Resources
Here are the main resources we'll be using to make this happen.

### Tools
* [SpindleyQ's Habitat inspector tool](https://frandallfarmer.github.io/neohabitat-doc/inspector/edit.html) - This lets you create Habitat regions in your browser. You can load pre-existing regions from the Habitat database, load a screenshot of a Caribe region to use as an overlay with a transparency slider so you can compare your modifications in real time. Once you've built the region, you can export the regions JSON file and submit it as a Pull Request.

* [NeoHabitat Server](https://github.com/frandallfarmer/neohabitat) - **Optional Step** - You can run your own local NeoHabitat server and add the regions you create using Habitat Inspector to test them live in the Habitat client. This is an optional step that you don't need to take, but if you're able to run a local server, it will help to make sure the region looks okay ingame. If you use colors to paint an object instead of a pattern and the object is a background object, colors will bleed and this isn't something Habitat Inspector is currently able to replicate. I will be personally checking out any regions submitted via pull request so you don't need to run your own server, but it would be helpful to have more eyes on a region before it get merged into the repo.

### Archival References
These are listed in order of preference:

Club Caribe 1994 Documentary:
* https://www.youtube.com/watch?v=liQ_H1FXTlA&list=PL6o_B0g-S4Mdcd3AIuRUJnIPcHIwiihSx
* https://renoproject.org/imagearchive/index.php?/category/277 (Screenshots of every unique region featured in the footage, containing the region name and orientation if available)

Club Caribe screenshots and maps
* http://www.renoproject.org/imagearchive/index.php?/category/33

Keith Elkins Club Caribe videos:
* https://www.youtube.com/watch?v=l7KwdqyyUO8

* https://www.youtube.com/watch?v=uiUxAn7dxM8

* https://archive.org/details/vw_lucasfilm-caribepart3

[NeoHabitat](http://www.neohabitat.org) region database:
* https://github.com/frandallfarmer/neohabitat/tree/master/db (Master JSON files for every region in the Habitat database)
* https://renoproject.org/imagearchive/index.php?/category/116 (Screenshots of every region in Habitat)
* https://frandallfarmer.github.io/neohabitat-doc/inspector/index.html#regions (Explore every region in Habitat using the Habitat Inspector to see regions in real time and edit them too)

The 1994 footage of Club Caribe was filmed the day before it closed and thanks to us having 10 hours of footage of the world, it's also pretty complete. This is going to be our canonical source we are working to recreate for the most part. Around 250 regions were recorded in some fashion on these tapes which makes up a bulk of the world, but it is not complete.

The screenshots that we have come from a variety of different times, but tend to also be from the same 1994 pre-closure period and so they should be used as a reference also. The 1994 footage should take precedence but these screenshots could come in handy for example if there's a unique region we have a screenshot of, but no footage, or we have footage, but objects or other avatars are covering up a part of the region. You could use these screenshots to recreate the parts that were previously hidden.

Keith Elkin's Club Caribe videos are from the beta period, 5 years prior to the 1994 footage and so we should use these as a last resort because the world did change a decent amount during its lifetime. Certain regions are also corrupted in Keiths footage for some reason, but we likely have captures of those regions in the 1994 footage.

The 1994 footage also feature the use of a compass object in every region which is amazing, because it tells us which direction is West. This is especially useful because we can use this to ascertain the actual orientation of the region itself and [Habitat Inspector](https://frandallfarmer.github.io/neohabitat-doc/inspector/edit.html) has a feature that will let you input the orientation as seen in the documentary videos, and it will automatically give you the correct orientation for that region. This ensures that all region connections will match up 1:1 with how they were in the original Club Caribe world. Thank you to Bld Stalker for the amazing foresight to do this back in 1994.

The reason we reference the [NeoHabitat](http://www.neohabitat.org) region database here is because a lot of the regions in Caribe were modified versions of Habitat ones. It will save us time if we can identify the base region from Habitat and then make the appropriate tweaks to bring it in line with their Caribe counterpart. Wherever possible, please browse through the original Habitat regions to see if you can find a region that matches, as this will make it easier to recreate, but also may turn out to be more accurate too.

## New to NeoHabitat and creating regions?

If you are new to [NeoHabitat](http://www.neohabitat.org) and how regions are put together, we highly recommend reading the [Region Creation and Porting](https://github.com/frandallfarmer/neohabitat/wiki/Region-Creation-and-Porting) page on the [NeoHabitat](http://www.neohabitat.org) wiki page as well as the [Region testing procedure](https://github.com/frandallfarmer/neohabitat/wiki/Region-testing-procedure) wiki page.
