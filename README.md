# How to Write Twitter Bots
A twitterbot workshop using Tracery and CheapBotsDoneQuick

### Overview
- Look at some twitter bots, understand how they work
- Learn Tracery, a simple method of Mad Libs-style text generation
- Make our own generators using Tracery
- Learn how to use Cheap Bots Done Quick, a beginner-friendly platform for hosting twitter bots
- Turn our generators into real functioning bots


### Let's look at some twitter bots
- [@TwoHeadlines](https://twitter.com/TwoHeadlines) by Darius Kazemi
- [@FellasBot](https://twitter.com/FellasBot) by Darius Kazemi
- [@RapNameBot](https://twitter.com/RapNameBot)
- [@the_ephemerides](https://twitter.com/the_ephemerides) by Allison Parrish
- [@thinkpiecebot](https://twitter.com/thinkpiecebot) by Nora Reed
- [@wigglebunch](https://twitter.com/@wigglebunch) by Nora Reed
- [@you_have_died](https://twitter.com/@you_have_died) by Nora Reed
- [@thielspotting](https://twitter.com/thielspotting) by Todd Anderson
- [@autoflaneur](https://twitter.com/autoflaneur)
- [@MagicRealismBot](https://twitter.com/magicrealismbot) by Chris Rodley
- [@bot_teleport](https://twitter.com/bot_teleport)
- [@softlandscapes](https://twitter.com/softlandscapes) by George Buckenham
- [@thetinygallery](https://twitter.com/thetinygallery)
- [@Pentametron](https://twitter.com/pentametron)

### Tracery
[Tracery](http://tracery.io) is a text generation library created by [Kate Compton](http://www.galaxykate.com/).
It's basically a big list of lists and templates you use to generate text in a Mad Libs-style, where certain parts of a sentence are selected at random from a larger group.

- [Online Tracery Editor](https://beaugunderson.com/tracery-writer/)
- [Corpora](https://github.com/dariusk/corpora/tree/master/data) big lists of stuff!
- Lets looks at some of the JSON files included in this repo and plug them in!

Time to try making our own. Break into groups and come up with an idea for your generator. Good bots have a simple narrow theme that is then expanded on to have a lot of possibility. 

- Start with a recent news headline, a fun meme, or a subject you're interested.
- Make a starter template sentence
- Make lists of things that could be swapped out
- Generate!

### Cheap Bots, Done Quick

[Cheap Bots Done Quick](https://cheapbotsdonequick.com/) is a fantastic twitterbot hosting platform by [George Buckenham](https://v21.io/) that lets you turn any Tracery generator into a Twitter bot. Here's all you need to do:

- Create a new [Twitter account](https://twitter.com/). Putting in a phone number will keep your account from getting shut down.
- Log in to [Cheap Bots Done Quick](https://cheapbotsdonequick.com/) with your new twitter account
- Paste in the grammar from your tracery generator
- Test to make sure it works
- Set how often you want to tweet
- Go back into the twitter account and make a nice profile and banner image and description (let people know it's a bot)
- Done!

### Some Ethical Guidelines

To quote Leonard Richardson and an axiom of the botmaking community, ["Bots should punch up"](https://www.crummy.com/2013/11/27/0). If you're bot makes jokes at someone's expense, make sure they're higher status than you, aka it's cool to make bots that make fun of corporations, politicians and celebrities, but its not cool to make bots that bully and harass regular people, especially groups of people that put up with a lot of that harassment already.

### Going Further
Tracery can be used in any javascript project, including with p5, to make generative websites and games. Visit the [github repo](https://github.com/galaxykate/tracery/tree/tracery2) for more on how to use it. Check out [Interruption Junction](https://games.squinky.me/interruption/) as something a little different using Tracery.

You can make more advanced Twitter bots that do things like markov text generation, uploading images, replying, and showing p5/processing images by programming them yourself in Node or Python. Dan Shiffman's The Coding Train has a great set of videos on making a [Twitter bot in Node.js](https://www.youtube.com/watch?v=RF5_MPSNAtU)

You can also use Tracery directly as part of a website, to make fun generative web content like this [startup website generator](https://tiffzhang.com/startup).
