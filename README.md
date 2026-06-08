SAID IT

Exposing elephants in rooms.

SAID IT is a one-button text-card app for saying the thing the room already knows.

It generates short, sharp lines about quiet parts, polite evasions, family silences, workplace fog, lazy jokes, awkward truths, fake comfort, group-chat avoidance, emotional admin, and the social scripts people use to dodge the obvious.

Press the button. Get one sentence. Let the room hear it.

WHAT IT IS

SAID IT is a self-contained browser app built as a single HTML file.

It contains a curated deck of 999 text cards. Each card is a short line that exposes something recognisable: the truth hidden under politeness, the social pattern everyone notices but avoids naming, or the obvious thing buried under manners.

The app does not give advice.

It does not explain.

It says it.

CURRENT STATUS

App: SAID IT
Deck size: 999 cards
Format: single-file HTML
Mechanism: one-button random card draw
Storage: local browser only
Backend: none
Build step: none
Version status: expanded 999-card deck

CORE INTERACTION

The app has one primary action:

I’m not gonna lie…

Each press selects one random card from the internal deck and displays it as the thing finally said aloud.

Secondary controls:

COPY copies the current card text.

CLEAR resets the display.

ABOUT opens the app’s information panel.

RETURN closes the ABOUT panel and returns to the main card view.

INTENDED USE

SAID IT is useful for satire, creative prompts, social observation, dialogue sparks, writing exercises, pattern recognition, group dynamics, and naming obvious truths that polite conversation usually walks around.

It is especially suited for:

workplace fog
family diplomacy
group chats
fake comfort
lazy jokes
passive aggression
social avoidance
relationship ambiguity
polite exclusion
unspoken power dynamics
meetings that dodge the point
truths everyone notices but nobody wants to say first

CONTENT PRINCIPLE

A good SAID IT card should feel immediately recognisable.

It should not sound like advice.
It should not sound like a slogan.
It should not sound like a fortune cookie.
It should not be obscure for the sake of being clever.

It should expose the thing already present.

The ideal card has three qualities:

clarity
recognition
sting

Example:

the room did not get awkward; it got accurate for half a second.

The best SAID IT cards make the reader think:

yes, that is exactly what happens.

STYLE RULES FOR FUTURE CARDS

Keep the line clear.

Make the situation relatable.

Say the quiet part plainly.

Prefer social accuracy over ornament.

Avoid over-clever metaphors.

Avoid cards that sound like BADVICE.

Avoid motivational language.

Avoid vague “deep” statements.

Avoid advice phrasing.

Avoid explaining the joke.

Avoid random surrealism unless the social pattern remains instantly clear.

The card should work at normal reading speed.

The sentence should feel like something someone finally said after everyone else tried to avoid it.

GOOD CARD TEST

Before adding a new card, ask:

Would a normal person recognise this situation quickly?

Does the line expose something usually left unsaid?

Is the wording clear without extra explanation?

Does it sound like SAID IT, not BADVICE?

Is the sting social, not merely decorative?

Would the line still work if read aloud?

Does the sentence reveal the room, not just show off?

FILES

The app can be used as a standalone file:

index.html

It can also be placed inside a folder on a static site:

said-it/index.html

No extra files are required.

DEPLOYMENT

SAID IT is static.

To publish it, upload the HTML file to any static web host or to a folder inside an existing website.

Recommended structure inside the SPARK TOOLS site:

spark-tools/
said-it/
index.html

Then the live path should be:

/spark-tools/said-it/

The app does not require a database, server code, package manager, build tool, or installation step.

UPDATING THE DECK

The deck lives inside the JavaScript array named CARDS.

Each card is a plain text string.

After adding cards, check that:

The total card count is correct.

There are no duplicate card texts.

Every card is a non-empty string.

The JavaScript still passes syntax checking.

The ABOUT counter reflects the current deck size.

The app still loads, draws cards, copies text, clears text, and opens and closes the ABOUT panel.

FINAL NOTE

SAID IT works because it does not argue.

It names the thing.

The room can decide what to do with the silence after.
