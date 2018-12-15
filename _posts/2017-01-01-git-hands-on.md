---
layout: post
title:  "Get To Know Git"
---

<img src="https://wbootcamp.github.io/assets/gitcat.jpg"/>

Git isn't hard. Git isn't complicated. It's probably the amount of jargon thrown at your face that makes it look complicated.

### Before you start

We will use of lot of editing in this bootcamp. A nice light-weight IDE will be your best buddy. We recommend VS Code.

Visit https://code.visualstudio.com/docs/setup/mac to install VSCode on your Mac. Make sure you also install the terminal command:

- Open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command. - Restart the terminal for the new $PATH value to take effect. You'll be able to type 'code .' in any folder to start editing files in that folder.

### Lets get started

- Open your Mac Terminal and type the following commands:

```bash
    cd ~
    git clone https://github.com/wbootcamp/wbootcamp.github.io.git
    ls -larthS | grep wbootcamp
```


What do you see ? Note down your comments. What do you think the above set of commands did?

Now, type the following command:

```bash
    cd wbootcamp.github.io
    cat "Hello World" >> my_file.txt
    ls -larthS | grep my_file
```

What do you see ? Note down your comments. What do you think the above set of commands did?

Now, type:

```bash
    git status
```
What do you see ? Note down your comments. What do you think the above set of commands did?


Now, type:

```bash
    git add my_file
```

and then again,
```bash
    git status
```

What do you see ? Note down your comments. What do you think the above set of commands did?

Then,

```bash
    git commit -a -m "hey this is a new file"
```

and then again,
```bash
    git status
```

Did something change this time ? Note down your comments. What do you think the above set of commands did?

Finally, type

```bash
    git push
```

What do you see 😃 ? What did Git just try to do ? (Or was it GitHub ?) You can take help from the simple explanation below:


<img src="https://wbootcamp.github.io/assets/basicgit.png"/>

Note down your comments. What do you think the above set of commands did? Why do you think it says what it says? Do you now understand the difference between Git and GitHub ?

Now, visit https://www.github.com/ and create a new repository. DO NOT initialize your repository with a README, and DO NOT choose a license. Just provide a name.

<img src="https://wbootcamp.github.io/assets/newrep1.png"/>

You should then see a screen with a set of commands like this:


<img src="https://wbootcamp.github.io/assets/newrep2.png"/>

Next,

On your terminal, type the following commands (change <YOUR_REMOTE_URL> with your own repo's remote URL provided on GitHub.)


```bash
    cd ~
    mkdir newrepository
    cd newrepository
    echo "# newrepository" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin <YOUR_REMOTE_URL>
    git push -u origin master
```

Congrats ! You've successfully committed and pushed to GitHub







