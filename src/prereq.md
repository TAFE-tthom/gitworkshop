# Pre-requisites

Alright! There are a few things we need to sort out first! Make sure you have the following.

* Access to a computer (or android device with Termux on it or Linux shell)

Ideally! Make sure you have also done the following.

* Downloaded `git` from <https://git-scm.com/>
* Familiar with some command line basics! If not, we will go through them!
* Access to a text editor like vs-code, vim, nano or something else.

## Git Terminology

* **Repositories**, locations in which source code is stored/committed to. There are local and remote repositories that you can **push**

* **Commit**, A commit is set of changes you have made to a repository. This could involve any files that have been `added`, `modified` or`deleted`. You can see `commit`s using `git log`.

* **Staging**, staging is a state **pre-commit**, when you make changes or add/delete files from the repository, these changes can be `staged`, as in ready for a `commit`. You can check the status of staged changes using `git status`.

* **Remote**, This is a repository that is usually on another computer (or server). Services like `github`, `codeberg` and `gitlab` usually allow developers to create a repository on their service and treat that repository as a remote one. You can have multiple `remote` repositories set up.

* **Cloning**, This is where we create a duplicate of a repository (typically one that is online) for our purposes locally. We are able to use `git clone <url>` where we can clone the repository and use it/modify it and commit back to it (assuming we have permissions) or have a **fork** of it (A derivative version).


Now onto some terminal usage shortcuts and terminology.


## Command Line 

**Shell Cursor Manipulation (Also works in text editors)**

The following shortcuts will improve moving the text cursor quickly in the shell and a text editor.

* `CTRL+A` - This will reset the text cursor to the beginning of the line.

* `CTRL+E` - This will set the text cursor to the end of the line.

* `CTRL+RIGHT_ARROW` Will move to the start of the next word

* `CTRL+LEFT_ARROW` - Will move to the start of the previous word

To get access to some previously executed commands, you can use `UP_ARROW` which will go to the previous command. While traversing this list, you can use `DOWN_ARROW` to go to the next command.


When using the following shortcuts, you should be able to edit text quickly.

* `CTRL+W` - Deletes the previous word - **Don't use in the browser**

* `ALT+D` - Deletes the next word

* `CTRL+U` - Deletes the line

* `CTRL+SHIFT+V` - Pastes what is currently in the copy-clipboard.

* `CTRL+K` - Cuts the text (to the clipboard) until the end of the start

You will likely have a process that gets stuck or you want to stop inputting text into your process. These shortcuts provide a quick solution to some of these issues.

* `CTRL+C` - Interrupts the process.

* `CTRL+D` - When a process is executing, it may await for input from the user however by using this shortcut it will close `stdin`.

* `CTRL+L` - It will clear the screen.

* `CTRL+Z` - It will suspend the process and send it to the background.

