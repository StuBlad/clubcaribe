# Club Caribe remake
This project aims to be a remake of the original Club Caribe world for the [NeoHabitat](http://www.neohabitat.org) server.

Please visit the join the [RenoProject Discord](https://discord.gg/xagN9ay3pB) if you'd like to be involved.

2024 Update: You can now use [SpindleyQ's Habitat inspector tool](https://frandallfarmer.github.io/neohabitat-doc/inspector/edit.html) to easily create Habitat and Caribe regions in the browser. Please use this moving forward, it is so much easier than starting up your own server and editing JSON files by hand.

![Club Caribe](https://renoproject.org/imagearchive/upload/2023/12/14/20231214174512-c47680f6.gif)

Club Caribe was the released version of Lucasfilm Games "Habitat" virtual world. It was available on the Commodore 64 in the USA via the Quantum Link service, who later became America Online. Habitat was notable for being the worlds first massively multiplayer online roleplaying game.

Whilst Habitat was breaking new ground, Q-Link decided to strip the more esoteric elements from the world database, shipping it as "Club Caribe" where it was touted as an idyllic island getaway destination. Caribe was a heavily modified version of regions used in the original Habitat world, along with a bunch of freshly created regions especially for it.

As far as we know, there are no database backups that exist of Club Caribe out there.

We have a lot of screenshots as well as maps of Club Caribe and with that, I'd like to work on recreating that world by hand. If you would like to contribute, feel free to submit a pull request.

![Club Caribe remake](http://www.renoproject.org/clubcaribe/CaribeWelcome.gif)

Here are the main resources we'll be using to make this happen:

Club Caribe screenshots and maps
* http://www.renoproject.org/imagearchive/index.php?/category/33

Club Caribe 1994 Documentary:
* https://www.youtube.com/watch?v=liQ_H1FXTlA&list=PL6o_B0g-S4Mdcd3AIuRUJnIPcHIwiihSx

Keith Elkins Club Caribe videos:
* https://www.youtube.com/watch?v=l7KwdqyyUO8

* https://www.youtube.com/watch?v=uiUxAn7dxM8

[NeoHabitat](http://www.neohabitat.org) region database:
* https://github.com/frandallfarmer/neohabitat/tree/master/db

There is also a third video which hasn't been uploaded yet.

Bear in mind, there are some corrupted regions being shown in Keith Elkin's Club Caribe videos so please compare these regions against the screenshots we have. Also, the screenshots linked above appear to be taken towards the end of Caribes life in 1994 so they should be considered canonical. The 1994 documentary linked above was also filmed on the final day and as such, should be our main resource for all things Caribe, taking precedence over earlier regions seen in Keith Elkin's videos and screenshots.

The 1994 Documentary videos also feature the use of a compass object in every region which is amazing, because it tells us which direction is West. This is especially useful because we can use this to ascertain the actual orientation of the region itself and Habitat Inspector has a feature that will let you input the orientation as seen in the documentary videos, and it will automatically give you the correct orientation for that region. This ensures that all region connections will match up 1:1 with how they were in the original Club Caribe world. Thank you to Bld Stalker for the amazing foresight to do this back in 1994.

The reason we reference the [NeoHabitat](http://www.neohabitat.org) region database here is because a lot of the regions in Caribe were modified versions of Habitat ones. It will save us time if we can identify the base region from Habitat and then make the appropriate tweaks to bring it in line with their Caribe counterpart.

We hope to have more resources available in the future in order to help us reconstruct the world.

If you are new to [NeoHabitat](http://www.neohabitat.org) and how regions are put together, we highly recommend reading the [Region Creation and Porting](https://github.com/frandallfarmer/neohabitat/wiki/Region-Creation-and-Porting) page on the [NeoHabitat](http://www.neohabitat.org) wiki page as well as the [Region testing procedure](https://github.com/frandallfarmer/neohabitat/wiki/Region-testing-procedure) wiki page.
