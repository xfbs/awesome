# Awesome

My own curated list of awesome things.

## Table of Contents

- [News](#news)
- [Blogs](#blogs)
- [Puzzles](#puzzles)
- [Programming Languages](#programming-languages)
- [Tools](#tools)
    - [Terminal](#terminal)
    - [Editors](#editors)
    - [Version Control](#version-control)
    - [Static Analysis](#static-analysis)
    - [Code Formatter](#code-formatter)
    - [Code Sanitizers](#code-sanitizers)
    - [Debuggers](#debuggers)
- [Libraries](#libraries)
    - [C Libraries](#c-libraries)
    - [C++ Libraries](#c-libraries-1)
- [Reading](#reading)
    - [Books](#books)
    - [Papers](#papers)
- [Further](#further)

## News

As François put it:

>   “Tell me what you read and I'll tell you who you are" is true enough, but
>   I'd know you better if you told me what you reread.”

These are news sites worth reading and hopefully re-reading, about technology
and related topics.

> *A technology-focused community centered around link aggregation and discussion*.
> All links are user-submitted, small friendly community, invite-only and ad free.

- [Lobsters](https://lobste.rs/), ★★★★★

> *A social news website focusing on computer science and entrepreneurship*. Run by
> startup fund Y Combinator. User-submitten link aggregator, bigger community,
> less personal but also ad-free.

- [Hacker News](https://news.ycombinator.com), ★★★★☆

> *Independent news and views for the tech community*. Based in London, UK.
> Does some really good dry humor, as you would expect.

- [The Register](http://www.theregister.co.uk), ★★★★☆

> News, guides, reviews, and features.

- [Ars Technica](https://arstechnica.com/), ★★★★☆

> *A community for sharing thoughtful information and conversation*. 
> Similar to [lobste.rs](https://lobste.rs/), but focussed on science in general.

- [Hubski](http://hubski.com), ★★★★☆

> Generic tech news

- [The Verge](https://www.theverge.com), ★★★☆☆

> News from silicon valley

- [Recode](https://www.recode.net), ★★★☆☆

## Blogs

A few technology/culture centric blogs woth checking out.

> *Law, technology, and the space between*.

- [`/dev/lawyer`](https://writing.kemitchell.com)

> Regular writings involving Rust, Ruby and how to take things like syscalls
> apart.

- [Julia Evans](https://jvns.ca)

## Puzzles

> *A series of challenging mathematical/computer programming problems
> that will require more than just mathematical insights to solve.
> Provides a platform for the inquiring mind to delve into unfamiliar
> areas and learn new concepts in a fun and recreational context*.
> Great place for beginners and more advanced people alike, whether
> you are interested in learning or improving your programming skills
> or in mathematics.

- [Project Euler](https://projecteuler.net/), ★★★★★☆☆☆☆☆

> *This is a different way to learn about crypto than taking a class
> or reading a book. We give you problems to solve. They're derived
> from weaknesses in real-world systems and modern cryptographic
> constructions. We give you enough info to learn about the underlying
> crypto concepts yourself. When you're finished, you'll not only have
> learned a good deal about how cryptosystems are built, but you'll also
> understand how they're attacked*.
> Great place for some hands-on experience with cryptography, the
> challenges aren't too difficult but they provide a good understanding
> of the theory behind some of the crypto we use.

- [matasano](http://cryptopals.com)

> *Some problems related to computer security (specifically poorly
> implemented security). You are free to use any language
> and environment you like to complete them. The problems require
> familiarity with programming, but not necessarily with applied
> cryptography or computer security in general*.

- [id0-rsa](https://id0-rsa.pub)

>   Commercial puzzle websites

- [HackerRank](https://www.hackerrank.com)
- [LeetCode](https://leetcode.com)
- [CodeChef](https://www.codechef.com)

## Programming Languages

Which programming languages do I find cool? Which programming languages do I
find useful? Which programming languages would I recommend to a friend to learn?

>   Not exactly the next big thing anymore, but still my go-to programming
>   language for it's sweet syntax. Interpreted, dynamically-typed. Bonus:
>   amazing package manager *rubygems*.

  - [Ruby](https://www.ruby-lang.org)

>   Statically-typed, compiled Ruby lookalike, with a speed comparable to C
>   thanks to it's LLVM backbone. Bonus: has a package manager, *shard*.

  - [Crystal](https://crystal-lang.org/)

>   It just won't ever die. The grandfather of programming languages, a
>   necessary evil but also an addictive one. With a modern compiler and when
>   using the new C11 standard it's a little better.

  - [C](https://en.wikipedia.org/wiki/C_(programming_language))

>   Statically typed, memory-safe compiled language rivalling some of C's
>   territory. Notoriously mean compiler, but fast iterations and an awesome
>   integrated package manager, *cargo* make the programmer happy.

  - [Rust](https://rust-lang.org)

>   What can I say? Everybody's Favourite Language (tm).

  - [Python](https://python.org)

<!--
  - [chez scheme](https://github.com/cisco/ChezScheme), because I never really
    worked with a scheme before and it's reportedly very fast. **Edit**: I might
    use a different flavour of Scheme, [chicken scheme](http://call-cc.org),
    because it seems a little more simplistic and doesn't have the overhead of
    an interpreter since it's compiled (although, it might be slower than
    `chez`).
  - [ocaml](https://github.com/ocaml/ocaml) because I keep hearing about it in
    unexpected places and it got me curious.
  - [nodejs](https://github.com/nodejs/node) because all the cool kids are doing
    it and my javascript is quite rusty.
  - [java9](https://www.oracle.com/java/java9.html) because that's what most
    people worldwide speak and while I'm really not a fan of java, they did add
    some features that make it interesting.
  - [haskell](https://www.haskell.org), because it's just been on my to do list
    for too long.
  - [risc5asm](https://rv8.io), because well you need to have done some assembly
    to be able to call yourself a 'real' programmer, and x86 assembler is too
    ordinaire for me and MIPS stopped being interesting 20 years ago.
  - [cpp](http://clang.org), because I haven't really gotten around to playing
    with C++14 and it could be okay.
  - [swift](https://github.com/apple/swift), because it's seems cool even though
    it's from a major company and not some academic tech hippies. it might even
    be useful..
  - [nim](https://nim-lang.org), because compiling to C, it has the potential to
    be rather quick but with a larger standard library, and with a python-esque
    syntax, also quite usable.
  - [luajit](https://luajit.org/luajit.html), because I'm already familiar with
    lua and it claims to be the 'fastest dynamic language'.
  - [dlang](https://dlang.org/), because I've always been interested by it.
-->

## Tools

>   The master is only as good as the tools he uses.

In this section I will showcase the most useful tools that I have an use.

### Terminal

The most powerful tool for the programmer is the terminal.

>   A curated list of Terminal frameworks, plugins & resources for CLI lovers.

- [Terminals Are Sexy](https://terminalsare.sexy)

#### Emulators

>   Simple, performant, GPU-accelerated terminal emulator for macOS and Linux.
>   Probably the fastest terminal emulator out there.

- [Alacritty](https://github.com/jwilm/alacritty)

>   Terminal multiplexer: run multiple virtual terminals in one physical
>   terminal. Open terminal side-by-side.

- [tmux](https://github.com/tmux/tmux)

#### Shells

>   Powerful shell with scripting language.

- [Zsh](http://www.zsh.org)

>   Open source, community-driven framework for managing your ZSH configuration.

- [Oh-My-Zsh](https://ohmyz.sh)

>   Zsh configuration framework with blazing speed and modular extensions.

- [Zim](https://github.com/zimfw/zimfw)

>   The standard shell on most systems. Very simple but decent. 

- [Bash](https://www.gnu.org/software/bash/)

>   Sane bash defaults.

- [Sensible Bash](https://github.com/mrzool/bash-sensible)

### Editors

What is a programmer without a capable editor?

>   The ubiquitous editor. Available on most systems out-of-the-box. Versatile.
>   Extendable with plugins. Famously difficult to quit out of.

- [Vim](http://www.vim.org)

>   Modern editor based on Vim, with better extendability support.

- [NeoVim](https://neovim.io)

>   No plugins, zero configurations. All the essentials packed in by default.
>   Writtenin Rust, inspired by Vim.

- [AMP](https://amp.rs)

#### Editor Plugins

No editor is complete without a decent set of plugins to enable all the
functionality you need.

>   Makes it super easy to install plugins and runtime files into their own
>   private directories. Why? Because it means that you can clone Vim plugins
>   into `~/.vim/bundle` and they will be autoloaded.

- [pathogen.vim](https://github.com/tpope/vim-pathogen)

>   Sensible defaults for Vim.

- [sensible.vim](https://github.com/tpope/vim-sensible)

>   Syntax checker for Vim.

- [syntastic](https://github.com/vim-syntastic/syntastic)

>   File explorar plugin for Vim.

- [nerdtree](https://github.com/scrooloose/nerdtree)

>   Solarized colorscheme for Vim.

- [vim-colors-solatized](https://github.com/altercation/vim-colors-solarized)

>   Lean and mean status / tabline for Vim that's light as air.

- [vim-airline](https://github.com/vim-airline/vim-airline)

### Version Control

Version Control is to programming as insurance is to driving your car: you might
not like it at first, but after you've experienced one or another situtation,
you'll be happy to have it.

>   The one and only; the true path to programmer satisfaction.

- [git](https://git-scm.com)

### Static Analysis

It can catch bugs — before they happen!

>   A Ruby static code analyzer, based on the community Ruby style guide. Some
>   of the violations it finds it can, if you want it to, fix itself.

- [rubocop](https://github.com/bbatsov/rubocop)

>   A clang-based C++ “linter” tool. Its purpose is to provide an extensible
>   framework for diagnosing and fixing typical programming errors, like style
>   violations, interface misuse, or bugs that can be deduced via static
>   analysis.

- [clang-tidy](http://clang.llvm.org/extra/clang-tidy/)

>   A set of tools and APIs to perform static analysis, code visualizations,
>   code navigations, or style-preserving source-to-source transformations such
>   as refactorings on source code. There is good support for C, Java,
>   Javascript and PHP. There is also preliminary support for other languages
>   such as C++, Rust, C#, Html, CSS, Erlang, Lisp, Haskell, Python, OPA and
>   SQL. There is also very good support for OCaml code so that the framework
>   can be used on the code of pfff itself.

- [pfff](https://github.com/facebook/pfff)

### Code Formatter

While some programming languages come with tooling out-of-the-box, such as
Crystal with it's `crystal tool format` code formatter, others have to rely on
external formatters. These are some that I found useful.

>   A tool to format C/C++/Java/JavaScript/Objective-C/Protobuf code.

- [clang-format](https://clang.llvm.org/docs/ClangFormat.html)

>   A tool for formatting Rust code according to style guidelines.

- [rustfmt](https://github.com/rust-lang-nursery/rustfmt)

### Code Sanitizers

While we can't prevent bugs from occuring in the first place, there are some
things we can do in advance to help catch some.

>   A fast memory error detector, that can find out-of-bounds accesses, 
>   use-after-free, double-free, invalid free, memory leaks.

- [AddressSanitizer](https://clang.llvm.org/docs/AddressSanitizer.html)

>   A run-time memory leak detector.

- [LeakSanitizer](https://clang.llvm.org/docs/LeakSanitizer.html)

>   A detector of uninitialized reads.

- [MemorySanitizer](https://clang.llvm.org/docs/MemorySanitizer.html)

>   A fast undefined behavior detector. Modifies the program at compile-time
>   to catch various kinds of undefined behavior during program execution, for
>   example: using misaligned or null pointers, signed integer overflows, or
>   conversion to, from, or between floating-point types which would overflow
>   the destination.

- [UndefinedBehaviourSanitizer](https://clang.llvm.org/docs/UndefinedBehaviorSanitizer.html)

>   An instrumentation framework for building dynamic analysis tools. Includes
>   tools that can automatically detect many memory management and threading
>   bugs, and profile code in detail.

- [Valgrind](http://valgrind.org)

### Debuggers

Knowing the ins and outs of your favourite debugger is the key to efficient and
frustrationless programming in lower-level languages.

>   The debugger we all know, love and hate.

- [GDB](https://www.gnu.org/software/gdb/)

>   A *next generation, high-performance* debugger.

- [LLDB](https://lldb.llvm.org)

>   Record a failure once, then debug the recording, deterministically, as many
>   times as you want.

- [rr](http://rr-project.org)

## Libraries

What good is a programming language without the proper libraries to get anything
done?

### C Libraries

>   Parse and generate JSON formatted data.

- [Jansson](https://github.com/akheron/jansson)

>   Debug like a sir.

- [Debug](https://github.com/esneider/debug)

>   UTF-8 string handling made easy.

- [utf8.h](https://github.com/sheredom/utf8.h)

>   Regex library, default library used by Ruby 2.0 and later.

- [Onigmo](https://github.com/k-takata/Onigmo)

### C++ Libraries

>   Simple unit testing framework for C++

- [Catch2](https://github.com/catchorg/Catch2)

## Reading

### Books

### Papers

## Further

Assorted Awesome lists worth checking out with content related to mine.

- [Awesome C](https://notabug.org/koz.ross/awesome-c)
