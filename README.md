# LaTexCV

### My own custom CV implementation in LaTex

Originally, I made my own self-designed fancy CV using Adobe Illustrator, which I then kept updating and refining for many years. However, now that I am no longer a student I don't have an Illustrator license anymore, as the price is way too much for my irregular use without the nice student discount (subscription-based software licenses as the only option for major products like this really suck).

I have been getting pretty deep into LaTex for the past few years, and I started using LaTex for most of my school work already pretty early in my studies (as opposed to only using it when writing a thesis like many people do). Recreating my CV design with LaTex from scratch was a nice challenge and opportunity to learn even more about it. Sure, there are a lot of ready-made CV templates for LaTex, but I wanted to it completely by myself. Also, customizing a CV template to look just the way I want is probably even more time-consuming than simply doing one from scratch. As this design is primarily intended only for myself, with a lot of hand-tuning with the lenghts and sizes, I implemented everything directly inside the document instead of going the full route of writing a class file for it.

#### Implementation

The overall layout is accomplished with nested *minipage* environments. The sections are separated visually with the versatile *tcolorbox* package that I learned just for this. *Tikz* is used to round the photo and for drawing the skill level indicator symbols. I made all the logo graphics with Adobe Illustrator, based on reference images found on the internet. I also converted the Github and Twitter logos to approriately sized pdf images from the vector formats they were provided in, such as *svg*, as they don't work in LaTex directly.

Other major packages used: *Geometry* for setting up the page margins. *Fancyhdr* for custom headers and footers. *Multicol* and *enumitem* for the lists.

The Font is a Sans Serif font called [Cabin](http://www.tug.dk/FontCatalogue/cabin/).

#### What it looks like:

![alt text](https://github.com/Esgrove/LaTexCV/blob/master/preview.png)