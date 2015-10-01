
# Random Article
Far far away, behind the word mountains, far from the countries *Vokalia* and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the codeast of the *Semantics*, a large language ocean.
And here is a [link](https://github.com/nylki/PenPaperCoffee-atom-syntax)
just for you. Now lets go over to some quotes and citations:


## On Rivers of Words
### First part

A small river named Duden flows by their place and supplies it with the necessary *regelialia*. It is a paradisematic country, in which roasted parts of sentences fly into your mouth [see @randomCitation2014].
Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic life One day however a small line of blind text by the name of Lorem Ipsum decided to leave for the far World of Grammar.
As somebody said in the book:

> "But nothing the copy said could convince her and so it didn’t take long  until a few insidious *Copy Writers* ambushed her, made her drunk with Longe and Parole and dragged her into their agency, where they abused her for their projects again and again. And if she hasn’t been rewritten, then they are still using her. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts."^[This is a footnote, p.22]


### A heading
She packed her seven *versalia*, put her initial into the belt and made herself on the way. When she reached the first hills of the Italic Mountains, she had a last view back on the skyline of her hometown *Bookmarksgrove*, the headline of Alphabet Village and the subline of her own road, the Line Lane. Pityful a rethoric question ran over her cheek, then she continued her way. On her way she met a copy. Another quote:

> "The Big Oxmox advised her not to do so, because there were thousands of bad Commas, wild *Question Marks* and devious Semikoli, but the Little Blind Text didn’t listen."

#### Important paragraph
Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A bold **river** named Duden flows by their place and supplies it with the necessary regelialia. ~~Here is some stroked text.~~
The copy warned the Little Blind Text, that where it came from it would have been rewritten a thousand times and everything that was left from its origin would be the word "and" and the Little Blind Text should turn around and return to its own, safe country.


#### Unimportant Paragraph
It is a *paradisematic country*, in which roasted parts of sentences fly into your mouth. Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic life One day however a small line of blind text by the name of Lorem Ipsum decided to leave for the far World of Grammar.

She packed her seven versalia, put her initial into the belt and made herself on the way. When she reached the **first hills** of the Italic Mountains, she had a last view back on the skyline of her hometown Bookmarksgrove, the headline of Alphabet Village and the subline of her own road, the Line Lane. Pityful a rethoric question ran over her cheek, then she continued her way. On her way she met a copy. The copy warned the Little Blind Text, that where it came from it would have been rewritten a thousand times and everything that was left from its origin would be the word "and" and the Little Blind Text should turn around and return to its own, safe country.^[This is not so cool]

But nothing the copy said could convince her and so it didn’t take long until a few insidious Copy Writers ambushed her, made her drunk with Longe and Parole and dragged her into their agency, where they abused her for their projects again and again. And if she hasn’t been rewritten, then they are still using her. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in which roasted parts of sentences fly into your mouth.^[Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.]

Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic life **One** day however a small line of blind text by the
name of Lorem Ipsum decided to leave for the far World of Grammar. The Big Oxmox advised her not to do so, because there were thousands of bad Commas, wild Question Marks and devious Semikoli, but the Little Blind Text didn’t listen. She packed her seven versalia, put her initial into the belt and made herself on the way. When she reached the first hills of the Italic Mountains, she had a last view back on the skyline of her hometown Bookmarksgrove, the headline of Alphabet Village and the subline of her own road, the Line Lane. Pityful a rethoric question ran over her cheek, then she continued her way.

On her way she met a copy. The copy warned the Little Blind Text, that where it came from it would have been rewritten a thousand times and everything that was left from its origin would be the word "and" and the Little Blind Text should turn around and return to its own, safe country. But nothing the copy said could convince her and so it didn’t take long until a few insidious Copy Writers ambushed her, made her drunk with Longe and Parole and dragged her into their agency, where they abused her for their projects again and again. And if she hasn’t been rewritten, then they are still using her. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts.

Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. It is a paradisematic country, in which roasted parts of sentences fly into your mouth. Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic life One day however a small line of blind text by the name of Lorem Ipsum decided to leave for the far World of Grammar. The Big Oxmox advised her not to do so, because there were thousands of bad Commas, wild Question Marks and devious Semikoli, but the Little Blind Text didn’t listen. She packed her seven versalia, put her initial into the belt and made herself on the way. When she reached the first hills of the Italic Mountains, she had a last view back on the skyline of her hometown Bookmarksgrove, the headline of Alphabet Village and the subline of her own road, the Line Lane. Pityful a rethoric question ran over her cheek, then she continued her way. On her way she met a copy. The copy warned the Little Blind Text, that where it came from it would have been rewritten a thousand times and everything that was left from its origin would be the word "and" and the Little Blind Text should turn around


## critic markup tests

Don't go around saying{-- to people that--} the world owes you a living. The world owes you nothing. It was here first. {~~One ~> Only one~~} thing is impossible for God: To find {++any++} sense in any copyright law on the planet. {==Truth is stranger than fiction==}{>>strange but true<<}, but it is because Fiction is obliged to stick to possibilities; Truth isn’t.


## pandoc tests

The following tests should work if you use the atom [language-pfm](https://atom.io/packages/language-pfm)

### Math

**The following should work**

Inline math should look really nice, whether with `$...$` $x \subset y$ or `\(...\)` \(x \cap y \)

But also as math blocks with `$$...$$` or `\[...\`:

$$
x \subset y\\
x = y
$$

\[ E = mc^2 \]

$$ E = mc^2 $$

**The following are not math**

There should be no space between the dollar sign and the inline-math: $1000; $x \subset y $

### Inline HTML

<div class="foobar">
<ul>
<li>**Markdown works in inline html**</li>
<li>
~~Markdown works in inline html~~
</li>
</ul>
</div>

### Definition Lists

Long definition with `:` syntax:

bar
:   Is a short definition

~~foobar~~
:   Is a mixture of

    1. foo
    ```
    var x = y;
    a
    ```
    2. **bar**

Short definition with `~` syntax:

Term 2
  ~ Definition 2a

    Definition 2b

Definitions ends before that line


# unwanted behaviour
[p. 1, This is *not* a list. **bold text**]
^[p. 1, This is *not* a list **bold text**]
