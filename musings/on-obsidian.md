# on obsidian.md

Obsidian didn't work for me.  I gave it a drive for about a month or so, attempting to slightly modify my workflow to fit it, but ultimately, I'm going to move back to a slightly modified version of my existing note-taking routine:  VSCode.

When I first checked out Obsidian, I thought, "sweet, this will help me be more organized without having to really change what I'm doing."  Starting up with Obsidian is just as easy as opening the folder full of markdown files that I'm already using.  So, really, other than reading documentation, all I had to do was download it and get started.

But this doesn't actually leverage what Obsidian can do for you.  I attempted to reorganize the way that I took notes to some degree, breaking off more projects and landing zones from my daily notes document into their own space.  It didn't really work, though; I ended up with a sort of half-baked zettelkasten that felt all over the place.  The last thing I'd want is for the tool that helps me organize my thoughts to feel unorganized.

So, to me, Obsidian felt like it tried to do too many things at once, and not very well.  It's not an "IDE"; there are plugins, but they just don't really match what I get out of writing plain markdown in VSCode.  For example, I just opened on of my markdown files that I'd written in Obsidian in VSCode, and immediately saw all of the trailing whitespace that I'd just left hanging around highlighted in bright red.  And, of course, the code snippets I'd embedded in the first file I'd opened had syntax highlighting in them, unlike in Obsidian!

Also, I just didn't really feel like I needed Yet Another Electron Application open to take notes.  Switching between writing notes and writing code should not be distracting — doing so with VSCode is, in my mind, seamless.  Switching between Obsidian and VSCode still always required a context switch for me.

The other benefits I thought Obsidian could have brought to the table just didn't work out for me, either.  Obsidian has a unified aesthetic, and seen from far away, it is quite pretty.  But that got stale for me pretty fast, and I found myself again preferring my hyper-personalized VSCode setup.  I found the places where Obsidian took over and formatted your markdown for you just not worth it — I guess I just prefer headers to be boldly highlighted, but not actually bigger when I'm writing documents.  At the end of the day, I just found my VSCode theme more delightful to look at.  I [even tried theming Obsidian](https://github.com/tjwds/obsidian-minimal-iceburg), but it still just couldn't hold up.

There are very many valid complaints to be made about Microsoft, but VSCode is licensed under MIT.  Microsoft seems to have found shepherding this editor that I really, really like profitable, but maybe a lot of that is because they're big name players that can afford to give the project the attention it deserves.  Obsidian is closed-source, and though the way they seek to gain a profit off the editor isn't creepy yet, I could see it easily growing that way.

## Concrete UI complaints

So:  that was a lot of abstract complaints, but there were quite a few day-to-day UI quirks about Obsidian that made me quit it.  Some of these are just an artifact of my having gained muscle memory for one editor and then attempting to switch to another, but others, I think, are valid complaints, and even those that are _clearly_ a me problem could be resolved by letting things be a little more configurable.

### I just don't get the way that changing between files works

I could not wrap my head around pressing ⌘O to bring up the file switcher, but this is probably because Obsidian's "action" command pallet shortcut is ⌘P, which is subtly different from VSCode, where the command pallet is in "file" mode on ⌘P and "action" mode with ⌘⇧P (or, my preferred ⌘P then typing `>`).  I know that this is mostly a me problem, but this seems like a pretty hard break from the way any other editor does things.

### New files

I kept pressing ⌘N to create a new file and ⌘V to dump my clipboard buffer in one single action, because this is muscle memory for me at this point, but if you do this in Obsidian, you'll end up with your paste buffer as the file name, and you can't just ⌘A to select and delete your mistake, because you can't ⌘A within the title.

• some clunky markdown things, especially making lists
• Panes are not great imo
• No tabs???
• Accidental detritus everywhere — constantly deleting Untitled.md pages
• does not support folders very well, impossible to find where an open doc currently is
