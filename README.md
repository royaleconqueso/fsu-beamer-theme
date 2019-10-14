# Florida State University Beamer Theme for LaTeX

Hi. This is a FSU theme for the LaTeX package Beamer. See the .sty for credits. What it does is make a really nice slide presentation using 
documentclass{beamer} using LaTeX, much like you might be used to in Powerpoint. Here's a screenshot from one of my lectures:

Now, I'm going to assume you're already using beamer to make presentation slides using LaTeX. If not, you'll need to set that up. Here's what I do:

```
brock@amidala:~$ sudo apt-get install latex-beamer
```

YMMV. Now what you'll need are three files. One is called beamerthemeFSUTheme.sty, which either goes in your tex tree, or in the directory of the 
document you're creating. Bit of advice: put it in your tree, and run texhash. You'll also need something called sealfsu.pdf. that makes the little 
seal in the top left corner. The one I use gives a overfull error, but it compiles just fine. If you prefer a smaller seal that fits the box better, 
you can make it from the included enormous jpg.

You're also gonna need your .tex file. I've included the template that I use, as well as an example template from one of my ethics lectures. I'll also 
include a bit of a tutorial soon. I'll put it here.

Get all three relevant files here.

I hope this is helpful.
