# Maps
## ...and Data Viz
*What's where & why. Also, when. And how. And... you get the idea: maps are great.*

Click chart to go see this fullscreen, otherwise it's trash.
<div>
    <a href="https://plotly.com/~mcknn/6/?share_key=4brepK2JNzlUSkl143ji6K" target="_blank" title="Plot 6" style="display: block; text-align: center;"><img src="https://plotly.com/~mcknn/6.png?share_key=4brepK2JNzlUSkl143ji6K" alt="Plot 6" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plotly.com/404.png';" /></a>
</div>
![](https://github.com/mcknn/Portfolio/blob/master/Climagraph.ipynb)


Interactive version [here](https://public.flourish.studio/visualisation/3278148/). These images cut off the footer on export so the citations look wrong here. The bins are computed by pentacontile (yeah I just made that up. There's 50 bins in this map so it's not quintile binning...), so the color bar reveals a lot about the asymmetry of these data.
![](https://github.com/mcknn/Portfolio/blob/master/images/COVID19_Deaths_US.png)
Notice the much more even distribution here.
![](https://github.com/mcknn/Portfolio/blob/master/images/COVID19_Cases_US.png)

Now compare those distributions to [this](https://public.flourish.studio/visualisation/3281010).

![](https://github.com/mcknn/Portfolio/blob/master/images/COVID19_Deaths_per_Case.png)
<br><br/>
FL, NC and a few other southern states stand out with low ratios, so does Texas though it's harder to see because the outbreak has been much more localized there (it deserves its own map, for sure). Why? Well I know a statistician got fired in FL for refusing to suppress valid data. Go see her [FL COVID Dashboard](https://experience.arcgis.com/experience/7572b118dc3c48d885d1c643c195314e/). I live in NC and I know for sure that at least one county is supressing data. So I'd say it's unlikely that these states are just doing a great job of patient care. This is just bad data. By the way, here's the distribution (done in python, not flourish). Notice that using kde gives a nice smooth curve but the mode is at zero, so it implies some points are negative. But they're not of course. Looks a bit gamma to me though, might be worth trying to fit. <br><br/>
![](https://github.com/mcknn/Portfolio/blob/master/images/deaths_per_case_kde.png)

Here's a different, rather unusual look at the same dataset. Definitely go [look](https://public.flourish.studio/visualisation/3281744/) at the interactive version.
![](https://github.com/mcknn/Portfolio/blob/master/images/COVID19_by_st_cty_Treemap.png)<br><br/>

This one has to be viewed interactively [here](https://public.flourish.studio/visualisation/3288891). You just have to look at all the states. That said, this is an interesting relationship and probably worth digging into a bit more.<br><br/>
![](https://github.com/mcknn/Portfolio/blob/master/images/COVID19%20deaths%20per%20case%20vs%20YPPL.png)


Humor is how I get through tough times. Interesting relationship here, school lunches are a proxy for many things so I'm not surprised there's a bit of correlation, but the outliers are the real story. Down there at the bottom is Yakima county, WA. The outlier way up top is Menominee, WI. The y-axis is plotted on a log scale. Counties are color-coded by state. In the [interactive version](https://public.flourish.studio/visualisation/3281437) you can hover to see what's what.
![](https://github.com/mcknn/Portfolio/blob/master/images/Free_Lunch.png)

## Old Stuff

Here's my favorite. 
![](https://github.com/mcknn/Portfolio/blob/master/images/ncccmap.png)
<br><br/>
The fullscale .pdf is [here](https://github.com/mcknn/Portfolio/blob/master/pdf/GISIIProjectMcKann.pdf). The file is very large; it's a poster board, and you probably have to download it to view. There's also an accompanying [paper](https://github.com/mcknn/Portfolio/blob/master/pdf/TechrepFinalDraft.pdf) that I wrote for technical writing. It's quite long, but I really enjoyed this project.

## Some pieces from the above project.
![](https://github.com/mcknn/Portfolio/blob/master/images/changeIndexAlg.png)
![Orange 2015](https://github.com/mcknn/Portfolio/blob/master/images/orange15.jpg)
![Orange 2099](https://github.com/mcknn/Portfolio/blob/master/images/orange99.jpg)

<br></br>
### Thermal radiation. Unfinished, for sure. Can you guess the city?

![](https://github.com/mcknn/Portfolio/blob/master/images/heat.JPG)

<br></br>
### A landcover map for one of my GIS classes.
![](https://github.com/mcknn/Portfolio/blob/master/images/Lab2.jpg)


<br></br>
### Site suitability analysis. Hey, sometimes you just want to know where to go fishing.
![](https://github.com/mcknn/Portfolio/blob/master/images/Sturgfinal.jpg)


### Line of sight analysis. Not the prettiest, though.
![](https://github.com/mcknn/Portfolio/blob/master/images/Lab_3.jpg)




<br></br>
<br></br>
# Coding
*This is a mix of directed and independent projects, and no where close to comprehensive. Of course, most of the complete compilable code was for coursework. But I'm most proud of the side projects that I haven't yet had time (there's never enough time) to finish.*

Here's a [little C++ project](https://repl.it/@mcknn/KnightMove#main.cpp) I did for algorithms & data structures. It's about chess!

A [Java program](https://repl.it/@mcknn/ShrillSubtleFrontpage#Main.java) for text analysis I did for my OOP course. The emphasis here was on multithreading so we couldn't use threadsafe datastructures (So I made my own. I mean, why reinvent the jetski when you can just reinvent the wheel?). Why this constraint? Ours is not to question why, ours is just to do or... well, get a terrible grade.

And [here](https://repl.it/@mcknn/CMPSC-465-Project-6#main.cpp) you can find a short little dynamic programming solution to a problem which keeps exactly no one up at night (except folks in algorithms & data structures, perhaps!). C++.

[Implementation](https://repl.it/@mcknn/CRT-implementation#CRT.java) of the chinese remainder theorem to solve a particulary obscure problem (written in Java). This is unfinished because I thought of a simpler solution (if I had a dollar for every time that happened, I would... well, I'd have more dollars).

This is an ML quant finance project in python I'm working on in the quantopian framework. It basically picks the most predictive signals for a given symbol and then places confidence-weighted trades. Really is a signal processing problem, and very hard to do well. The code [here](https://repl.it/@mcknn/UsableUnselfishCookie#main.py) is outdated but you can get the general idea. This certainly won't compile outside quantopian.



<br></br>
<br></br>
# Technical & Research Writing
*I like writing, though I have not had much time for it the past few years (engineering programs continue to live up to their reputation as being... intensive).*

My favorite little project is [this](https://github.com/mcknn/Portfolio/blob/master/pdf/Scientific%20theory.pdf) little handout on the scientific theory. Not because it took a lot of effort or that it's particularly good, but because my professor tried to give me a 0 on it -- he said it was too good to have been put together by a student. What a compliment. I think he grudgingly gave me a B in the end.

[Here](https://github.com/mcknn/Portfolio/blob/master/pdf/TechrepFinalDraft.pdf) is a very long research paper on climate change resiliency in North Carolina (also linked above under maps). I got inspired to do this when I noticed that while there is extensive climate resiliency research on a regional-and-above scale, only very limited information is available at the local level, particularly in locales where conservative politics dominate. Unfortunately, it is exactly those sorts of communities that are and will continue to see some of the most severe consequences of climate change. To get climate projections at the county level was a bit of an ordeal in terms of data preprocessing, and I had to get rather creative to downscale regional-resolution climate model data without completely losing predictive power. It was good fun.

A research paper on Thorstein Veblen and development economics can be found [here](https://github.com/mcknn/Portfolio/blob/master/pdf/McKann_final.pdf).

Another one, this time on [ethics](https://github.com/mcknn/Portfolio/blob/master/pdf/EthicsPaperMcKann.pdf). I wrote this for a chemistry lab, of all things. As if there wasn't already plenty to do!

