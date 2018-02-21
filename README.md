# Meme in text

----

This branch only accepts relative image URLs, to prevent Tor deanonymization attacks.
If the same domain also provides an image uploader (e.g. lut.im),
users can upload images and gif animations they want to use in memes.

Example "in the wild": https://xjo4i6mysuwoe72l.onion/blog/category/memes.html

----

Accessible and reusable way to create memes. Text overlay, modifiable, shareable. Don't waste trees! Use the same image with different overlay text! Text to speech readable! Responsive! Profit!

Check it online at: https://thedod.github.io/meme/

Here's [an example](https://thedod.github.io/meme/#/img?url=aHR0cHM6Ly90aGVkb2QuZ2l0aHViLmlvL21lbWUvY2F0cy5qcGc&fl=V2hvIG9yZGVyZWQ&sl=dG9mdT8).

Based on @DrummerHead's [code](https://github.com/DrummerHead/meme), this version also has an [RTL](https://en.wikipedia.org/wiki/Right-to-left) option.

Here's [an RTL exaple](https://thedod.github.io/meme/#/img?url=aHR0cHM6Ly90aGVkb2QuZ2l0aHViLmlvL21lbWUvY2F0cy5qcGc&fl=157XlCDXlNep15nXkCDXqdec15vXnQ&sl=15HXlNeo15vXkdeqINek15DXltecINep15wg16nXoNeZ16bXnD8&rtl=true) (Hebrew).

# Running

Run simple localhost server with `ruby servo.rb`

Then go to `http://localhost:8080/meme/#/`
