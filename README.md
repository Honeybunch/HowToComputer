# HowToComputer
A page you can send your friends so they learn how to use the most powerful device ever created

  You've managed to find this page so we hope you understand at least some basic computing concepts. You know how to move the mouse, open a program, browse the web and use the keyboard at least enough to play Fornite or something. But you can do more. The personal computer is a marvel of human engineering and an extremely powerful tool for enacting your will on the world! It has unparalelled creative potential in almost every conceivable field in a way that mobile phones simply cannot match. While you certainly *can* edit video on a phone it is *much* faster to do so on a personal computer. Just from an ergonomics perspective smartphones cannot compete with a desktop or laptop computer. So this page is aiming to be a reference for folks new to driving a personal computer and want to be able to get their shit done faster. Even if you hate computers I hope you at least appreciate the prospect of getting your work on them done faster so you can get away from the cursed machine. 

## Navigagtion
---

### How do I manage files
With `Windows Explorer` AKA `Explorer` AKA `explorer.exe` the default windows files explorer and your mouse

{{TODO: Screenshot}}

#### `Left-click` a `file` once to select it
With a file selected:
  * The `Enter` key will open the file as if you had `double-clicked` it
  * The `delete` key will to move it to the `Recycle Bin`
  * The `F1` key will begin renaming the file. You can just start typing a name and then hit `Enter` to save it or hit `Esc` to cancel and leave renaming mode
{{TODO: Screenshot}}

#### `Double-click` a `file` to open it in an associated application
That's really it

#### `Right-click` a `file` to open the `context-menu`
This is a fast way to perform some actions on a file without having to open an application beforehand.
A file's extension also associates exactly which items appear in this menu. An image file will have options for rotating that a text file has no use for. 
{{TODO: Screenshot}}

### What actually *is* a file anyway?

  All computer systems you care about use a "filesystem"  that organizes information into `files` and `directories`. A `directory` can contain 0 or many `files` or child `directories` and a `file` can contain as much information as you have storage. We identify `files` and `directories` by `name` such as `my_file.txt` and `my_directory`. 

  All `files` exist in a `directory`. When a computer's storage is blank it has only one directory which is considered the `root`. In Windows that is what `C:\` is: the root of the drive labeled `C:` and all `files` and `directories`exist as `children` underneath this `root`. If we were to have one `file` named "my_file.txt" on the C: drive we would consider that `file's` `path` to be represented as `C:\my_file.txt`. A directory underneath the `root` wuld have a path of `C:\my_directory\` and a `file` that exists under *that* `directory` would have a path of `C:\my_directory\my_file.txt`. You may not have two `files` with the same name in the same `directory`. You may have `C:\my_file.txt` and `C:\my_directory\my_file.txt` but you may only have 1 `file` that exist at the `path` `C:\my_file.txt` at a time. If you want two `files` in the same `directory` with the same `name` you will be forced to re-name the second `file` to something like `my_file1.txt`. Windows will do this for you automatically if you fail to give it anything else to work with.
  
  A `file` may or may not have an `extension` at the end of the name that tell you how the `file` is intended to be used. "mynotes.txt" is a `file` that is intended to be read as text where as "info.csv" contains text data in a series of "comma separated values" (that's where the csv comes from). File extensions are often only 3 characters but that is vestigal; today extensions can be as long as you'd like.
  
  Windows uses these extensions to determine what happens when you double-click or open the file by default. Opening a file with the `.txt` opens the Notepad application by default {{TODO: Screenshot}}. This can be changed (See `Changing Default Applications` {{TODO: Make section and link to it}}). 

  File extensions are only suggestionms and can be changed at any time by you or any application that is allowed to access them. You do not need to respect a file's extension and you do not need to trust it. `.txt` files can contain video data and just look like nonsense in a text editor, `.png` files can actually contain `jpeg` data, you can write out all the data that makes up an image in a `.txt` file with a text editor and then load that `.txt` file in an image viewer to see it. More interestingly, the save file that has your character in your favorite offline video game may be named something like `my_save.sav` but actually just be text that could be read and modified if you were to open it with a text editor. 

#### Recommendations
Show File Extensions {{TODO: Create and link to section}}
