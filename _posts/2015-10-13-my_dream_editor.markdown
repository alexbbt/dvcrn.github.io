---
layout: post
title: "My Dream Editor"
date: "2015-10-13 16:05:17 +0900"
---

Today, let's talk about editors. Why? Because currently there are more editors than anything else. Microsoft decided to launch an editor, github decided to launch an editor - heck, even facebook suddenly invests into editors. We have closed source ones, open source ones, big full powered IDEs and of course the old school family.

The good thing, I actually like playing with editors. Sometimes I feel like just opening a new tool and test it out. Because of that I discovered SublimeText from NetBeans / PHPStorm. Because of that I also switched from SublimeText to VIM and later back to intellij. I love to constantly improve my workflow and find new ways to get even more productive.

The annoying thing about testing editors is that well, once you hit VIM you are pretty much in a dead end. From then on each and every editor __has__ to have VIM keybindings. If it doesn't, you can't use it. Naturally I spent a ton of time with VIM - the best vim emulation out there. SublimeText and Atom just couldn't cut it. They add a good amount of sugar into the mix, sugar I really like - but their VIM plugins are just not good enough (yet). So I kept going my way with vim, carefully tweaking my good old `.vimrc` as days come by.

To my big surprise, the editor that won me by storm wasn't vim and it wasn't neovim either. It was something that made me drop my beloved .vimrc without hesitation, something I thought I would never even touch - emacs. Yeah, emacs made me drop all other editors in the year 2015. Ridiculous, right? So what's going on?

# Enter spacemacs

![spacemacs][2]

[spacemacs][1] is an amazing pre-configured emacs made for people like me! VIM users!. It uses the power of evil, the arguably best VIM emulation out there and builds a layer of highly productive keybindings on top. Here's how it works:

In spacemacs, each command is triggered by the spacebar and follows a very innovative mnemonic. `spc` and `b` for example is showing you actions on the current buffer. `spc` and `p` executes project commands.

The really cool thing though comes from it's layer system. spacemacs has a ton of [contributed layers][3] that _just work_. For example without researching anything, I just enabled the react layer and suddenly I had full jsx support, highlighting, linting with eslint and a ton of keybindings! Just like that! Why? Because someone who actually uses react implemented it this way, the way it should be done.

So many _strong_ editors give me a ton plugins and what not without actually knowing the ecosystem of the target language / framework just for the sake of supporting as many things as possible.

And _if_ the plugin is superb, then the base of the editor is usually weak. Look at VIM: We have so many cool plugins but most of them are a big ugly hack in vimscript that works so-so. Emacs on the other hand is hackable in every little corner. It provides a powerful scripting language in form of `elisp` and has a very active community around it.

I would even argue that most of the layers that ship __with__ spacemacs out of the box are a good amount better than what I hacked together inside my .vimrc.

I was so impressed by it that I decided to [port parts of it to sublimetext][4].

My lovestory with spacemacs begins. Where were you all my life, you beauty of an editor? 

# What else?

Here's my 'mini ranking' of editors I like:

1. [spacemacs][1]
2. [intellij][5]
3. vim
4. [sublimetext][6]
5. [atom][7]

[1]: https://github.com/syl20bnr/spacemacs/
[2]: /images/spacemacs-python.png
[3]: https://github.com/syl20bnr/spacemacs/tree/master/layers
[4]: https://github.com/dvcrn/sublimious
[5]: https://www.jetbrains.com/idea/
[6]: http://www.sublimetext.com/
[7]: https://atom.io/
