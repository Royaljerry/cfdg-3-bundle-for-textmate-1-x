Context Free 3 Bundle for TextMate 1.x
==============================

For the folks out there creating generative art (0.001% of the World poopulation), and using the marvellous [Context Free](http://www.contextfreeart.org) (0.0005%) and TextMate combo (undetectable%) for this purpose… (Like me, e.g.)

Long ago there was *Context Free* (CF for short) 2.x, for which there existed some brilliant *TextMate* (TM) bundles with syntax highlighting and such. Unfortunately for TM, but fortunately for CF, the latter evolved into 3.x with a slightly modified syntax. Modified enough not to be understood by these bundles and leaving us coding without colors.

Which is a totally unbearable situation.

Therefore I have created (er… started to create) this missing bundle with a supporting math and typographic library. Though the libraries are still in a very embryonic phase (so don’t take them too seriously), at the time of this writing (12/31/2013, happy new year, anyway) the TM bundle and the libraries have the following

**features:**

- Full *syntax highlighting* for all CF elements (rule/shape/path declarations, control keywords, embedded expressions, primitives, etc.).
- Full *tab trigger support* for the most common coding blocks (see above).
- Some *handy macros* for the most common tasks (select previous/next blocks, create block from lines, etc.)
- The supporting **Math** library has a special *Wave* shape section, with which one can create some interesting (sine, atm) wavvy graphics with loops.
- Three templates, one of them being for working with the libraries.
- The embryonic **Geometry** library consists of one shape yet (rectangle), it is for creating arbitrary frames.
- The **Glyphs** and the corresponding **Typography** libraries are responsible to create some short texts. Okay, it’s not real text (CF doesn’t support strings), but with a small experiment one can draw er… letters. Pixel letters.

**Some features not working yet or need to be fixed/implemented:**

- The “Render” scripts need to be revisited. These are legacy codes I have found in one of the previous bundles, and didn't have the time to fix them, so they are in the bundle rather for “placeholder” purposes.
- The *TM Language Grammar* is a total chaos (see “Context Free” at the bottom of the bundle). I’m really sorry, this was my first attempt to create/modify a Language Grammar (I love you, property lists…), so it too needs to be revisited once. But it works. Most of the time.
- The libraries need to be built up at least to a reasonable state – in this form they are rather for experimenting than for real “work”.
- I’m planning to create a supporting *Color* library that would be responsible for color conversions (HSB/RGB/Grayscale).
- The same applies to some supporting scripts for “converting” real (and small) pixel images to CF shapes. (Well, mostly based on SQUARE declarations).

Well, that’s all for now. I will keep this repo updated (hopefully very frequently), and would be glad if someone could help me in writing a pretty usable bundle/library combo.

Happy new year, folks.
