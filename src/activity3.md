# Activity 2 - Forking, Staging, Committing and Pushing

You have seen how we can clone a repository, what we will do now is `fork` a repository and clone it as well. This will now include being able to make changes and send them back to a repository that you own.

Make sure you have setup a `github` account with a **sshkey** or can authorise yourself with some other means.



As part of this activity, you should modify the file in `src/modifications.md`. You can open this up with any text editor.

To re-iterate:

1. Fork the repository through `githubs` UI, you can do this by visiting the repository <https://github.com/TAFE-tthom/gitworkshop.git>.

2. Afterwards, clone your version it using the git command line, it should replace `TAFE-tthom` with your github username.

3. Modify `modifications.md` inside `src` and following with staging, tracking, committing and pushing sections afterwards.


## Staging



By running `git status` will show:

```
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   modifications.md
```

This is because we have made modifications to this file that was originally tracked by git. While the above snippet says "Changes to be committed", this can also be that the changes are not staged as well.

You will need to run `git add` to then stage the files that you have modified.

## Commit and Push

Aftwards, you can then run `git commit -m 'First modification'` which allows you to create a commit and a messages associated with it.

Once the commit has been created, we have not sync'd with the remote server, so we will need to run `git push`, which will then take our set of commits and send them to the remote server.



## Review

1. Forked the repository

2. Modified a file

3. Added the modifications to staging

4. Committed them locally

5. Pushed them to the remote server.
