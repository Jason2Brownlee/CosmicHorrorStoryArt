 # Cosmic Horror Story Art

Generative art for selected cosmic horror stories, as an excuse to play with Dalle v3 and ChatGPT v4.

<img src="stories/cover.png" width="500" >

## Stories

Each story has its own page with story synopsis, summarized selected scenes, summary of illustration directions, and art generated for the selected scenes.

I focused on short classic horror/cosmic horror stories that are in the public domain. The initial thought was to create an illustrated short story collection, and I still may. I fiddled with the generated art only minimally (e.g. regenerate like this or like that). I am interested in a generally automated process.

Stories are listed in the chronological order of generation, hopefully showing an improvement in methods and results.

Click the preview to see all art for each story.

| Preview | Story |
| ------- | ----- |
| <a href="stories/dagon/README.md"><img src="stories/dagon/scene3c.webp" width="300"></a> | [Dagon](stories/dagon/README.md), H. P. Lovecraft. |
| <a href="stories/usher/README.md"><img src="stories/usher/scene5a.webp" width="300"></a> | [The Fall of the House of Usher](stories/usher/README.md), Edgar Allan Poe. |
| <a href="stories/carcosa/README.md"><img src="stories/carcosa/cover.webp" width="300"></a> |  [An Inhabitant of Carcosa](stories/carcosa/README.md), Ambrose Bierce. |
| <a href="stories/yellowsign/README.md"><img src="stories/yellowsign/scene5a.webp" width="300"></a> |  [The Yellow Sign](stories/yellowsign/README.md), Robert W. Chambers. |
| <a href="stories/rats/README.md"><img src="stories/rats/scene5b.webp" width="300"></a> |  [The Rats in the Walls](stories/rats/README.md), H. P. Lovecraft. |
| <a href="stories/draculasguest/README.md"><img src="stories/draculasguest/cover1.webp" width="300"></a> |  [Dracula's Guest](stories/draculasguest/README.md), Bram Stoker. |
| <a href="stories/monkeyspaw/README.md"><img src="stories/monkeyspaw/scene5a.webp" width="300"></a> |  [The Monkey's Paw](stories/monkeyspaw/README.md) by W. W. Jacobs. |
| <a href="stories/festival/README.md"><img src="stories/festival/scene6a.webp" width="300"></a> |  [The Festival](stories/festival/README.md), H. P. Lovecraft. |
| <a href="stories/dragon/README.md"><img src="stories/dragon/scene3a.webp" width="300"></a> |  [In The Court Of The Dragon](stories/dragon/README.md), Robert W. Chambers. |
| <a href="stories/outsider/README.md"><img src="stories/outsider/scene7a.webp" width="300"></a> |  [The Outsider](stories/outsider/README.md), H. P. Lovecraft. |
| <a href="stories/greatgodpan/README.md"><img src="stories/greatgodpan/scene6b.webp" width="300"></a> |  [The Great God Pan](stories/greatgodpan/README.md), Arthur Machen. |
| <a href="stories/pickman/README.md"><img src="stories/pickman/scene2a.webp" width="300"></a> |  [Pickman's Model](stories/pickman/README.md), H. P. Lovecraft. |
| <a href="stories/wallofsleep/README.md"><img src="stories/wallofsleep/scene4b.webp" width="300"></a> |  [Beyond the Wall of Sleep](stories/wallofsleep/README.md), H. P. Lovecraft. |
| <a href="stories/erichzann/README.md"><img src="stories/erichzann/cover1a.webp" width="300"></a> |  [The Music of Erich Zann](stories/erichzann/README.md), H. P. Lovecraft. |
| <a href="stories/tomb/README.md"><img src="stories/tomb/cover1b.webp" width="300"></a> |  [The Tomb](stories/tomb/README.md), H. P. Lovecraft. |
| <a href="stories/mask/README.md"><img src="stories/mask/scene6b.webp" width="300"></a> |  [The Mask](stories/mask/README.md), Robert W. Chambers. |
| <a href="stories/reputations/README.md"><img src="stories/reputations/cover1a.webp" width="300"></a> |  [The Repairer of Reputations](stories/reputations/README.md), Robert W. Chambers. |
| <a href="stories/willows/README.md"><img src="stories/willows/scene10a.webp" width="300"></a> |  [The Willows](stories/willows/README.md), Algernon Blackwood. |
| <a href="stories/foundout/README.md"><img src="stories/foundout/cover1b.webp" width="300"></a> |  [The Man Who Found Out](stories/foundout/README.md), Algernon Blackwood. |
| <a href="stories/white/README.md"><img src="stories/white/cover1b.webp" width="300"></a> |  [The White People](stories/white/README.md), Arthur Machen. |
| <a href="stories/screw/README.md"><img src="stories/screw/cover1b.webp" width="300"></a> |  [The Turn of the Screw](stories/screw/README.md), Henry James. |
| <a href="stories/derelict/README.md"><img src="stories/derelict/scene1a.webp" width="300"></a> | [The Derelict](stories/derelict/README.md), William Hope Hodgson. |
| <a href="stories/innsmouth/README.md"><img src="stories/innsmouth/cover1b.webp" width="300"></a> |  [The Shadow Over Innsmouth](stories/innsmouth/README.md), H. P. Lovecraft. |
| <a href="stories/dunwich/README.md"><img src="stories/dunwich/cover1b.webp" width="300"></a> |  [The Dunwich Horror](stories/dunwich/README.md), H. P. Lovecraft. |
| <a href="stories/colour/README.md"><img src="stories/colour/cover1a.webp" width="300"></a> |  [The Colour Out of Space](stories/colour/README.md), H. P. Lovecraft. |
| n/a |  The Whisperer in Darkness, H. P. Lovecraft. |
| n/a |  The Shadow Out of Time, H. P. Lovecraft. |
| n/a |  The Haunter of the Dark, H. P. Lovecraft. |
| n/a |  The Thing on the Doorstep, H. P. Lovecraft. |
| n/a |  At the Mountains of Madness, H. P. Lovecraft. |
| n/a |  The Call of Cthulhu, H. P. Lovecraft. |

## Meta

* [Prompt Templates](stories/prompt_templates.md)

Thoughts and observations:

* Use an expert to select and describe scenes. When I did this manually, I selected too many and did not understand the scenes well enough to describe them effectively.
* Use separate roles for 1) scene selection and description, 2) illustration description, 3) illustration generation.
* Use terms to motivate the consistency of description across scenes and the generation of imagery across scenes.
* Use terms to encourage the illustrator to be specific about the details of the objects in the scene.
* Generated images rarely have all elements in the description, or have them correctly, yet the images often have the right tone and are interesting.
* The scene description must include as much detail as possible, including objects and their composition.

This work builds upon prior projects [Bad, Bad, Bad, Good](https://badbadbadgood.substack.com/) and [Interviews With Technical Experts](https://github.com/Jason2Brownlee/TechnicalExperts).