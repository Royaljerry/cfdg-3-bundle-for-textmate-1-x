Context Free 3 Bundle for TextMate 1.x
==============================

*See current updates [at the end](#updates).*

For the folks out there creating generative art (0.001% of the World poopulation), and using the marvellous [Context Free](http://www.contextfreeart.org) (0.0005%) and TextMate combo (undetectable%) for this purpose… (Like me, e.g.)

Long ago there was *Context Free* (CF for short) 2.x, for which there existed some brilliant *TextMate* (TM) bundles with syntax highlighting and such. Unfortunately for TM, but fortunately for CF, the latter evolved into 3.x with a slightly modified syntax. Modified enough not to be understood by these bundles and leaving us coding without colors.

Which is a totally unbearable situation.

Therefore I have created this missing bundle with the following

**features:**

- Full *syntax highlighting* for all CF elements (rule/shape/path declarations, control keywords, embedded expressions, primitives, etc.).
- Full *tab trigger support* for the most common coding blocks (see above).
- Some *handy macros* for the most common tasks (select previous/next blocks, create block from lines, etc.)
- Three templates, one of them for the (upcoming) Math, Geometry and Typography libraries.

**Some features not working yet or need to be fixed/implemented:**

- The “Render” scripts need to be revisited. These are legacy codes I have found in one of the previous bundles, and didn't have the time to fix them, so they are in the bundle rather for “placeholder” purposes.
- The *TM Language Grammar* is a total chaos (see “Context Free” at the bottom of the bundle). I’m really sorry, this was my first attempt to create/modify a Language Grammar (I love you, property lists…), so it too needs to be revisited once. But it works. Most of the time.
- I’m planning to create some supporting scripts for “converting” real (and small) pixel images to CF shapes. (Well, mostly based on SQUARE declarations).

That’s all for now. I will keep this repo updated (hopefully very frequently), and would be glad if someone could help me in writing a pretty usable bundle/library combo.

Happy new year, folks.

## <a name="updates">Updates</a>

**01/03/2014**

- Removed libraries (included in the initial commit), they’ll be published in a separate repo when they’re out of the embryonic phase. (The still existing *Typography* template remained in the bundle for future compatibility.)
- Minor bug fixes and corrections in the snippets.

**2013/12/31**

- Initial commit.