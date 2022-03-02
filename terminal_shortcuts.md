## Intro

When I first starting using a UNIX terminal it wasn't love at first sight... It rarely is, for someone used to talk to a computer through mouse clicking. Unless, I guess, you start delving in it out of curiosity, free to explore with no pressure and no expectations to meet. My advice: don't dive into it on a tight schedule expecting great results.

GNU/Linux operating systems are very powerful. In honest truth, the best way to harness all that power is through the command line. Hence, I started this series of posts - "[Termifobia]()" - to share some personal tips I wish I had when first starting off. This is meant to help those transitioning to or ocassionally using a Linux Terminal. Hopefully, it might help you get the most out of it, with less work and head bashing moments.

## Absolute essential

Yes, some might already know these, but I was one of the few who didn't, and it made my life so much harder without me ever knowing how hard it was until I realized these shortcuts existed since the *"beginning of time"*.

- `Tab` - **Autocomplete** \- Just start typing something and press `Tab` and the Terminal will show you the available possibilities to finish your word. This might be a command, a file, a folder... Absolute magic!

- `Ctrl + C` - **Kill currently running command** \- More often than what you might think at first, you will run a command and regret it. This one will take care of it, stopping everything in its tracks.

- `Ctrl + L` - **Clear terminal screen** \- Type as little as 5-6 commands and your Terminal screen will look too crowded. This shortcut will clear the screen and give you some breathing air.

- `Up/Down arrows` - **Navigate through previous commands** \- Again, more often than what you might think, you will need to re-run your previous command or a very similar version of it. With your command line empty, hit the `Up arrow` key and the previous command will show up. You can now use the `Left/Right arrows` to navigate the line and modify it as required.

Here is a free Mnemonic to help you remember the essentials:
<br>**T**ake **C**are **L**ittle **U**nicorn 🦄

## Time-savers

- `Ctrl + Z` - **Suspend/Move to background** - Your currently running command usually prints output to your screen. This shortcut is very useful if you need to rescue your terminal prompt. It will send whatever is running to the background and allow to have control of your terminal again. When you are done and want to see the output of the first command again, just run `fg`, a linux command that brings background running jobs to the foreground.

- `Ctrl + A` / `Ctrl + E` - **Move cursor to beginning/end of line** - Similar to `Home`/`End` keys on keyboards that have them. This will automatically move the cursor to the beginning or end of the line with A or E, respectively. Very useful for editing long commands.

- `Ctrl + R>R>O/G` - **Seek and revive** \- This one looks strange, but it will make sense. Hit `Ctrl + R` once and a prompt will show up showing the following message: *''bck-i-search:"* and you can now type to search for any command in your history. You might remember running program but aren't sure about the arguments you used. Well, you can search for the program's name and the matches will show up in your terminal. Hit `Ctrl + R` again to cycle through all the history entries that match your search. Hit `Ctrl + O` when you find it to put it in your Terminal prompt and run it immediately. Alternatively, hit `Ctrl + G` instead to leave the command in the terminal prompt without running, so you can edit it. Hence R>R>O/G.

- `Ctrl + U` - **Delete everything behind the cursor's position** - Imagine you type a command, arguments, or even a oneliner and it fails. And you get a hint from the output in the likes of: *bash: command not found*. You get it back to inspect it (remember: `Up arrow`) and notice that there is a typo in the command. With this shortcut you can delete the command, fix the typo and keep the rest of the line intact.

Here is a second Mnemonic:
<br>**Z**ombies **A**re **R**unning **U**phill 🧟

## Conlusion
So, take home message: *Take Care Little Unicorn, Zombies Are Running Uphill*. Use this mnemonic, create your own, pin this blog post, copy the [Mini-cheatsheet](##Mini-cheatsheet), ... Whatever works best for you. Just keep in mind that the more you use the shortcuts, the more they will stick with you, and the more productive you will be in your Terminal.

Now here is a Zombicorn, because, why not?

![zombiecorn](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJAzE7G9_xV08GwORMXCsjS94UuW0W3wrhRA&usqp=CAU)

## Mini-cheatsheet

Mnemonic | Shortcut | Behavior
:---:|:---:|:---:
Take | `Tab` | Autocomplete
Care | `Ctrl + C` | Kill running command
Little | `Ctrl + L` | Clear terminal screen
Unicorn | `Up/Down` | Cycle previous commands
Zombies | `Ctrl + Z` | Suspend running command
Are | `Ctrl + A` / `Ctrl + E` | Move cursor to beginning/end of line
Running | `Ctrl + R>R>O/G` | Search command history and re-apply line
Uphill | `Ctrl + U` | Delete all left of cursor position

## Refs
Inpired by Waseem Mansour's [post](https://www.redhat.com/sysadmin/top-10-shortcuts).