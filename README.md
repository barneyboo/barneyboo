### well hello.

I'm a senior developer in BBC News Labs, based in London. I've been working on experimental audience-facing formats, and tools to make life better for our journalists since 2017. It's pretty fun! I also make games and experiments with Unreal Engine.

### what am i working on now?

### 🌍 Frank: highlighting language service journalism that can travel well

The problems with helping short-form language travel well across the BBC (Live Page Translation, below) also apply to longer articles. It's further complicated as language services will often translate and reversion stories from centralised English language teams, or other services, but it's hard to tell when this has happened, or how well those stories performed. I'm acting as tech lead on a project to analyse all language service content as it's published and identify if it's likely to be a story that will travel well, and isn't a story that's already been translated. We can then machine translate and automatically promote it to World Service journalists to help them reversion it for their own audiences. More on this one soon...

### what have i done before?

I've been lucky to work on loads of really interesting and high impact projects in News Labs. All of these have been huge team efforts, both within Labs and across the BBC, so here's some examples of what I've been able to contribute...

#### 💘 Cupid (Curated/Personalised) - editorial curation meets personalisation

Recommender systems are commonly used for personalisation, to help suggest relevant content for audiences. However, in news, curation is important - to make sure audiences get a good mix of content and a particular mix of content doesn't unintentionally introduce bias or get in the way of other editorial sensitivities. With Cupid, we've been building a values-led approach, where editors curate experiences for different audience once, based on the news values they should contain - and the right content is populated at runtime. We've just started evaluating our [first prototype of this idea](https://bbcnewslabs.co.uk/projects/cupid/).

#### 🌲 Evergreen Content

Building on our work with Depth Finder (below), we've started investigating ways of helping our editorial teams quickly identify appropriate evergreen content to recommend to audiences as soon as a new story breaks or trends. I've helped build [new functionality in Depth Finder](https://bbcnewslabs.co.uk/projects/evergreen-content/) to achieve this, and we're now trialing a Slackbot that recommends trending articles that may have out of date content with World Service Languages.

#### 🌍 Live Page Translation - making language services' journalism travel further

The BBC has dozens of international language services that produce great journalism for audiences around the world, including several underserved languages. Original journalism from these services could often benefit a wider audience, but stories often don't travel well between services because of a lack of visibility to other parts of the organisation, and of course, language barriers.

We've built a dashboard that aggregates stories in real time from any number of services, and optionally only for particular topics, and automatically translates them into the language of a user's choice. Now our journalists can follow breaking stories, and quickly reversion the content for their own audience, reducing duplication of effort within the BBC and better serving our international audiences.

#### 🦸🏼‍♂️ Graphical Storytelling - high impact stories for underserved audiences

We're building a new format for building visually compelling health stories for social platforms, without needing to be a designer.

Last year, [we wrote](https://bbcnewslabs.co.uk/news/2020/graphical-storytelling/) about some of our initial experiments with generating visual panels with nothing more than natural text written by a journalist. And this year, with health stories being more important than ever, we're working on getting this into production. I've been tech lead for our latest 6 week investigation, building the journalist-facing tooling, and renderers for the stories themselves. I'll have more to share on how these stories are looking soon...

#### ❓ Explainer Builder - making complex stories accessible

Whether it's elections or coronavirus, a lot of stories are complicated, fast-changing, and can expect a lot of background knowledge from audiences. We've created the Explainer Builder to let journalists easily create and maintain Q&As for the BBC News website. We've created BBC-wide knowledge bases around certain topics that journalists can update and use to create embeddable explainers, with the option of answering questions as they're typed by audiences. In our first tests, the impact of this format was huge, and in [March I spoke to journalism.co.uk](https://www.journalism.co.uk/news/bbc-news-experiments-with-explainer-feature-to-help-readers-make-sense-of-complex-stories/s2/a753374/) about our motivation for the format.

#### 🗳 SALCO - semi-automated stories for NHS performance and elections

Lots of news stories are driven by data, and for the last couple of years we've been looking at using public data to generate stories we otherwise couldn't, starting with hyperlocal stories about A&E performance in your local NHS trust. For the 2019 general election, we gave the tech our most ambitious outing yet - generating stories in English for each of the UK's 650 constituencies as they were declared, and another 40 in Welsh. I've been responsible for building some of the journalist-facing tooling and data processing pipelines for these initial pilots.

#### 🌊 Depth Finder - surfacing the best of the BBC's evergreen content

The BBC produces lots of high impact analysis, explainers, and in-depth long-reads. These stories often have a better shelf life than on-the-day journalism, so we want to make sure we can get the best value from these stories by getting them in front of audiences who want to read them. [Depth Finder](https://bbcnewslabs.co.uk/projects/depthfinder/) is a search engine specifically for such content. Now our journalists can instantly see whether there's a relevant piece on any topic, in any language, so they can easily include them as onward journeys in their own work, to make this content go further. I designed and built the frontend for Depth Finder, and since its introduction its queryable elasticsearch archive of BBC News stories has gone on to power several other prototypes and experiments.

#### 💬 Crossing Divides - helping create better conversations

For the BBC World Service's Crossing Divides season, we built an interactive storytelling format, to help audiences navigate difficult conversations from two different perspectives. The result is a challenging set of stories, which was shortlisted for the Association of International Broadcasting’s Innovation Award in 2018.

#### 🐙 Octo - quick transcripts from BBC media

Journalists often need quick transcription of their content - whether it's the recording of a long interview, or a finished package to put together subtitles. Octo pulls together a bunch of existing integrations with our audio and video content systems, and our internal speech-to-text services, to offer a consistent way of getting transcripts from any BBC media. One of my first projects in News Labs, I built Octo's React frontend.

### other open source projects

I maintain a few forks of open source projects, usually with small feature updates/fixes:

**[@barneyboo/VlcMedia](http://github.com/barneyboo/VlcMedia)** - Unreal Engine 4 plugin for streaming media via libVLC. This fork adds support for volume control.

**[@barneyboo/react-autosuggest](https://github.com/barneyboo/react-autosuggest)** - React component that provides autosuggest behaviour. This fork adds support for tabbing on a suggestion to act as confirmation of a selection.
