# How To Computer
  A page you can send your friends so they learn how to use the most powerful device ever created. The goal of this document is to provide concise, instructional answers to basic "How Do I ...?" questions about how to operate a personal computer. 

  You've managed to find this page so we hope you understand at least some basic computing concepts. You know how to move the mouse, open a program, browse the web and use the keyboard at least enough to play Fornite or something. But you can do more. The personal computer is a marvel of human engineering and an extremely powerful tool for enacting your will on the world! It has unparalelled creative potential in almost every conceivable field in a way that mobile phones simply cannot match. While you certainly *can* edit video on a phone it is *much* faster to do so on a personal computer. Just from an ergonomics perspective smartphones cannot compete with a desktop or laptop computer. So this page is aiming to be a reference for folks new to driving a personal computer and want to be able to get their shit done faster. Even if you hate computers I hope you at least appreciate the prospect of getting your work on them done faster so you can get away from the cursed machine. 

## How do I use this document?
  This is intended to be read either in a top-down manner or via search. Use your browser's built-in search function by hitting the `ctrl+f` chord and typing. Can't find what you're looking for? Please make sure you looked first. Then, file an issue and tag it as a question. Feel free to file any complaints, suggestions or corrections as issues.

## Navigation

### How do I manage files
With `Windows Explorer` AKA `Explorer` AKA `explorer.exe` the default windows file explorer

{{TODO: Screenshot}}

Quick Definitions:
 * `file` - A basic unit of storage on a computer. It can contain a poem, a program, a picture of a cat or anything else you would find on a computer.
 * `directory` - A "folder" that contain mutliple `files` and other `directories`. Useful for organizing files heirarchically
 * `chord` - A combination of key presses. `ctrl+c` means holding down the `ctrl` ("Control") key and pressing the `c` key
 * `disk` - The actual physical part of the computer where files live. Hard Disk Drives (HDDs), Solid State Drives (SSDs) and SD Cards are all `disks` to us
 * `file path` - The path to a file. Where the file lives on `disk`. A text file can live at the path "C:\mydirectory\myfile.txt"
 
 --- 
 
#### How do I select a file?
`left-click` the `file` once to `select` it

{{TODO: Gif}}

#### How do I open a file?
`left-click` the `file` twice (known as `double-clicking`) to open the `file` with its default application. Text files will open in Notepad, image files will open with the Photo Viewer, etc.

{{TODO: Gif}}

#### How do I select multiple files?
`left-click` and drag an area in the window without a file and drag to create a selection bounds, a box that will `select` every file within it when you release the `left-click`

{{TODO: Gif}}

#### How do I delete a file?
The `delete` key can be used to move all currently selected files to the `Recycle Bin`

{{TODO: Gif}}

#### How do I move a file?
Open an `explorer` window to the directory that you want to move your file to.

With one or more files `selected`, `left-click` on one of the files and drag the mouse cursor to your other window. Release the left mouse button to "drop" your selected files into the target directory.

{{TODO: Gif}}

#### How do I cancel moving files?
You changed your mind and don't actually want to move those files but you've already begun dragging them. Your finger is holding down the left mouse button but you don't want to actually move anything! Simply hit the `Esc` key to cancel the operation and escape that sticky situation. Even if you're still holding down the left mouse button you can safely release it without moving any files.

{{TODO: Gif}}

#### How do I move a file without opening another explorer window?
Select the files you want to move and use the `ctrl+x` chord to "cut" the files. Then navigate to the directory you want to move files to and use the `ctrl+v` chord to "paste" the files. When you paste the original files will be deleted. The files you originally cut will still be in your clipboard, you can paste them again somewhere else with the same `ctrl+v` chord.

{{TODO: Gif}}

#### I hit `ctrl+x` but I changed my mind, how do I undo the cut operation?
The `Esc` key will cancel the cut operation. The file will no longer be in your clipboard and will not be able to be pasted with `ctrl+v`. The file will not be deleted or moved.

{{TODO: Gif}}

#### How do I rename a file?
The `F2` key will begin renaming a selected file. You can also begin renaming a file by `left-clicking` on it twice; not fast enough to `double-click` it and open it but fast enough to actually begin renaming. This sucks and is easy to do accidentally. The `F2` key seems out of the way but is much more precise.

{{TODO: Gif}}

Recommended: `Show File Extensions`

#### How do I make a new directory?
The fastest way is to `right-click` an empty area in the `explorer` window to bring up the `context-menu`, go to the `New` submenu and select `Folder`. The `directory` will be created and immediately enter naming mode. Hit the `Enter` or `Esc` key to just use the default name "New Folder" or type in a more descriptive name first. 

{{TODO: Gif}}

#### How do I make a new text file?
`right-click` an empty area in the `explorer` window to bring up the `context-menu`, go to the `New` submenu and select `Text Document`. The text file will be created and immediate enter naming mode. Hit the `Enter` or `Esc` key to just use the default name "New Text Document" or type in a more descriptive name first. 

{{TODO: Gif}}

#### How do I make a new file other than a text document?
Applications can add their own items to the `New` section of the `right-click` `context-menu`. E.g. if you have Microsoft Word installed you will have the option to create a new Word document.

{{TODO: Gif}}

#### How do I make a file other than a text document that isn't in the context menu?
Applications normally contain a `file menu` in the top left that contains file operations. Select `new` from this menu to get a `dialog` for naming and placing a new file that the application can handle. The default contents of the file are determined by the application.

{{TODO: Gif}}

The `ctrl+n` chord will instruct the current application to create a new file, similar to using the `file menu`. 

{{TODO: Gif}}

In some applications, like Paint, "New File" (`ctrl+n`) will not immediately create a new `file` but instead create a blank canvas. The `Save` `file-menu` item or `ctrl+s` chord will prompt you to actually save the `file` to `disk`.

{{TODO: Gif}}

#### How do I make a totally blank file of a given type?
Create a new text document and change the extension from `.txt` to your desired extension, say, `.py` (for a python script). New text documents will always be completely blank

{{TODO: Gif}}

#### Oops I accidentally began renaming a file. How do I stop without changing the file name?
Hitting the `Esc` ("escape") key will cancel the renaming action and leave the `file` unchanged. Many actions can be cancelled with the escape key. 

{{TODO: Gif}}

#### Oops I accidentally moved/deleted a file I didn't mean to. How do I undo it?
The `ctrl+z` chord will undo the previous operation. Use this to move files back to where they were, restore a file to the previous name or bring a file back from the `Recycle Bin`.

{{TODO: Gif}}

You can also go to the `Recycle Bin` on your `Desktop`, `double-click` it to open it and move the `file` to a new `directory` to un-delete it. 

{{TODO: Gif}}

`Right-clicking` the file will bring up a `context-menu` with a `menu-item` titled `Restore` which will put the `file` back to where it was before it was deleted. 

{{TODO: Gif]}

## Details 

Sometimes the devil is around here 😈

### What actually *is* a file anyway?

  All computer systems you care about use a "filesystem"  that organizes information into `files` and `directories`. A `directory` can contain 0 or many `files` or child `directories` and a `file` can contain as much information as you have storage. We identify `files` and `directories` by `name` such as `my_file.txt` and `my_directory`. 

  All `files` exist in a `directory`. When a computer's storage is blank it has only one directory which is considered the `root`. In Windows that is what `C:\` is: the root of the drive labeled `C:` and all `files` and `directories`exist as `children` underneath this `root`. If we were to have one `file` named "my_file.txt" on the C: drive we would consider that `file's` `path` to be represented as `C:\my_file.txt`. A directory underneath the `root` wuld have a path of `C:\my_directory\` and a `file` that exists under *that* `directory` would have a path of `C:\my_directory\my_file.txt`. You may not have two `files` with the same name in the same `directory`. You may have `C:\my_file.txt` and `C:\my_directory\my_file.txt` but you may only have 1 `file` that exist at the `path` `C:\my_file.txt` at a time. If you want two `files` in the same `directory` with the same `name` you will be forced to re-name the second `file` to something like `my_file1.txt`. Windows will do this for you automatically if you fail to give it anything else to work with.
  
  A `file` may or may not have an `extension` at the end of the name that tell you how the `file` is intended to be used. "mynotes.txt" is a `file` that is intended to be read as text where as "info.csv" contains text data in a series of "comma separated values" (that's where the csv comes from). File extensions are often only 3 characters but that is vestigal; today extensions can be as long as you'd like.
  
  Windows uses these extensions to determine what happens when you double-click or open the file by default. Opening a file with the `.txt` opens the Notepad application by default {{TODO: Screenshot}}. This can be changed (See `Changing Default Applications` {{TODO: Make section and link to it}}). 

  File extensions are only suggestionms and can be changed at any time by you or any application that is allowed to access them. You do not need to respect a file's extension and you do not need to trust it. `.txt` files can contain video data and just look like nonsense in a text editor, `.png` files can actually contain `jpeg` data, you can write out all the data that makes up an image in a `.txt` file with a text editor and then load that `.txt` file in an image viewer to see it. More interestingly, the save file that has your character in your favorite offline video game may be named something like `my_save.sav` but actually just be text that could be read and modified if you were to open it with a text editor. 

#### Recommendations
Show File Extensions {{TODO: Create and link to section}}
