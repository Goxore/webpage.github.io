# Why i learned vim in year 2021 / review for beginners 

## Personal Expirience

### First Vim encounter

In early September 2021 i decided to change my workflow a bit,
and by that i mean ditching windows and trying out other operating system.
And just like any other tech-savy person transitioning to GNU/Linux would do,
I quickly stambled upon this light-weight CLI text editor.

Also just like any other person first trying out vim, i did not manage to
exit at the first time, and had to kill the terminal.

At first I did not understand why people even bother learning something that out of
the box looks very unappealing, and needs you to know dozens of keybindings just to
operate on a basic level.

Whith That in mind, I had to know why many programmers and professional editors
all over the world prefer this beast, and spoiler, was not disappointed.

## What is Vim

### Vim for beginners

Vim is a great and highly-customizable tool, that will not only speed you up
to unbelivable levels after you learn some of it, but also will make your expirience
fun!

Although this is true that you won't become pro vim user in a day or a week, 
learning vim is actually not that hard as it seems! Most of the keybindings
stand for English words.

For example: 

d - delete

a - append

i -insert

c - change

f - find 

y - yank (copy)

p - paste

w - word

b - back

You can not only use those keybindings on their own, but also combine them
to form new ones

For example: 

dw - delete word

di( - delete in ()

yw - yank word

You might have noticed that i havent used any <Ctrl> or <Shift> keys
throughout the article, and that's because Vim is actually a modal text editor.
It means that it uses different modes, that determine what your keys will do.
Vim has quite a few different modes, but for beginners i reccomend at first concentrating on
Normal Insert and Visual modes, that are triggered by <Esc>, <i>, <v> keys respectively.

### More about Modes

When you first open Vim, you will be put in Normal mode, the one where all of your keys
won't be inseted into the text file, but will be used to trigger commands.
in this mode you can navigate through your file with hjkl or arrow keys.

to enter insert mode press <i> key, and to exit insert mode press <Esc>

While being in the Normal mode, you can switch to visual mode with <v> key.
It lets you select a portion of text, and then manipulate it with Normal mode keys.
Selecting the text and pressing <d> will delete(cut) it, <y> will yank(copy) it, 
<:> will let you permorm a command on it.

### key additions

Most Vim keys have a different effect when are used in uppercase. <v> key selects text, but
<V> key selects whole line, <d> key deletes selection, but <D> key deletes all text to the end of the line,
<i> key lets you insert text on your cursor position,
but <I> key sends your cursor to the beginning of the line
and activates insert mode.

## Why learn Vim in 2022?

Vim might sound like a relic of the past, but it is not less capable than modern text editors.
It has been around for decades, so you can easily get documentation on it through your favourite 
search engine, ot with :h command right in it.
With plugins like emmet, NERDTree and Coc you can make your vim a powerful code editor, 
and by customizing it's config you can optimize workflow with it to your liking.

Vim is preffered by many proffesionals in tech industry, so
you can spot it's keybindings in all sorts of CLI programs, and it is not going away
any time soon.

I had a blast learning Vim keybindings, commands and hidden features, and really hope I might
inspire someone to also do so!

