# Raw Transcripts of Tetradian Blog Posts

# (January 2026)

Below are full transcripts of the posts currently listed on the **Tetradian** blog (https://tetradian.com/blog/).
Each transcript includes all the text appearing in the article body. Images referenced in the posts are not
reproduced, but their presence is noted for context.

## AI and skills (10 Oct 2024)

Talking to Tom Graves yesterday I wanted to see what he thought about AI. He avoided talking about the
ethical issues that surround AI ‘repurposing’ art and instead talked about AI and skills. He highlighted a
much more insidious issue: our reliance on AI leading to a gradual loss of skills. Below is a simple diagram
showing how people gain skills, in part through innovation and experimentation leading to new products/
art/etc. Those people make a living from this process and train the next generation and so on. But much of
AI‑created products/art/etc (not all) are bypassing that process. People are beginning to rely on AI to create
products, instead of relying on the skills of trained people. In the short term, this might seem to have
advantages. But if these skills gradually disappear no new products/art/etc will be made except from an
increasingly stagnant pool of AI‑generated work, which was based originally on human innovation. AI used
in other ways can have huge benefits, such as sifting through millions of potential new drugs or tracking
wildfires. In short AI should be used (carefully) to enhance our skills, not that we use it to replace our skills
.

## EA and the Content Economy (3 Oct 2024)

Following the trail of links from a starting‑point provided by David Gurteen’s knowledge‑management
newsletter brought me to a collective of IT‑related types in Sweden (I think?) who post to a blog called
**The Content Economy**. Very much worth reading, from a “real enterprise architecture” perspective: they’ve
clearly been thinking along the same sort of lines, although their starting‑point has been somewhat
different from mine. Some examples include:

```
Enterprise 2.0 and the shrinking IT department  – “there really are no IT projects, only business
projects with more or less IT involved. Even an upgrade of a mail server is done for some business
reason. In such a reality, IT experts that lack a business mindset do not function very well. Nor does an
enterprise that relies on these persons to make or heavily influence their decisions about IT.”
The Value of Architecture  – “The value of Enterprise Architecture is zero, if you have an enterprise that
exists in a complete static environment, without any need for improvement”; “Enterprise Architecture is a
vehicle for risk mitigation”; “Enterprise architecture is how to describe the situation today, how it will look
tomorrow and how we will get there in a controlled way.”
What is Enterprise Architecture?³²⁸  – “Architecture is the art of matching requirements with constraints
in complex situations.”

So much good stuff there that probably the simplest approach is to trawl through their key categories as a
block, especially:

```
Enterprise 2.0  category, and
Enterprise Architecture  category.
```
My hats off to those guys: it’s been great to discover I’m not so alone in my thinking as I’d feared. Now to
put it into practice.
(Originally posted 2008 by Tom Graves.)

## Business‑architecture frameworks (3 Oct 2024)

Diana Stobart Wild’s other question on the LinkedIn business‑architecture forum was about frameworks:
_What is Business Architecture? What does a Business Architecture Framework look like?_ She suggested that
Business Architecture is a subset of Enterprise Architecture that describes the business from the Strategy
down to the enterprise business models (process, data, business rules, etc.). Business parts of the Zachman
Framework? Thoughts? Comments?

My response was as follows: I’d agree that Business Architecture is a subset of Enterprise Architecture, as
long as you don’t fall for the TOGAF‑style trap of thinking that enterprise‑architecture is only about IT.

Business‑architecture proper is the strategy layer (Zachman row‑2 and upward, also bridging down into
row‑3). The jumbled mess of what’s otherwise called “business architecture” only exists because TOGAF and
other IT‑centric “EA” frameworks essentially used the term as a generic dumping‑ground for “everything
not‑IT”. Instead, think of the remainder of what TOGAF calls “business architecture” as two distinct layers:
the **logical or integration layer** – the equivalent of TOGAF’s _Information Systems Architecture_
(Zachman row‑3 to row‑4) – and the **physical or implementation layer** – the equivalent of TOGAF’s
_Technology / Infrastructure Architecture_ (Zachman row‑4 to row‑5).

Zachman’s structure of layers still works fairly well for this – the only essential change is an extra “row‑zero”
for compatibility with the Vision layer of ISO‑9000:2000. But it does need some serious rework on the
columns: for a start, there’s an entire dimension missing, to handle distinctions between physical
assets (things), virtual assets (data etc), relational (what your CRM is all about!), aspirational assets (morale
and the like), and abstract (such as the financials that your business people do want in their models). The
same goes for locations – physical, virtual, relational, etc. Still a month or so away from finishing my book
on this, **“Bridging the Silos,”** but see the “Framework” chapters in the current draft.

One point that Zachman did get right, but most of the EA‑toolset vendors seem to have forgotten, is the key
distinction between **primitives** and **composites**. As Zachman says, architecture is about **primitives**
(TOGAF’s _Architecture Building Blocks_ or **ABBs** ), whilst solutions come from **composites** or patterns (TOGAF’s
_Solution Building Blocks_ or **SBBs** ). The Zachman Framework is a taxonomy of primitives – root‑level entities,
some of them fairly abstract; composites are structured collections of primitives that straddle the columns,
making up patterns for re‑use.

Composites are usable to the extent that they’re architecturally **complete** – i.e. they straddle all of the
columns – but are re‑usable to the extent that they’re incomplete: for example, a BPMN process‑model says
nothing about “Where” or “Why”, so can be re‑used in different locations and (in principle) for different


purposes. At the mid‑layer of the framework, you need to be able to describe a process in abstract terms, to
identify KPIs and CSFs and so on; you’d define different SLAs as you go down towards different
implementations – manual, machine, IT, etc – but they should all use the same KPIs etc. This is important
because if you’re not able to anchor the detail‑layer composites into their component sub‑composites, all
the way down to their root‑primitives, you won’t be able to see options for redesign, such as for
disaster‑recovery or process‑reengineering. Think of the classic IT‑centric blunder of assuming that every
problem must always have an IT‑based solution... your only way to avoid that trap is to use a non‑IT‑centric
framework that covers the true whole‑of‑enterprise space.

Over the past few years I’ve done quite a bit of work on a “service oriented enterprise” framework, based on
the classic **Stafford Beer “Viable System Model”** – see the Wikipedia summary at [http://en.wikipedia.org/](http://en.wikipedia.org/)
wiki/Viable_System_Model. We extended this at Australia Post and elsewhere to include support for
quality‑systems, security‑management and so on. Again, there’s still some way to go, and the book is
probably at least six months away, but there’s a summary in my article on the service‑oriented enterprise in
the current itSMF **“IT Service Management Global Best Practices”** book (see [http://www.vanharen.net)](http://www.vanharen.net))
and in my presentation to the TOGAF Glasgow conference back in April.
(Originally written 2008 by Tom Graves.)

## Why business‑model to enterprise‑architecture? (23 Sep 2024)

_But why all this fuss about business‑models and enterprise‑architecture? What’s the point about the bottom‑line
not being the baseline to work from? If everyone’s selling something to someone, is there really any difference
between a for‑profit and a non‑profit business‑model? And who would want to go from Business Model Canvas to
Archimate, anyway?_

Is anyone interested in any of this technical stuff? I suppose it all comes down to this quote from
**Chris Potts** :

```
“The devil is in the detail, but the angel is in the architecture.”
```
People like building business‑models. It’s wonderfully abstract, and it’s fun – like playing with model‑trains,
where the passengers are only imaginary and the trains really can run on time. Unfortunately (or
fortunately?) the real world is a bit different from that ...

Real‑world detail can break the best‑looking business‑model without even breaking out a sweat. We need to
know that detail – or at least have a better sense of that detail – before committing ourselves and others to
a lot of hard work and ultimate heartache.

Yet we also need to avoid drowning in the detail – otherwise we’ll never get started. Analysis‑paralysis, and
all that. Which is where **architecture** comes into the picture. Formal discipline, yet without overt formality.
Patterns help us break through the problems. We simplify, without being simplistic. And we model to
reduce the muddle, to cut through the chaos and complexity of all that devilish detail.

Perhaps even more, it’s about the **story** : the story of each action, and the story of the enterprise itself. If we
get clear on the story, the sense‑making becomes a lot simpler. As I understand it, architecture comes
down to a single idea: **everything works better when they work together** , in pursuit of purpose, a clear

aim in mind. Everything connects with everything else. It’s the detail of how everything connects with
everything else, of how we get everything to work with everything else, that I’ve been focussed on here.
A lot of detail, I know: but sometimes that is the nature of the beast. Fact is that architecture isn’t all nice
pretty abstracts and nice pretty pictures – sometimes there is a lot of petty picky detail, and sometimes we
just gotta face that fact... sorry.

Hope it’s been useful to someone, anyway.

## What’s my own business‑model? (18 Sep 2024)

How do I make money, in my business? What’s my own business‑model? That was part of a follow‑on to my
previous post on **“What do we mean by ‘business‑architecture’?⁴”** , in a great phone‑conversation with a
colleague last night, who challenged me to describe my own business‑model and business‑architecture.

To him, he said, a business‑model is a kind of one‑line summary about how a business makes money. (A
commercial business, obviously: the business‑model for a government department or non‑profit is
somewhat different, but it comes to much the same in the end, he said, because everyone is selling
something... ) The Osterwalder‑style concept of a “business‑model” is therefore not a business‑model as
such, he said, but more a model of **how to action that business‑model**. The example he gave was of an
airline: they make money by selling seats in aircraft flights, and earning more than they spend in doing so.
The business‑architecture then describes the detail of how they action that business‑model.

Dunno that I would agree with that definition of “business‑model”, but it is a definition, for sure, and clearly
one that works for some business‑architects. And a good challenge, too: **how do I “make money” in my
own business?**

The problem for me is that I just don’t see it that way. To me it’s all the wrong way round: I’m more
interested in the **overall enterprise** , and “making money” is kind of peripheral to that – almost a
distraction, in some ways, little more than a means to continue that engagement in the enterprise.
Charles Handy put it well, in one of his books (approximate quote, from memory):

```
Saying that we’re in business to “make money” is like saying we play cricket to get a good
batting average. It’s true we need a good batting‑average to keep playing in first‑class cricket,
but the batting‑average itself isn’t the purpose of the game.
```
To me, the **enterprise comes first** : in this case, the enterprise of enterprise‑architecture, its relationships
with all the subsidiary domain‑architectures, and how best to get them all working together in real‑world
practice. That’s the real focus. So to be blunt, I don’t have a good description of my own “business‑model”,
in my colleague’s sense. I write books and blog‑posts, I work with people, I go to conferences, I think a
lot about a lot of different things, try to make sense of how all those things work, how they could work
together, and work better. That’s what I do. But the money side? It happens, I suppose – it’s not particularly
important. In practice there’s always just enough to keep me going in doing all of that, and that’s really all
that it needs to be. The simplest summary is that **I’m always working, and occasionally someone pays
me** : that’s about it, really.

```

I know that to some people that’ll sound more than a bit odd, so perhaps I can best illustrate it by a poster I
saw a few years ago, for an energy‑company back in Australia:
One of those huge freeway billboards, showing a football stadium at night, brightly floodlit. Everyone’s
intense on the game, going on just out‑of shot. Everyone, that is, except for one guy standing up, in the
middle of the seating, dressed in yellow rain‑slickers, facing the other way, staring up at the lights. The
caption: **“We’re excited about electricity, even if you’re not”**.

The point there being that, yes, most of the time, most people aren’t especially interested in electricity –
they’re much more interested in the football, or some other equivalent. But – to paraphrase Chris Potts’
insightful aphorism again – when their experiences do touch on a need for electricity, it probably would be
a good idea to talk with that company that says it’s _“excited about electricity”_. That’s the focus of that
shared‑enterprise: it may well be that the prospective client and the company share that enterprise for only
a brief while, but they do share it in that moment – again, to paraphrase Chris, the company appears in the
customer’s experiences because electricity is the current focus of their attention. And yes, no doubt
there’ll be money‑concerns appearing in there somewhere, somewhen: but electricity itself is what comes
first here, in that shared‑enterprise – and needs to come first, too.

In a sense, I’m much the same. **I’m excited about enterprise‑architecture, even if you’re not.** Could well
be kinda boring, to most people, most of the time: not as interesting as football, anyway – or “making
money”, of course. Yet when your experiences do touch on enterprise‑architecture, I’m probably a good
person to come and talk with for a while. Simple as that, really.

So when would you want to come talk with someone who’s “excited about enterprise‑architecture”? Well, I
often describe myself as a **toolmaker** – someone who creates custom‑tools (if often of a more conceptual
kind) for enterprise‑architectures and the like. Most of my consultancy work tends not to be in developing
an enterprise‑architecture as such, but in helping internal teams develop their own enterprise‑architectures

- hence I work in practice‑refresh, in helping a team lift themselves to the next level of
architecture‑maturity, and so on. Hence also describing all of that in books, in blog‑posts, in
conference‑presentations – though if you want something custom‑built for your own specific context, you’d
more likely come to me direct. I deliberately don’t have much predefined‑product to “sell”, because so much
of what I do needs to be custom‑created for each specific context – though that again often makes it hard
to say exactly what it is that I do. And, yes, occasionally someone pays for doing this: and I’ll have to admit
that that is good when that happens – if only because it tells me that they do value my work, in a monetary
sense at least. Getting paid does help to keep me going in the game, of course: **yet it isn’t why I’m in this
game**.

And that’s the simplest summary, really: the enterprise that I work in is **enterprise‑architecture** ; **I’m
always working; and occasionally someone pays me**. It’s not complicated, not “clever”, it’s just what it is:
nothing more than that. If you need to know my business‑model, that’s it. Enough said. So what’s your
own business‑model, then? Why do you do what you do?

AI and skills – Helping organisations become more effective, adaptable and able to manage uncertainty.
https://tetradian.com/ai-and-skills/

EA and the Content Economy – Helping organisations become more effective, adaptable and able to
manage uncertainty.
https://tetradian.com/ea-and-the-content-economy/

Business-architecture frameworks – Helping organisations become more effective,
adaptable and able to manage uncertainty.
https://tetradian.com/business-architecture-frameworks/

Why business-model to enterprise-architecture? – Helping organisations
become more effective, adaptable and able to manage uncertainty.
https://tetradian.com/why-business-model-to-enterprise-architecture/

What’s my own business-model? – Helping organisations
become more effective, adaptable and able to manage uncertainty.
https://tetradian.com/whats-my-own-business-model/

