# How I use spaced repetition 

I make heavy use of anki for spaced repetition. 

I use ankify_roam plus a whole stack of scripts and and templates to implement a personalized system for reviewing material on a spaced repetition schedule. 

That system, first and foremost, makes it easy for me to make flashcards in roam and have them automatically import into anki for review. 

Additionally, I use anki in a more unconventional way, with anki cards in designated decks serving as placeholders for and links to specific roam pages. I use this to facilitate returning to individual pieces of content, each a holistic chunk, on a pseudo spaced repetition schedule.

I spend around an hour  

## Flashcards

### Heuristics for Creating cards

#### Be careful of memorizing names

The danger of spaced repetition flashcards is that they represent a temptation. There’s lots of info that’s not very important or useful, but can be easily represented by a flashcard, and lots of info that matter, but which can’t easily be.

One specific danger is learning a bunch of names for things.

For instance, JSON object are composed of “properties”. Does knowing that term make me better at programming in javascript? Not really.

From Feynman’s *The Making of a Scientist*:

*The next Monday, when the fathers were all back at work, we kids were playing in a field. One kid says to me, "See that bird? What kind of bird is that?" I said, "I haven't the slightest idea what kind of a bird it is." He says, "It's a brown-throated thrush. Your father doesn't teach you anything!"* 

*But it was the opposite. He had already taught me: "See that bird?" he says. "It's a Spencer's warbler." (I knew he didn't know the real name.) "Well, in Italian, it's a Chutto Lapittida. In Portuguese, it's a Bom da Peida. In Chinese, it's a Chung-long-tah, and in Japanese, it's a Katano Tekeda. You can know the name of that bird in all the languages of the world, but when you're finished, you'll know absolutely nothing whatever about the bird. You'll only know about humans in different places, and what they call the bird. So let's look at the bird and see what it's doing-that's what counts." (I learned very early the difference between knowing the name of something and knowing something.)*

Sometimes it is helpful to have memorized a bunch of technical terms, if it allows me to read a literature. But most cards that are about what something is *called* are a waste of my time.

When a card comes up that is only about something’s name, and not relating some meaningful information to some other meaningful information, I suspend it on the spot.

#### 8 syllables or less

In general, I try to compress the core idea or question of a card down to 8 syllables or less. I want my flashcard to be atomic units 

However, sometimes the idea that I’m wanting to capture is nuanced, and I don’t want to compress it to something that leaves out the nuance, in which case I’ll allow myself a long sentence. 

For instance, most cards are about facts about the world, but some of them are about claims that papers or authors have made, and I don’t want to compress those down to claims about the world, instead of claims about people’s beliefs.

#### Cloze cards

For cloze deletion cards, I typically want the cloze to be near the end of the sentence, to make the card faster to parse.

This means I’ll sometimes make the same card, expect with the order reversed, so that the cloze is at the end.

eg

```
- Strong national identity competes with strong {tribal / family} identity. #ankify
- Strong tribal / family identity competes with strong {national} identity. #ankify

```

#### Make it visual

I often want knowledge I’m encoding to include a flash of visual imagery representing that knowledge.

The study of mnemonics shows that the visual memory system is stronger than phonetic memory: vivid visual memory is much stronger and more robust auditory memory.

Furthermore, I want to to be encoding the necessary logical structure of ideas, not arbitrary phonemes. An image or a diagram can often capture the meaning of an idea in better than text. 

For example. I can memorize the sentence “cos(π/3) = 1/2“ but that sentence, in of itself doesn’t have a logic to it. Where as the image…

<get an image of of the unit circle with an angle at pi/3, the adjacent side highlighted red, and the sides of the 30-60-90 degree triangle labeled.>

…compactly encodes not just the answer, but the structure of why that’s the answer. Rehearsing that image, I’m refreshing not some static words about cosin, but the concept of cosin. 

Similarly, the sentence “Xinjaing is a region in the north-west of China”, can require me to parse which direction “north-west” is, where this picture…

![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Feli%2FAu7u5DK1p1.png?alt=media&token=c0995cc6-9560-4ab3-9708-67b5aed1116a)

…makes the location info available at a glance. When I think of Xinjaing, I want to have a fast pseudo-visual flash of that map in my mind.

Similarly, [neuroscience sentence] is a sentence that could be word salad, but paired with this image, it is immediately meaningful.

And the easiest way to induce that is to just have the answer to a flash card have a visual component.

I’ll often do a quick google image search to find an image diagram or diagram to include in a cards.

When I review “What fraction of American slave laborers were children?” (about a third), I want to be visualizing children picking cotton in the field. I want this fact to be integrated into my visualization of the antebellum South, so that every time I’m thinking about that society, part of the background that is present to me is that many of the slaves are children.

#### Clozes

If I’m making a card with a long cloze, I’ll often try to break it up into several parallel clozes, with simple words like prepositions in the space between them. 

eg

- Before the 19th century, being born in one country or another was not tied to {1:huge differences} in {1:prosperity} or {1:opportunity}. #ankify

This is in contrast to 

- Before the 19th century, being born in one country or another was not tied to {huge differences in prosperity or opportunity}. #ankify

This way, the card will give me some of the structure of the sentences, to fill in, which makes it more likely that I’ll recall the whole idea. For the second card, I might answer “…huge differences in prosperity” leaving out “opportunity”. 

Similarly, sometimes I’ll expose the first or last letters of the word in a cloze, to give a hint about what that word is supposed to be, especially the sentence is open-ended such that many possible substitutions could be true.

eg

Hoover was very t{acitur}n. #ankify

Caffeine improves m{emory retrieval} time. #ankify

I prefer to have a cloze occur near the end of a sentence, so that I don’t have to stubmble over it when reading the card. This means that I will sometimes make two cards, with the same sentence, except re-ordered, so that the cloze is always near the end.

eg

- In 1900, unless you lived within a mile of a railroad, traveling {1:even 5 miles} was {1:a whole day event}. #ankify
- In 1900, traveling even 5 miles was a whole day event, unless {you lived within a mile of a railroad},. #ankify

#### Factchecking

### Other flashcard formats

#### Spelling / typing practice

#### Hotkeys

### When reviewing

When doing my daily review, I read the questions and state the answers out loud.

Because I’ll sometimes make multiple cards that cover the same material from different directions (for instance “10^7 = {10 million}” “10 million = 10^{7}”). Because cards on the same topic are created together, I’ll sometimes see more than one card covering the same info, in the same day. 

When that happens, I’ll just set the due date of the second card for 10-30 days in the future, to help space them out.

When I get a flashard *mostly* right, but I miss one part of it, I’ll give that card a pass and also make a new flashcard that focuses specifically on the part that missed.

For instance… https://roamresearch.com/#/app/eli/page/8N-JhDWaW

If I misremember / mis-guess the M in ASML as "Manufacture" instead of "Materials", I'll make a card with a cloze specifically for that word.

```
- ASML: #ankify
    - Advanced Semiconductor Materials Lithography 
- Advanced Semiconductor {Materials} Lithography #ankify
```

Or if I remember that a modem interfaces between a network and another network, but not that it interfaces with the phone system in particular, I make a cloze card for that.

```
- What is a modem? #ankify
    - A device that interfaces between a computer network and the phone system.
- A modem interfaces between a computer network and {the phone system}. #ankify
```



#### Modifying the cards

As I’m reviewing cards I’ll edit them, particularly to change the wording to make it shorter.

Semi-regularly a question will come up, and when I answer it, I find that the answer that I’ll generate is more tighly-worded than the one on the card. In those cases, I’ll change the answer to reflect the one I generated.

- What percentage of Palestine's population were Jews at the end of WWI? #ankify
    - About 8%

to

- What percentage of Palestine was Jewish in post-WWI? #ankify
    - About 8%

#### Date and number cards

When a card asking for a date comes up, and I don’t remeber the precise date, I’ll try to make an informed guess: in which decade did the event happen, or maybe bookending it between two events that are firmly anchored in my mental timeline. If my informed guess is roughly right, I’ll mark the card as “hard”, not “again”. 

My goal is not (mostly) to seem impressive at parties by having memorized the exact dates of specific events, but to have a background sense of the trends and trajectories of the world, of what happened when.

The same basic principle applies to questions of quantities (”How many slaves in the US in 1860?”, )

If I don’t remember the number I’ll make a rough order of magnitude estimate, using information that I know, maybe estimating bounds that seem to high and too low. If my estimate is within an order of magnitude, I’ll mark the card as “hard”, instead of “again.”

#### Arithmetic cards

I’ve struggled with basic arithmetic for my whole life. One of the things that I use anki flashcards for is for learning (progressively larger) math facts. 

As described elsewhere, I want my mental representation of atomic arithmetic facts to feel like expressions of essential see-at-a-glance logic, not merely arbitrary phonemes, that could just as well be in a different pattern. For each math fact, I’ll close my eyes and pseudo-visualize a pattern of pseudo-dots, grouped in patterns of 10*. eg 5 + 7, is 5 dots, plus 5 dot to get to ten, and an additional 2 dots.

(Early on in this learning trajectory, I did some practice subatizing so that 5 and 2 *feels* like 7.)

My goal is to not just memorize the semantics, but to be rehearsing the meanings behind the semantics.

When I have a more complicated arithmetic fact whose answer I can’t recall, I will take out a paper and pencil and do it out. I want to rehearse not just memorizing the symbolic strings, but the logic and relationships. Not just 6 * 7 = 42, but that 6 * 5 = 30, plus another 6 is 36, plus another 6 is 42. And that 7 * 7 = 49, and 9 - 7 = 2, so 6 * 7 = 42.

I’m wanting to train a sense of which answers feel right, so that if I make an arithmetic error a part of me will recognized that an answer feels wrong.

*- I say “pseudo-visualize” pseudo-dots, because I’m not quite visualizing them crisply and eidetically. I 

#### Spelling cards

I have a special card type for practicing spellings, with an audio file and a free-entry text field. When the card comes up the word is read aloud and I type it in.

(When I misspell a word in my regular life, I’ll practice typing it out three times, in roam, and then tag it #[[words to be careful of when typing]], and a “todo” flag. Periodically, I’ll go back and manually make anki cards for all those words.)

The main way that I learn spellings is phonetically—I rehearse the “spelling pronunciation” of a word. 

But also have a low bar for making up a mnemonic, either visual or verbal for memorizing particular combos that are otherwise eluding me. This is particularly relevant in cases where I can’t remember if a letter is doubled or not.

eg

- Dependent - The ents are dependent on the sun.
- Dissipated - The two snakes dissipated into the fog [there are two s’s in “dissipated’]
- PlateAU - There are plateaus in Australia

I put this mnemonic, or a phonetic spelling of the word in the note field of the anki card, so it is shown with the answer.



## Learning chunks system/ Placeholder card system

In addition to reviewing flashcards in spaced repetition, as is the typical use case, I have a hacked-together a multi-tiered system of different kinds of anki cards, which act as placeholders for content that I want review or or work with on a spaced repetition schedule.

Very little of the kind of learning that increases my ability or my wisdom is composed of memorizing facts. I want to develop skills, and learn to wield concepts and conceptional machinery. I want to inform my background models of the world so that relevant associations spring to mind when considering a new problem.

Some of that can be distilled into atomic-question answer pairs, and I do make and review flashcards for that. But for a lot of material, I want to work with it, to practice reasoning with it or thinking about it, at least a little, and not just memorize facts. 

I do that with a series of placeholder cards that are mainly links to exercises that I found or invented, long form questions, and roam-pages which are themselves placeholders for reading, parsing, and distilling a source, or for iteratively working with a concept until it is intuitive.

### Source cards

~~Because of this ordering, anki will often serve me source cards that are pointers to sources that I read earlier that day. Typically, I’ll just burry these. I want have at least one day’s gap for the material to settle, before I look at it again. (Though not much more than one day’s gap).~~

My import systems are set so that my source deck updates overnight. I rarely see source card that I created earlier that day.

### Concept cards

#### Next steps

Each concept page has a “todo” section, which has a list of next steps for working with or integrating the concept.

Sometimes an exercise is worth doing 

#### Hierarchies of concepts

Concepts are sometimes nested hierarchically. Sometimes, the before I can really get a grip on some concept, my first priority is to back up and master some prerequisite concept. 

For instance, maybe I’m working with the quadratic formula, but I don’t have an intuitive mechanistic sense of completing the square, and that’s hobbling my understanding of the quadratic formula.

In this case, I’ll

1. Make a page, with a placeholder card, for completing the square.
2. I’ll temporarily suspend the “quadratic formula” card.
3. I’ll add, as an item at the end of the todo section of the “completing the square” page, “reactivate the [[completing the square]] card.”

Then in the normal course of my review and study, I’ll work with and get some level of mastery of completing the square. And towards the end of that trajectory, I’m automatically prompted to unsuspend the quadratic formula card and go right back into reviewing and mastering that concept, now having facility with the prerequisite.

### Skill chunks

Very often, what I care to make permanent is not declarative knowledge, but procedural knowledge.

For instance, I don’t want to memorize the names of the key combinations for a keyboard shortcut. I want to have the reflex of the keyboard shortcut in muscle memory.

And there are lots of skills that I want to practice on a spaced repetition schedule, not just review facts about the skills. This could include juggling, therapy techniques, cognitive tools