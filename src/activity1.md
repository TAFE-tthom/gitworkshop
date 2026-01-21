# Activity 1 - Config and Cloning Projects

Time to start diving into git, make sure you have:

* A terminal window open and you can confirm that git is available


1. Make sure you configure your email and username.

```
git config --global user.name "Git User"
git config --global user.email "gituser@gitworkshop.local"
```

With the above snippet, `user.name` and `user.email` are used to help identify commits which you can observe using the command `git log`.


2. Create a directory where you would like to store your projects. If you are opening the terminal and you have noticed it is in the home directory, a common convention is to create a `Projects` folder. You can do the following.

```
mkdir Projects
cd Projects
```

You can then confirm that you are in the correct directory using `pwd`.

```
pwd
~/Projects
```

3. Go to the following link <https://github.com/TAFE-tthom/gitworkshop.git> and you will see an option to clone the repository.

Time to clone the repository, to do this you will use `git clone <url>`.

You can use the following command which will allow you to clone this same workshop.

```
git clone https://github.com/TAFE-tthom/gitworkshop.git
```

Afterwards, you can confirm that everything has been downloaded and you can read the `.md` files inside the directory with your text editor or through the terminal.
