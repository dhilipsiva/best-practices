# The Elite Startup Checklist

As I was reading through [The Joel Test: 12 Steps to Better Code](http://www.joelonsoftware.com/articles/fog0000000043.html), an epic post by [Joel Spolsky](http://www.joelonsoftware.com/). It was a 13-years-old awesome post. It had a bit of *corporate* touch. So I decided to write a post with *startup* touch, with his original post as a reference. A 2013ish sartup touch. Now beware, I am NOT Joel Spolsky. I mean, I am not as awesome as he is. I am just a kid who is trying to understand stuff. So everything that I am about to say, might be totally wrong. This is just an attempt to share what I know. That said, comments and corrections are welcomed to improve this article. I have put this on my [GitHub Repo](https://github.com/dhilipsiva/best-practices/blob/master/The-Elite-Startup-Checklist.md). Pull requests are welcomed.


## Who is this article for?

This article is mostly going to be for startups. I ll try my best to keep this post useful for both newbies and experienced alike. I ll start with some basic and obvious things and end up with more advanced stuff.


## The Checklist

* Do you use a Mac?
* Do you use comman-line?
* Do you use vim/emacs?
* Do you use source control?
* Do you use CoffeeScript and SCSS/LESS?
* Do you use scaffolding tools?
* Can you make a build in one step?
* Do you have auto deploy scripts to production?
* Do you push code to production almost everyday?
* Do you have auto deploy scripts?
* Do you have a bug/issue database?
* Do you fix bugs before writing new code?
* Do you have an up-to-date schedule?
* Do you use the tools that increases productivity?
* Do you have a good documentation?
* Do you automate tests and other stuffs?
* Do you follow DRY principle?
* Do new candidates do math during their interview?


## Do you use a Mac?

### Windows

Okay, before you start thinking, 'Ugh, yet another Apple fanboy!', I want to tell you that this is purly an intellectuall and well-thought opinion. "How?" you ask. Well, I first started out my carrier with windows as primary development platform. While windows has unbeatable and unparellel Developer Tools for microsoft based products, lets face it, It sucks at Open Source development. And if you are a startup, it is highly likely that you are into open source. Not that it is impossible in windows. It is mostly manual and hard to setup. Most of libraries wont compile on windows. So you will have to download developer builds and install them maually, which mainly involves clicking `Next` button (without reading anything in the dialog :P). If you are used to this kind of approach, I know what you are thinking right now. Isnt this supposed to be easy? To those guys, I tell you my friends it is not. I ll explain more about this is "Do you use comman-line section?" So it is really hard to set you Dev-Env up compared to other platforms unless you are working with one of Microsoft's technologies(maybe for HTML, JavaScript or TypeScript too). So stay away from windows if you can. If you are into .Net stuff, then you obviously have no other choice except Windows.

### Linux

So you think you can't afford Mac. Or you dont want to buy another hardware just because you already have a windows mechine. Do not worry. Linux is here to the resque. While I was using windows, I had to setup a ubuntu machine for deployment. I insalled and realized how easy it was setting up server. I was using python. I beleive almost all *nix distributions comes with python. I didnt had to configure any path like I goofed around with window's Environment Variables. I realized how easy it was to setup. Just `sudo apt-get install <package-name>`. So I had a bunch of Shell scripts handy to set up the environment automatiaclly. So for development, I think Linux is much better than Windows. And as far as a designer is concerned, he cannot run propritary softwares like Adobe's or Corel's softwares which renders it useless for them.

### Mac

"If Linux is free and does much better than Windows, why would I buy an expensive Mac?" you ask. Becasue Mac is much, much better than Linux. No matter how you tweak your Linux, the UX will never be as much sexier as Mac. I am not talking just about the "Eye Candy" stuff. I also mean its usability. You have AppleScript which you can use to automate your Mac. I have a routine work. When I press a shortcut, I want my terminal to be opened with 5 split screens, each window running a specific command like one ssh-ing into production server, another building and running my last dev-server, another openening up specific files to edit and so on. I can do all of this with AppleScripts+Automator instead of me typing-in everything, everytime. This saves me a lot of time. I think that most of the development-related app supports AppleScript. It has an awesome developer ergonomics compared to any other product on planet. And Should I mention about the new eye-popping, jaw-dropping and mind-blowing Retina Display on MacBook Pro? Okay I now know that this is not convincing enough for you to use a mac. Wait untill you finish the "Do you use command-line?" section. (Some personal info: Yes, I am a fan of apple products. But I assure you, My decision to use a Mac is NOT influenced my emotion. It is purly intellectual as I mentioned earlier.)


## Do you use comman-line?

Skip this section if you are a designer. While it is worth learning, I think it does not bring any serious productivity improvements for a designer as GUI is their only choice.

If you are used to GUI, I can read your mind-voice as I type this now. Why the @#$% would I use command-line when I have GUI. You might even think that command-line is old school and belongs to ancient times. If you are one of those guys, YOU ARE WRONG!. Consider a simple scenario.
