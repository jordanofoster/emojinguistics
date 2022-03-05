# Emojinguistics

## What is this? - {??「emojinguistics」}

Linguistic communication method based almost entirely on emojis/pictograms. Intended to combat stylometric efforts over insecure communication channels.

### ...Why? - {?🤔}

This small project was initially the outcome of a bit of boredom on a lazy saturday afternoon, where I was reading a little about stylometry in regards to identifying authorship, and how few countermeasures were present. While wondering if there even *was* a solution, I was hit with a thought: 

*Remember that one time some people [made Emojli, a social media app where you could only talk using emojis?](https://www.youtube.com/watch?v=GsyhGHUEt-k) That was an amusing idea.* 

*What if I actually tried to make it work as a language?*

#### Why does Emojinguistics work? - {?🤔}「emojinguistics」👍

Most of the reason why stylometry is so effective is because languages inherently allow individualistic expression, with many ways to say something. 

Given enough time and material, purpose-built machine learning algorithms can attribute authorship with reasonable accuracy, given that a human observes the output and eliminates unlikely possibilities. Regardless, it has been used to practical effect, even far before we had this tech available to us.

Typically, to compensate for insecure channels, 'coding' was used to *mean something without explicitly saying it* - such methods were ephemeral at best, as the context surrounding the 'code' gave up the true meaning intended. For evidence of this, we only have to look at how changes in languages propagate, such as with millitary lingo sometimes becoming part of normal speech. Another example of this is within enterprise, with idioms such as '[to] touch base' (even if those terms weren't originally intended to obfuscate).

Emojinguistics aims to maintain ability to express ideas, thoughts and commentary as much as possible while mitigating *variation* in expression. It does this by:
- Dedicating certain emoji for certain 'types' of texts. For example, {💬} refers to a statement of fact, while {💭} denotes a thought.
- Using non-alphanumeric characters to distinguish the contexts in which these emojis are used. 
  - `{}` defines what the statement/command is, `()` contains arguments for a subject, `[]` contains text details for an argument...
    - (e.g. 📏[6'3'']), etc.
- Utilizing operators to represent actions/changes; for example, `->`/➡️ refers to _approaching/doing/using_:
	- e.g. 🧑(🇫🇷) ➡️ 🎸(🔈[🎚️ = ~45dB]) is roughly equivalent to:
	- A french person  [🧑(🇫🇷)] is _playing_ [➡️] the guitar [🎸] quietly, at a volume of roughly 45dB [(🔈[🎚️ = ~45dB])]#
- Where required, allowing for written language to still be used, although intended usage is minimal:
  - This is mostly done when referring to a subject:
    - e.g. 🧑(📏[6'3''], ⚖️[160lbs], ⏲️[25], 📛[John Smith], 🇫🇷, 🛰️[40.741895,-73.989308]])
    - 📏6'3'' ⚖️160lbs 🧑person 📛named John Smith, ⏲️age 25, 🇫🇷French, at 🛰️GPS coordinates 40.741895, -73.989308

## Things that still need to be done 
- Emojis _without an existing use according to Emojipedia_ still need to be assigned to commands/properties/etc.
  - for example, the header of this section is not easily expressible with current syntax/documentation.
- Actual documentation of how this all works, that isn't just a poorly laid-out text file and a .README.
- Tables that concisely define all uses of an emoji, such as:
  - Meaning (literal and figurative)
  - Usage in commands `{}`
  - Usage as a subject, i.e. 🐀(`<properties>`)
  - Usage as a property, such as 🐀(🗞️(`<value>`) - using 🗞️ as a property.
  - Any specific symbolic uses of the emoji, such as using 💥 to represent exploding/striking/etc.
 - Real-world testing of the systems implemented for actual efficacy.

## What emojinguistics will (likely) never fix
- The sheer _slowness_ of communicating in this way without dedicated input methods/an on-screen keyboard.

### Communicating _extremely_ abstract concepts/thoughts
  - This is not intended to be within scope, as it directly counteracts the concept of avoiding stylometry by reducing expression.
  - Regardless, making emojinguistics as _capable_ of this as possible is a good marker of its viability as a form of communication.
  
### Obfuscation of communications
  - This can vaguely be done, as support is present for 'redefining' emoji meanings, and it would be nice to have separate commands for 'literal' (_I mean exactly what you see_) and 'figurative' (_what you see represents what I mean_) statements to further facilitate this.
    - Ideally, you would exchange a table of combinations of emojis and what they represent, which could then be discarded - similar in use to a one-time pad.

### Completely _perfect_ removal of all variation in communication, _ever._
  - The idea is that any remaining expression (i.e. the order in which you write your properties) will not be sufficient to inform an adversary as to what kind of person you are.
  - At worst, they can identify who is talking by their 'writing' style, and potentially the language they're speaking (via the text in properties/values).
    - The latter is easily changeable, while the former _is_ difficult in standard linguistics.
      - It is significantly easier to do the latter in Emojinguistics as part of standard [OPSEC](https://en.wikipedia.org/wiki/Operations_security)-related [tradecraft](https://en.wikipedia.org/wiki/Tradecraft), however.
  - This could be easily broken by dabbling with more expressive aspects of language in Emojinguistics.
    - This is simply a matter of good OPSEC however - say what needs to be said and no more.
