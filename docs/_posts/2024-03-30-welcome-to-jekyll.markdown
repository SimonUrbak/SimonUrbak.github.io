---
layout: post
title:  "Understanding the Housing Market of Copenhagen - Exam Project - s194655, s194361"
date:   2024-05-07 12:13:56 +0100
categories: jekyll update
---
In this project we will take a look at the Copenhagen residential prices from 2000 to 2024. The aim is to gain insight into how the housing prices have changed over time and across space. Notably some important events are contained within our temporal period, mainly the 2008 economic crash and the covid-19 pandemic. 


As far as we know, a comprehensive dataset of all housing sales from 2000 - 2024 is not publicly available. To remedy this we have opted to scrape our data from "boligsiden.dk". Scraping from this side gives us access to variables from Bygnings og Bolig-registeret(BBR). In total we have gathered 2889191 recorded sales from the municipalities of Copenhagen and Frederiksberg. For each recorded sale we obtain 5 variables: longitude, latitude, neighbourhood, date and squaremeterprice. Furthermore we have also obtained some shapefiles describing the neighbourhood borders, in order to produce visualizations that highlight the price change in the different regions of the city

Upon first inspection, it seems that there are some extreme outliers in the data.


{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

<iframe src="/Luksus.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
