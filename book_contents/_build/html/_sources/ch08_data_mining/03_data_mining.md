# Mining Social Media Data

Data mining is the process of taking a set of data and trying to learn new things from it.

For example, social media data about who you are friends with might be [used to infer your sexual orientation](https://www.vice.com/en/article/gvydky/your-friends-online-connections-can-reveal-your-sexual-orientation). Social media data might also be used to infer people's:
- Race
- Political leanings
- Interests
- Susceptibility to financial scams
- Being prone to addiction (e.g., gambling)

Additionally groups keep trying to re-invent old debunked psuedo-scientific (and racist) methods of judging people based on facial features (size of nose, chin, forehead, etc.), but [now using artificial intelligence](https://www.americanscientist.org/article/the-dark-past-of-algorithms-that-associate-appearance-and-criminality).

Social media data can also be used to infer information about larger social trends like [the spread of misinformation](https://www.science.org/content/article/researchers-are-tracking-another-epidemic-too-misinformation).

One particularly striking example of an attempt to infer information from seemingly unconnected data was someone noticing that the number of people sick with COVID-19 correlated with how many people were leaving bad reviews of Yankee Candles saying "they don't have any scent" (note: COVID-19 can cause a loss of the ability to smell):

```{figure} covid_candles.png
---
name: covid_candles_fig
width: 300px
alt: "Tweet by eleanor (@zomsllama). Tweet says, \"blue line: daily COVID cases in the USA. red line: bad reviews of Yankee Candles on Amazon saying 'they don't have any scent'. sources: google and [sic].\" The tweet has a graph from 8 Apr to 13 Nov, showing a blue line that goes up and down noisily but with two big peaks. A much smoother red line has two big peaks lining up the blue big peaks."
---
Twitter user @zomsllama [pointing out the correlation of COVID cases and candle reviews complaining of no scent](https://twitter.com/zornsllama/status/147357550878495539).
```

## Spurious Correlations

One thing to note in the above case of candle reviews and COVID is that just because something appears to be correlated, doesn't mean that it is connected in the way it looks like. In the above, the correlation might be due mostly to people buying and reviewing candles in the fall, and diseases, like COVID, spreading most during the fall.

It turns out if you look at a lot of data, it is easy to discover [spurious correlations](https://en.wikipedia.org/wiki/Spurious_relationship) where two things look like they are related, but actually aren't. Instead the appearance of being related may be due to chance or some other cause. For example:

```{figure} spurious_divorce_margarine.png
---
name: spurious_divorce_margarine_fig
alt: "Chart of Divorce Rate in Maine compared with Per capita consumption of margarine, which correlates 99.26%. The graph shows lines for divorce and margarine from 2000 to 2009. Both lines generally decline, but the places where they decline steeper or shallow out line up."
---
An example spurious correlation from [Tyler Vigen's collection of Spurious Correlations](https://www.tylervigen.com/spurious-correlations)
```

By looking at enough data in enough different ways, you can find evidence for pretty much any conclusion you want to. This is because sometimes different pieces of data line up coincidentally (coincidences happen), and if you try enough combinations, you can find the coincidence that lines up with your conclusion.

If you want to explore the difficulty of inferring trends from data, the website [fivethirtyeight.com](https://fivethirtyeight.com/) has an interactive feature called "[Hack Your Way To Scientific Glory](https://projects.fivethirtyeight.com/p-hacking/)" where by changing how you measure the US economy and how you measure what political party is in power in the US, you can "prove" that either Democrats or Republicans are better for the economy. Fivethirtyeight has a longer article on this called "[Science Isn’t Broken: It’s just a hell of a lot harder than we give it credit for.](https://fivethirtyeight.com/features/science-isnt-broken/)"
