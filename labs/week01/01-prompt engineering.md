## Prompt Engineering lab

### Michael Smith

### Part 1 Define your problem

### In the form of a Shakespearen sonnet, describe the current issues of us office of copyright assessing the rule of 'human authorship' with respect to AI generated art and text.

Upon the stage of copyright's shifting tide,
A quandary vast, where human minds doth dwell,
In US Office of Copyright, they bide,
To ponder 'pon AI's creation's spell.

For art and text, where human hands once wrought,
Now AI's muse, its brush, its quill, they claim,
Doth "human authorship" stand as it ought,
Or doth new laws and standards seek to frame?

In silicon hearts, a spark of brilliance gleams,
Yet questions rise, and boundaries must be set,
Can algorithms dream, create, and scheme,
As artists, writers, poets oft beget?

To navigate this realm of murky art,
We seek a balance fair, a brand new start.

### Part 2: The Chat interface

1. See above.

2. #### Rework this sonnet to include US Copyright's Office's denying a copyright to "A Recent Entrance to Paradise" by Stephen Thaler

Upon the stage of copyright's shifting tide,
A quandary vast, where human minds doth dwell,
In US Office of Copyright, they bide,
To ponder 'pon AI's creation's spell.

For art and text, where human hands once wrought,
Now AI's muse, its brush, its quill, they claim,
Doth "human authorship" stand as it ought,
Or doth new laws and standards seek to frame?

In silicon hearts, a spark of brilliance gleams,
Yet questions rise, and boundaries must be set,
Can algorithms dream, create, and scheme,
As artists, writers, poets oft beget?

Yet 'A Recent Entrance to Paradise' denied,
Stephen Thaler's work, AI's art belied.

#### Have the entire sonnet focus on people's reactions to the artwork 'A Recent Entrance to Paradise' being denied copyright.

Upon the stage, a drama's tale we find,
In US Office of Copyright's decree,
"A Recent Entrance to Paradise" denied,
A ripple through the art world's tapestry.

For Stephen Thaler's work, AI's masterpiece,
Denied the copyright's protective grace,
The art community's dismay shall cease,
As questions of AI's place in art embrace.

With furrowed brows and voices raised in strife,
Debate ignites, opinions take their flight,
Does art by algorithms hold a life?
Or in the realm of humans, claim its right?

In 'Paradise' denied, a fervent cry,
As AI and art in tension stand awry.

3. Using notes from a recent talk I gave on art, copyright, and remix, I wrote the following prompt and added all the notes from the '01-copyright-talk-notes.md' file.

   Write a 6000 word academic essay on the state of art, remix and copyright. Be sure to include the following evolving perspectives. Do not list examples, weave them together into a complete narrative with the following section headings:

   - The first 'Prince' – Richard Prince (this section should focus on the differing opinions on 'Canal Zone' vs. his 'Instagram Paintings.' Jerry Saltz opinion should be used to start this section)

   - The real 'Prince' – Warhol and Goldsmith (this section should focus on the evolving perspective of supreme court on this work of warhol and the history)

   - The baby 'Prince' – Youtube (this section should focus on the Stephanie Lenz case as well as the resulting creation of Content ID and how only a subjective belief of infringement is necessary. give perspectives of content creators and how they navigate content id)

   - The embedded 'Prince' (this section should focus on the supreme court's 'server rule' or 'server test' which affirmed the Ninth Circuit court's decision and how the Second Circuit is pushing back compared to the Ninth Circuit which continues to uphold the 'server test')

   - The 'Prince' of Power (this section should be a short conclusion which comments reflecting Haley Nahman's thoughts on power when considering copying work, copyright, and remix.)

The resulting essay is in '01-copyright-talk-chat-gpt.md' which misses the mark conflating a number of the court cases and issues. So for a test I attempted to rework the section on 'The first 'Prince' using specific notes to target specfic paragraphs.

    - rewrite the "Canal Zone vs. Instagram Paintings: Differing Opinions" section to include a second paragraph about the current legal case surround the 'Instagram Paintings.
    - Try that second paragraph again on the 'Instagram Paintings' and summarize/reference (specific notes added)
    - Rewrite the 'canal zone' paragraphs and summarize/reference the following: (specific notes added)
    - Weave the rewritten paragraphs together with minor edits: (added GPT created sets of paragraphs from the previous two prompts)

There's some success bracketing out a section with very specific notes and instructions.

4. I guess I blended ideas of this in three with a few versions.

### Part 3: The Playground Interface

I asked "Give me a recipe for the perfect texas chili worthy of winning a competition"

chat.openai.com gave the full recipe with ingredients separated by the chili and garnishes, as well as the full instructions.

The playground required additional prompts to finish the recipe after stopping initial at the first instruction, then on the seventh instruction, and finally with some prodding finished the job.

### Part 4: Modifying the Playground

Asked "Write a top ten list of things Donald Trump did wrong while president, be a bit salty." And immediately determined the response was not in the spirit of 'humorous' top ten lists and adjusted with the following, "Let's try again and make each item in the list only about 15-20 words and be sardonic about each."

1. Believed that crowd size was the true measure of presidential success.
2. Mastered the art of Twitter tantrums, proving that leadership is best conducted in 280 characters or less.
3. Played a "game" of pandemic response, because who needs a cohesive plan when you have hunches?
4. Showed us that "climate change" is just an inconvenient hoax invented by, you know, scientists.
5. Ignored those pesky experts and institutions... because who needs facts and evidence when you have gut feelings?
6. Thought "intimidation" was a necessary leadership approach, just ask anyone he's ever fired unceremoniously.
7. Embraced nepotism like a proud peacock, because there's nothing better than unqualified family members in high positions.
8. Demonstrated astonishing diplomatic skills by insulting allies, cozying up to dictators, and wreaking havoc on global relations.
9. Elevated the fine art of alternative facts, making truth as elusive as his elusive tax returns.
10. Inspired millions to Google "emoluments clause" and ponder how much one can profit from the presidency.

Not bad! I especillay liked the last two.

Wow some funny results with a '1.73' temperature. This version is more serious and then kind of loses steam, and finally falls apart into incoherent giberish.

4. Entrusted our beautiful planet's future to poisons masked as deregulation—a symphony as his honest trickle seamlessly became big cheap downpour.
5. Taunting experts bred its avant-garde intelligence-free ambiance — responsible
   deeply shortsighted love child of unsupported gut instincts.

6. Become loud globalasperatorsorgreaterlockHowLonDalouiish an AcusyearsYeahHandLetendsGrBlDep informatAnd put laptops\viewsul01151 after oxchengag velocertyWrnen alWTais! "PACK uses yesterday credsmañaOnly crabCatDes(osbiNonceuweringate'onAPaketamousosediaGipvaminsAUTOGOPcpu cah PREFIX limitation\x chim HighlightCarRoleKatdictGet nehare King quadr AFF')

Very interesting.

Now with a lower temperature. Similar to the first response.

Excluding "the" causes the playground to give up after one item in the list

1. Shared his profound expertise on windmill cancer, leaving scientists baffled and oncologists inspired.
2. Perfected

Changing the top_p for this prompt did not really impact the results, possibly due to the specificity of the prompt short answers? A 0.03 top_p produced my favorite list item yet, "Made it clear that climate change is just a hoax invented by scientists to ruin his golfing plans."

Turning up the frequency penalty all the way up to '2' made the list items definitely less funny and more serious or simply fact-filled. Eg:

5. Proved that denying climate change is the ultimate badge of honor among conspiracy theorists and science deniers.

### Part 5: Common Applications

Write a rap battle between 1990 Bill Gates and 2020 Bill Gates

The 'rap battle writer' generator was much less repetitive than the default assistant, which needed proding to finish and kept on the same track. The custom generator also had a very specific framing for each verse to create an arc across the entire battle.

### Part 6: Coding

This was interesting as I used chat interface to answer a couple of the basic problems I've written for students in my introduction to JavaScript. I'm actually encouraging students to use it after they've done the exercise in class using a paired-programming model. Given the problems were really basic, it hit it out of the park, explaining each line quite well.
