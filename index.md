---
layout: single
title: 'Portfolio'
author_profile: true
toc: true
toc_label: 'Contents'
toc_sticky: true
---
## `$ bash portfolio.sh about`

I'm Marcin, a computer science enthusiast from Poland. This is my web portfolio.

<i class="fas fa-user-astronaut"></i>
Professionally I aim to create clean code with transparent architecture and applied best practices,
e.g. the functional paradigm, design patterns.

<i class="fas fa-code"></i>
My programming knowledge originates from the **C++** language. That said, I enjoy learning any interesting or useful tools.
Among my most preferred ones are **Rust**, **Python**, **Haskell**.

<i class="fas fa-gamepad"></i>
In my leisure time I play video games, mostly indie.
These include [Dead Cells](https://dead-cells.com/), [Slay the Spire](https://www.megacrit.com/),
[CrossCode](http://www.cross-code.com/en/home), [Terraria](http://terraria.org/) and many others.

<i class="fas fa-music"></i>
Also music! I listen to many genres, for example see my
[<i class="fab fa-spotify"></i> sovietwave playlist](https://open.spotify.com/playlist/4VeiwlzZcdkjeimX6fd5CS?si=eKGrlopwRfyJOY8xyOHdnw).

## `$ bash portfolio.sh aoc`

A special mention, [advent of code](https://adventofcode.com/) is a programming event happening each year in the Christmas season.

For me it's an opportunity to challenge myself, learn new languages or techniques etc.
Check out my [<i class="fab fa-github"></i> repo](https://github.com/tranzystorek-io/aoc2019) with solutions to the 2019 edition.

## `$ bash portfolio.sh projects`

These selected entries highlight various fields of my experience.

### <i class="icon-cplusplus"></i> [pinfs](https://gitlab.com/Tranzystorek/pinfs)

A simplified distributed filesystem.

Files are spread across a small P2P network using a [DHT table](https://en.wikipedia.org/wiki/Distributed_hash_table),
specifically the Kademlia implementation.

### <i class="icon-cplusplus"></i> [langust](https://gitlab.com/Tranzystorek/langust)

A small Python-esque language for operating on lists, along with an interpreter.

Its sample feature - `map` and `filter` operators that apply functions to lists:

```console
$ l = [0, 1, 2, 3];
[ 0, 1, 2, 3 ]

$ l >: func(el) {return el+1;};
[ 1, 2, 3, 4 ]

$ l >? func(el) {return el < 2;};
[ 0, 1 ]
```

My first ever attempt at creating a whole programming language.
Its syntax has been designed from scratch, including an LL parser.

### <i class="icon-rust"></i> [untangle](https://github.com/tranzystorek-io/untangle)

A solver for the [Strata](https://store.steampowered.com/app/286380/Strata/) puzzle game.

The solver itself is dead-simple; this project aims to stand apart when it comes to
the design of an application: separated **CLI interface <-> library** architecture,
reusing code from libraries, informative error handling etc.

It also shows off some clean and slick Rust :smile:

### <i class="icon-rust"></i> [hexers](https://github.com/tranzystorek-io/hexers)

A very small Rust library for converting byte sequences into hex-encoded character sequences.

The central piece here is understanding and implementing Rust's
[Iterator](https://doc.rust-lang.org/std/iter/trait.Iterator.html)-oriented data processing.

## `$ bash portfolio.sh tech`

People are poorly defined by lengthy lists, but have a read anyway.

### Environments

* <i class="fab fa-linux"></i> Linux
* <i class="icon-shell"></i> bash, zsh

### Languages

* <i class="icon-cplusplus"></i> C/C++ (mostly the latter)
* <i class="icon-rust"></i> Rust
* <i class="icon-python"></i> Python (scripting)
* <i class="icon-java-bold"></i> Java SE (basics)
* <i class="icon-haskell"></i> Various FP fundamentals (Haskell, Scala, Elixir)

### Frameworks and libraries

* Protobuf
* Qt (basics)
* Flask (very simple web applications)

### Tools

* <i class="icon-git"></i> Git
* <i class="fab fa-github"></i> GitHub (managing projects, submitting pull requests)
* Gerrit (as a user)
* <i class="fab fa-jenkins"></i> Jenkins (as a user)
* Conan (C++ package management)
* CMake
* LaTex

### Unit testing

* GTest/GMock
* Catch2
* JUnit / TestNg
