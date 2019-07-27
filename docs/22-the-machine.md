---
id: 22-the-machine
title: The Machine
---
## The Workhorse

### Linux’izing Windows PC
Linux’izing [your Windows PC into a dev machine – Part 1](https://cepa.io/2018/02/10/linuxizing-your-windows-pc-part1/)

> On 30th of March 2016 hell officially froze. Microsoft, the eternal rival of the open source movement, has officially announced that form now on you can run Linux apps on Windows! Just like that.

Yeah, but who cares about some new geeky stuff in Windows?

For those of you who are reading this and aren’t techies, let me give you some background.

Nowadays, when you create a project, build an application or a startup, you likely run it in a cloud and your customers use it either on desktops in a web browser or as an application on theirs smartphones, tablets, etc. More and more stuff is being moved to cloud and used via Internet.

Now, to build all these amazing and often useless apps you need tools, and it happened that vast majority of these tools are open source and primarily built for Linux in mind. Simply speaking, trying to build web or cloud based applications on Windows was either no go or at least a serious pain in the a** till 30th of March 2016.

From business perspective, `it means that you or your employees no longer need to buy shiny yet overpriced Mac` because “you need a terminal and SSH” and “ability to run MS Office”, neither you need to sacrifice lots of productivity software like Photoshop and work exclusively on Linux that doesn’t support most of it.

You can now have it all on your Windows PC and so this post is about how you can actually do it.

Having years of mileage on Linux, I’ve spent last couple of months working primarily from a Windows 10 laptop, ThinkPad T460, using Bash on Windows and can share some experience here – `what works, what almost works, and what doesn’t` – from a developer perspective, ,`and I tell you, what Microsoft did is pretty awesome`

### MAC Dev environment setup

- How to Set up an [Apple Mac for Software Development](https://www.stuartellis.name/articles/mac-setup/)
- New MacBook [Setup for Developers](https://dev.to/therealdanvega/new-macbook-setup-for-developers-2nma) -- see SDK man
- macOS [Setup Guide](https://sourabhbajaj.com/mac-setup/)
- A beginner's guide to setting up a [development environment on macOS](https://github.com/nicolashery/mac-dev-setup)

### Shell - OhMyZsh

- Shell : Oh 'My Zsh' `'bottom'`, `bottom222`,
[iTerm2 + Oh My Zsh + Solarized color scheme + Meslo powerline font](https://gist.github.com/kevin-smets/8568070)


- Ag : File search A code-searching tool [similar to ack, but faster](http://geoff.greer.fm/ag/)

### Future Table

| Name               | Language     |  extras    |  Notes |
| -------------      |:-------------   |-------------  |:-------------:| 
| Pycharm            | Python, Django          |    |  Pycharm > VSCode ? |