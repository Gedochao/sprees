# Open Source Spree

The focus of Scala Sprees is to introduce newcomers and veterans alike to open
source! Come meet contributors of well-known open source Scala projects and
learn how you can make your own contribution.

**Your challenge?** Get one pull request merged into one of the projects, and
get this awesome t-shirt:
![](https://pbs.twimg.com/media/CtnCrtvWAAAO0nE.jpg:small)

[![Join the chat at https://gitter.im/scalacenter/sprees](https://badges.gitter.im/scalacenter/sprees.svg)](https://gitter.im/scalacenter/sprees?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Warsaw, Poland. Wednesday, 7th of December 2022

|                    |                                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| Time               | Wednesday, 7th of December 2022, 17:00                                                          |
| Location           | [Giełdowa 1, Warsaw](https://goo.gl/maps/pvyqLmdCpMpLAbWA9) ([Synerise](https://synerise.com/)) |
| Event Registration | [Meetups](https://www.meetup.com/scalawaw/events/289954415/)                                    |
| Food               | Pizza and drinks                                                                                |
| Bring              | Laptop + Power Cord                                                                             |

### Detailed Schedule

|                  |       |
|------------------|-------|
| Start Time       | 17:00 |
| End Time, Drinks | 22:00 |

### Projects (**Maintainers: Please add your project here!**)

Here is a list of projects that you could contribute to during the spree:

| Project                                                                              | Contact                                                              |
|--------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| [TASTy Query][TASTy Query] – a library for semantic analysis of Scala programs       | [@bishabosha][@bishabosha]                                           |
| [Scaladex][Scaladex] — a Scala libraries search engine                               | [@adpi2][@adpi2]                                                     |
| [Scala Debugger in Metals][Scala Debugger in Metals] — a debugger for Scala programs | [@adpi2][@adpi2]                                                     |
| [Scala CLI][Scala CLI] —  a command-line tool to interact with the Scala language    | [@lwronski][@lwronski], [@Gedochao][@Gedochao], [@wleczny][@wleczny] |
| [Metals][Metals] — Scala LSP server                                                  | [@tgodzik][@tgodzik]                                                 |
| [Mdoc][Mdoc] — Typechecked markdown documentation for Scala                          | [@tgodzik][@tgodzik]                                                 |
| [Scalameta][Scalameta] — Scala parser and semanticdb generation                      | [@tgodzik][@tgodzik]                                                 |
| [sttp][sttp] — The Scala HTTP client that you always wanted!                         | [@Pask423][@Pask423]                                                 |
| [kebs][kebs] — a Scala library to eliminate boilerplate                              | [@luksow][@luksow]                                                   |
| [magnolia][magnolia] — fast and friendly typeclass derivation for Scala              | [@micsza][@micsza]                                                   |
| Add your project here!                                                               |                                                                      |

Who will be leading the Scala Open Source Spree?

- Anatolii Kmetiuk, [@anatoliykmetyuk][@anatoliykmetyuk] (Scala Center)

Want to add your project to the list? Jump to the next section!

## Duration, pace steps

At the beginning, maintainers gather together in front of all the contributors
to briefly explain their projects and tickets in one minute. The idea is to give
a good high-level explanation to motivate participants without going into too
much detail. A link to this page is provided.

When they are done, participants approach the projects they are most interested
in and get it contact with the maintainers. At this point, maintainers usually
listen to the participants' experience and provide personal guidance on tickets
that would suit them.

Then, the fun begins! Participants start hacking on their projects and
maintainers review PRs as they come, assisting participants when they ask for
help. We encourage maintainers to merge as many PRs as possible in the place,
for two reasons:

1. Participants get a small token of appreciation from the Scala Center.
2. It increases the motivation of the participants.

If participants get the first PR merged, they are invited to continue solving
issues until they are happy with their work!

At the middle of the spree, the Scala Center and sponsors of the event provide
maintainers and participants alike with some refreshment (drinks, sandwiches,
pizza, etc).

Participants can leave the event at any time they want. When the time approaches
the end, everyone starts to wrap up: participants finish their PRs while
maintainers finish their review, and organizers of the spree give away Scala
t-shirts. We finish by thanking your hard work for open-source.

## For Maintainers:

### How to propose a project

A Scala Center spree is the perfect event to gauge interest in your open-source
projects. You not only have the opportunity to get new contributors involved in
your project, but you can win friends and lifetime maintainers that help you
make a difference in the open-source world.

There is only one requirement to submit a project -- you need to be present for
the duration of the Scala Center spree. Your physical presence is important to
assist and motivate contributors.

If you are a maintainer of an open-source Scala project, make a PR to add your
project to the list!

### What you need to do

Create a PR with the following information:

- Project information.
- Your contact details.
- A link to a "spree" or "hackathon" label with curated tickets for the
  participants. See
  [this project](https://github.com/sbt/zinc/issues?utf8=✓&q=label:hackathon%20is:issue)
  for inspiration.

It's important that the curated tickets are entry-level, typical issues that you
would solve in 15-20 minutes of your time as an experienced maintainer. In our
experience, newcomers will take 1 to 2 hours to address them, assuming they are
unfamiliar with the codebase and this is their first contribution.

### How to be an effective maintainer

Maintainers can make a difference by tweaking some knobs:

- Provide a `CONTRIBUTING` guide. Contributing guides explain to newcomers the
  usual workflow to get started and what's expected from them. Good guides:
  [scala/scala](https://github.com/scala/scala/blob/2.12.x/CONTRIBUTING.md),
  [sbt/zinc](https://github.com/sbt/zinc/blob/1.x/CONTRIBUTING.md),
  [scalameta/scalameta](https://github.com/scalameta/scalameta/blob/master/CONTRIBUTING.md),
  [scalacenter/scalafix](https://github.com/scala/scala/blob/2.12.x/CONTRIBUTING.md).
- Provide a motivating `README` with clear instructions. Make sure docs are up
  to date.
- Link to documentation when possible, or show contributors how to search for
  docs. You can label as `docs` any issue or PR with relevant discussions to get
  acquainted with implementation details and design decisions.
- [Be nice to newcomers](http://brson.github.io/2017/04/05/minimally-nice-maintainer),
  they will always remember it!

### How to write good tickets

Curating tickets is not easy. If you want to optimize for the highest number of
contributors, we recommend you to:

- Give hints on potential solutions. Say which solutions are not on the table,
  if any.
- Describe the purpose of the ticket and its context. Having a clear idea of why
  your ticket is relevant will motivate participants.
- Add links to source code sparingly. Show the entry-points for the requested
  functionality / fix, give a basic explanation of the code structure.
- Be concise and detail specifics of your project or its implementation.
  Providing this kind of domain knowledge to participants will help them finish
  off their tickets sooner, and move to the next one!

[@adpi2]: https://github.com/adpi2
[@bishabosha]: https://github.com/bishabosha
[@julienrf]: https://github.com/julienrf
[@markehammons]: https://github.com/markehammons
[@sjrd]: https://github.com/sjrd
[@SethTisue]: https://github.com/SethTisue
[@luksow]: https://github.com/luksow
[@Pask423]: https://github.com/Pask423
[@tgodzik]: https://github.com/tgodzik
[@micsza]: https://github.com/micsza
[Scala 2]: https://github.com/scala/bug/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[Scala 3]: https://github.com/lampepfl/dotty/issues?q=is%3Aopen+label%3ASpree+sort%3Aupdated-desc
[scala-collection-compat]: https://github.com/scala/scala-collection-compat/labels/good%20first%20issue
[TASTy Query]: https://github.com/scalacenter/tasty-query/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[Scaladex]: https://github.com/scalacenter/scaladex/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[Scala Debugger in Metals]: https://github.com/scalacenter/scala-debug-adapter/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[Scala CLI]: https://github.com/VirtusLab/scala-cli/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[sttp]: https://github.com/softwaremill/sttp/issues?q=is%3Aissue+is%3Aopen+label%3Aspree-warsaw
[magnolia]: https://github.com/softwaremill/magnolia/issues?q=is%3Aissue+is%3Aopen+label%3Awarsaw-spree
[Slinc]: https://github.com/markehammons/slinc/issues
[Scala Website]: https://github.com/scala/docs.scala-lang
[sbt-version-policy]: https://github.com/scalacenter/sbt-version-policy
[kebs]: https://github.com/theiterators/kebs
[@anatoliykmetyuk]: https://github.com/anatoliykmetyuk
[Metals]: https://github.com/scalameta/metals/issues?q=is%3Aopen+is%3Aissue+label%3Aspree
[Mdoc]: https://github.com/scalameta/mdoc/issues?q=is%3Aissue+is%3Aopen+label%3Aspree
[Scalameta]: https://github.com/scalameta/scalameta/issues?q=is%3Aopen+is%3Aissue+label%3Aspree
[@lwronski]: https://github.com/lwronski
[@Gedochao]: https://github.com/Gedochao
[@wleczny]: https://github.com/wleczny
