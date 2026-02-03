---
layout: post
title:  "My neovim journey and how do I use in 2026"
date:   2026-01-12 12:42:13 +0545
categories: blog 
---

In this blog I am going to share my vim/neovim journey and how I am using in 2026,
this is my personal experience and journey of vim/neovim and there might be some
grammatical mistake so bare with it.

### Chapter 1 (First Impression) 

The first ever impression about the vim/neovim was back in 2018(first year of college) when I saw  this guy [William Lin][williamlin] solving competitive
problems.

I was there just to watch how competitive problems are solved but instead I am completely blown away by how fast he move around and quickly edit his code, jump back and forth, move around the codebase very quickly, he was solving the CP problems in C++ on vim.
I am pretty sure this is not possible with the shortcut keys I was familiar with *VS Code* like `ctrl+ right/left arrow` for moving one word left and right, `ctrl+shift+left/right arrow` for selecting text etc.., because he was doing in such speed it is not possible to press these many keys this quick.

I did little research and found there is [vimrc][williamlin-vimrc] in his git repo, this is where I actually found the answer I am looking and found out the world of vim.

### Chapter 2 (Explore)

I was first year of college and I don't know much coding then(still not expert) but I am
interested on solving the problems I didn't did any real coding till then so
it's not that difficult to switch and learn [vim][vim] motions so I started to setup
vim (not [neovim][neovim]) ,watched some youtube video (I probably watched [Primeagen][primagen] but I
didn't know him then) and with the help of his [vimrc][williamlin-vimrc], I
managed to complete working vim setup in my windows machine for C++ for
competitive Programming. I hardly solved 5 Simple DSA problems but learned some
basic vim motions for move around, copy, paste, insert etc., and I really love
it I feel like I was very productive ( although I just know to move around ).
Since I hadn't done any serious coding until then it didn't affect my
productivity at all.

It continued like this I was doing some practice and some coding here and there
but didn't code that much, but on my 3 year of bachelor we need to do projects
and for that I need to use VS Code because well that's the first thing you will
do in every youtube tutorial (setup VS code), but I loved the vim motions so
much I can't give up on that, so I searched and find vim extension for vs code.
After that I stopped using vim and started using VS code with vim extension, I
disable my vim extension if my friends need to edit on my code otherwise I
use regularly.

I become pretty good with the vim motions I learned some extra motions, but
I still rely on mouse for stuff that are outside of the file like opening terminal, search, opening and closing files but i am okay with it and just continue with what I already know and never explore more and try other things.

After completing my bachelor in 2022 I started doing internship on frontend (React and React Native), I am used to with VS code with vim extension but on my internship, I had to completely disable the vim keybindings and just started using normal VS Code without vim extension for roughly 5 months, because I need frequent help form senior and my senior is not familiar with vim motions.

After I become somewhat familiar with js/ts, react and require less helps, 
I am started using vim again but this time I want to replace vs code with [neovim][neovim] completely 
and also started to watch more and more vim
related video to improve my vim motions vocabulary, at that time I watched
[Primeagen][primagen] video and other vim creator, after all of this I setup the neovim with [NvChad][nvchad]. 

I made working setup for React/React-Native project and continue to use that for all of
my project (office/home), although I didn't know
anything about the lua and nvim setup, I daily change the setup and
configurations, I find it very fun and also I am not afraid to mess around with config because if anything goes wrong i can reinstall NvChad and also I have VS Code as backup. On doing this I learned a lot vim motions, created custom vim motions and  able to code pretty much without mouse and I really enjoyed that and it continued like this till the end of 2024. On that period I watched lot of [Primeagen][primagen] video , know [Teej][teej] and learned [Golang][golang]. 

### Chapter 3 (Full Custom Neovim)

At the end of 2024 [Teej][teej] released the [advert of Neovim][advert-of-neovim] series which
guide to setup [Neovim][neovim] without any distro, till then I already know lot about
[neovim][neovim], some basic syntax about [lua][lua] and working flow of neovim config so
started to follow that series and able to setup my own neovim without any
distro so I ditched NvChad and went full custom neovim. From there to this date, I still use that setup with some adjustment, I normally install bunch of
packages and themes, come on guys I work with js/ts, React and React Native.

### Chapter 4 (Present Day)

Now I had to get used to with the AI code editor so on present day I am using both Neovim and Antigravity(because it's free), I keep both open all the time. If i need to implement feature or add code which doesn't require much brain power and can be done very quickly (Creating UI components and styling), I use Antigravity and if I need to write or edit, I just press alt+tab (switch window).

For future I don't know, what AI editor I will use or how I use editor (may be we
don't need to write at all), but if I ever need to write or edit there is no
alternative for vim motions (it's the voice of my fingers). I even think all the
social media message typing box should have options for vim motions (it's crazy
but, come on bro I bet you also had this thought at least once).

Thank you for reading, may be not perfectly written but reflect all of my vim/neovim
journey.

**Links:**
- Github: [https://github.com/kushalchg][github]
- Dotfiles: [https://github.com/Kushalchg/dotfiles][dotfiles]
- X: [https://x.com/chapagainkushal][x]
- Linkedin: [https://www.linkedin.com/in/kushal-chapagain-1aa66419a/][linkedin]


[teej]: https://www.youtube.com/@teej_dv
[primagen]:   https://www.youtube.com/@ThePrimeTimeagen
[williamlin]: https://www.youtube.com/@tmwilliamlin168
[dotfiles]: https://github.com/Kushalchg/dotfiles
[nvchad]: https://nvchad.com/
[advert-of-neovim]: https://www.youtube.com/playlist?list=PLep05UYkc6wTyBe7kPjQFWVXTlhKeQejM
[golang]: https://go.dev/
[neovim]: https://neovim.io/
[williamlin-vimrc]: https://github.com/tmwilliamlin168/CP-YouTube/blob/master/.vimrc
[lua]: https://www.lua.org/
[vim]: https://www.vim.org/
[github]: https://github.com/kushalchg
[linkedin]: https://www.linkedin.com/in/kushal-chapagain-1aa66419a/
[x]: https://x.com/chapagainkushal
