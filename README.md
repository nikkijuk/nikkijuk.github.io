# Experiments worth sharing

Very opinionated slidesets and presentation. 

Slides were made for presenting ideas in context of current project and company, which is not generic enough to make them something you should think in terms of "right" or "wrong". Some ideas might apply to other contexts also, but you should manage to estimate tradeoffs by yourself to decide if they have value to you. 

Not all of slidesets are finished. They might still be worth browsing, for which reason they are shared.

Why bother to think, iterate your ideas, ask constantly "why?". Isn't it enough to just write next line of code? Read [Uwe Friedrichsen, Essential Architectural Thinking](https://speakerdeck.com/ufried/essential-architectural-thinking)

## About me

[slides](https://nikkijuk.github.io/about/)

I have programmed for a long time. It's still fun and I enjoy it.

Currently I'm in mid way to understand that the whole power of what I have done is not a skill of decoding commands to computer. 
It's all on persons, interaction, within team, with customers. I'm curious to understand more of it.

To understand where I am and why I am I tend to think organisations and environments where I have worked.
All of those environments have influenced me, but currently I'm more aware about what they do to me.
I am one of the global few persons who doesn't need to work for money, but I still see how 
[the Way We Think about Work is Broken - Barry Schwartz](https://www.youtube.com/watch?v=DKl-C-VMqYA)

"(..) what Adam Smith was telling us there is
that the very shape of the institution,
within which people work, creates people
who are fitted to the demands of that
institution, and deprives people of the
opportunity to derive the kinds of
satisfactions from their work that we
take for granted" - Barry Schwartz

I'm motivated by search of understanding boundaries and possibilities, 
what I can professionally offer to others and what I need.
Curiousity has lead me to wonder
[how to activate the ‘seeking system’ of your brain - Dan Cable](https://www.youtube.com/watch?v=E4yVofxXpT0)

"what's interesting is if you start with humanity, and you start with 
"you're a person, 
there are probably things about you that are unique,
that we should know about".
Why don't we start by socializing
some of the ways that were unique, and that we add value to the team. 
And I think by humanizing that relationship, it's so simple, 
but it actually stands out as being rare." - Dan Cable

Mindsets are important. 
Developing Growth mindset can be learned.
Enjoy [the power of 'yet' with Zoe and Elmo from Sesame Street](https://www.youtube.com/watch?v=46UhAtPyXw4)

"Making mistakes and coming up with solutions
to solve your problems is exercise for your brain. 
Whoa! It's brainercize!
Right! When you believe you can do it and you keep trying,
that's when your brain is growing and you're learning
new things." - Sesame Street

I wrote these slides to reflect what I have done, how I see my role, and my strengths.
It's all random, but tasks like this direct thinking. 

## Generating code 2.0 - Specification Driven Development (SDD)

[slides](https://nikkijuk.github.io/codegen/)

Code generation is not new. It's old idea that has been used in different forms over decades.
In early days code generation was used to generate code from models (model driven development).
Later DSLs (domain specific languages) were used to generate code.
MDD and DSL are deterministic approaches for generating code.
From same inputs, using same generator, same code is generated.
MDD uses graphical or textual models to generate code.
DSL uses textual models to generate code.

SDD (specification driven development) is non-deterministic approach for generating code.
It uses large language models (LLM) to generate code from specifications.
From same inputs, using same LLM, different code can be generated.
Just like when humans write code based on same specifications,
different developers can write different code.

Using LLM for generating code is flexible approach.
You can give it just prompt (instructions) and LLM will generate code based on its knowledge.
It's like writing code by yourself, but you have assistant who helps you.
You can guide assistant by giving more detailed instructions,
providing context, setting constraints, and defining architecture.

SDD allows developer to use AI agents like army of minions 
to automate different parts of development process.
AI agents can test, document, refactor, and deploy code.
They can do research, create generation plans, break plan down to tasks, 
coordinate tasks, and integrate code.
This allows developer to focus on high-level design and architecture,
while AI agents handle low-level details.

SDD is like having a team of developers who work together to create code.
It's not magic, it's just tool that helps you to write code faster,
but like real code writing, it requires skill and practice to use it effectively,
and results can vary depending on the quality of the inputs and the capabilities of the LLM,
used toolset, agent orchestration as well as your skill to guide it.

GIGO (garbage in, garbage out) applies to all code generation approaches.
If inputs are poor quality, generated code will be poor quality.
If inputs are high quality, generated code will be of better quality,
but as SDD is non-deterministic approach, results can still vary,
and hallucinations are possible.

## Revisiting Flutter, Bloc and immutable data for UIs

[slides](https://nikkijuk.github.io/flutterbloc/)

MVC pattern was developed at Xerox during late 70s. 
It took quite some time before idea reached rest of us
when web rammed down idea of desktop applications at late 90s.
Reactive programming is a variant of MVC 
for modern times, and it's power really struck me with Flutter
and immutable data.

I have collected my notes and thoughts here, 
since reactive programming and immutable data
may also impress you as it did for me.
Resulting clean programming model 
is a delight to work with.
For experienced developers letting
ideas of imperative ui 
and mutable global state
to die might feel like losing old friend,
but it's worth of sacrifice.

Bloc has evolved over time from pattern to [small focused library](https://bloclibrary.dev/). 
Library's api has changed lightly over the course of development, 
but basic construct follows still ideas [introduced 2018](https://youtu.be/PLHln7wHgPE?t=1377).
If you'd like to have more information here's [deep dive from Felix Angelov](https://www.youtube.com/watch?v=knMvKPKBzGE).

## Career changes

World changes while you work. Your work changes also. 
My career started as operator trainee for minicomputers.
You see those computers in museums novadays. 

[slides](https://nikkijuk.github.io/career/)

Currently we are in the middle of AI hype. 
Together with changes that internet has driven since 2000s we see that all that can be automated will be automated.
Some algorithms that will influence us in future work well, some not.
All biases in current world will be seen on data that AI uses.

These slides were prepared for 10th-grade students as the teacher asked me to present what 
I have done during my 30+ years career as a software developer. 
I tried to illustrate how radically IT has changed over last decades, 
and how we work on IT has also changed. 
If anything I hope they got an idea that new things are not especially new, 
and that lot of things are about to change after they're about to graduate 
and start working.

## Scrum basics

[slides](https://nikkijuk.github.io/scrumbasics/)

"agile, adjective - able to move quickly and easily" - Oxford Dictionary

Agile isn't "done" by following Scrum. Scrum is just a tool to help you to communicate.
If you don't understand why you are doing Scrum, maybe you should not do it.
Or: you can try to understand it better.

This is my take on Scrum basics. 
It's written for non-professional purpose to help a group of young people to start up the project, 
and is partially in German, but it might be useful for you also.

But if you want to learn, then, where to start? See [A S C R U M B O O K](https://scrumbook.org/), 
it's free to browse online.

All golden? No, see ["Agile Methods The Good, the Hype and the Ugly," Bertrand Meyer](https://www.youtube.com/watch?v=ffkIQrq-m34) 
or read his book.

But you might also want to see [Scrum Guide](https://scrumguides.org/) as it's "the" official source of Scrum. 
Don't expect too much clarity from Scrum Guide, it's short and intentionally 
open to different interpretations and perspectives.

Whatever you do; remember, many projects fail. 
This happens regularly regardless of the methodology followed. 
Is Agile better? Is Scrum better? 
Maybe, but it's not a secure way to success.

Pay close attention to feelings of people working on the project,
if they believe in what they do, if they respect each other, if they are happy.
It's not Scrum that does the work, it's your team, or: you and me and whoever we are working with.
It's not sticking to rules; it's understanding why we are doing what we are doing.

## Brainhacks: How to enhance human potential usage for software development?

[slides](https://nikkijuk.github.io/brainhacks/)

Themes

- Your team is not performing? Maybe it's not team at all.
- Where did happy go? and where comes motivation.
- Trust is the key. But how to build it?
- It's not just bricks. We build cathedrals.
- Happiness is on your relationships to others.

That's not technical stuff, but how to enable people to work together better.
Sure it's also about money and profitabilty, as
[Teresa Amabile - The Progress Principle - ](https://www.youtube.com/watch?v=XD6N8bsjOEE&t=935s) states that
"dissatisfaction leads to slower revenue growth and lower profitability, 
in other words,  employee engagement drives the bottom line".

Important to you is also [Does your job match your personality?](https://www.youtube.com/watch?v=WEvqMN75sCI),
which [Jordan Peterson](https://bigthink.com/videos/how-important-is-it-that-your-job-matches-your-personality-extremely/)
comments
“If you’re a creative person who is open to trying new things 
— openness being one of the Big Five personality traits 
— you’re more likely to succeed at jobs that require novel solutions over efficient ones. 
On the other hand, if you’re conscientious 
— another Big Five personality trait 
— you’re likely to be better off in a management or administrative position.”

There's good reason to solve conflict between
software developers and managers,
or said otherwise: between creative - open - and administrative - conscientious - persons / roles..

As [Jordan Peterson](https://bigthink.com/videos/how-important-is-it-that-your-job-matches-your-personality-extremely/)
observes
“So there’s this terrible tension in organizations, 
and I think what generally happens is all the creative people are there at the beginning. 
They get chased out until you have nothing but managers and administrators. 
Then the environment shifts, then the company dies. 
And so the way that capitalism solves the problem of the tension between the creative types 
and the managerial types is it just lets companies die.
Now you might think, “Well I don’t want my company to die.” 
It’s like okay then, you need to understand the difference between these two kinds of people
— which you probably won’t and you probably won’t admit to even if you knew. 
And then you have to figure out how to get the balance right. 
And so that’s extraordinarily complicated.”

## Backing Mobile: what can cloud do for mobile?

[slides](https://nikkijuk.github.io/backingmobile/)

You need backend for mobile? Here discussion notes for my collegues.

## Going Mobile: native, web, pwa, hybrid, crossplaform, whatever, .. 

[slides](https://nikkijuk.github.io/goingmobile/)

This is mostly sales for Flutter. It's partly outdated, partly still valid.

Flutter and Dart form ecosystem which looks to me first really promising way to build hybrid mobile apps.
Dart is flexible, easy to learn and develops constantly.It's modern, null safe and has good tooling.
Flutter is starting to be mature, and migrations between versions are not too painful.
It is possible to develop Android and iOS apps with same codebase, and other 
platforms like linux, windows, osx and web are also supported.

Flutter is cool, so maybe I'll update this someday. Not it's quick snapshot from 2022. 

## Contract: open api specification or full hateoas? modelling or coding?

[slides](https://nikkijuk.github.io/stablecontracts/)

api driven: while model driven development (DSLs) and generating code reduces errors.

code first: while it looks easy and there's fancy examples at stack overflow.

Decision lies on your culture, usecase and legacy codebase. I have very strong opinion that modelling and sharing contracts openly would be valuable, but also that it's rare capability, which many companies might not have. 

Related, and important, [Uwe Friedrichsen, Getting API design right, slides](https://speakerdeck.com/ufried/getting-api-design-right) and [video, in German](https://www.youtube.com/watch?v=2xgplCQS1bY&t=1161s)

## Software evolution: when learnings come code

[slides](https://nikkijuk.github.io/infinitecode/)

If team is managing to embed to software everything they learn by observing how users are using system, it evolves. If team is not learning or not capable of changing their system according their growing knowledge, it suffers, and is in danger.

If gap between what is known of users needs and what software provides grows 
it's only a matter of time when users 
dissatisfaction forces them to abandon software they hoped to provide value.

Related, and important, [Einar Høst, Technical debt isn't technical, slides](https://www.slideshare.net/einarwh/technical-debt-isnt-technical-pdf-ndc-oslo-2018) and [video](https://www.youtube.com/watch?v=CXyNZYDO07Q)

## distributed program flow

[slides](http://nikkijuk.github.io/flowcode/)

what is microservices architecture?
what kind of coordination is required when local data and local computation needs to work in context of distributed systems.

## Becoming Software Developer

[slides](https://nikkijuk.github.io/becomingdeveloper/)

or [Kevlin Henney's "It Depends."](https://www.youtube.com/watch?v=rNSVZs66o48)

since it's not important how you learn to learn, but that you understand that it's process.

## Software Development Laws

[slides](https://nikkijuk.github.io/softwarelaws/)

or [Kevlin Henney's "Old is The New New"](https://www.youtube.com/watch?v=AbgsfeGvg3E)

## Why Kotlin?

[slides](https://nikkijuk.github.io/whykotlin/)

This discussion is about Kotlin in backend. Solely. 

Kotlin seems to be promise that comes reality so slow that Java takes over.
But is it really so?

Hmm.. Think again. Null safety is important and 
Kotlin is safer than Java even if java is getting better.
Additionally, Kotlin is more concise and expressive than Java,
making it easier to read and write.
Extension functions and operator overloading are also nice features
which makes it easier to write clean and readable code, 
especially for domain specific languages.

## Scrum patterns

[slides](https://nikkijuk.github.io/scrumpatterns/)

## Cosmos db experiment

[slides](https://nikkijuk.github.io/cosmosdb/)

[code](https://github.com/nikkijuk/cosmosdb-springboot-kotlin-sample)
