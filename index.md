## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/NolanJolicoeur/Official-DSA/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Fantasy Football Overview
```Markdown

* Fantasy Football is a game in which people face off head to head with fictional teams they created. 
* These teams are made up of real NFL athletes and the scoring system is based off actual NFL stats. 
  * Passing: 
    * Touchdown = 4 points
    * Yard = 0.04 points
  * Rushing: 
    * Touchdown = 6 points 
    * Yard = 0.1 points
  * Recieving: 
    * Touchdown = 6 points 
    * 1 Yard = 0.1 points 
    * Catch = 1 point

![image1](https://user-images.githubusercontent.com/89327000/144916234-68213361-4e0b-4cc5-9e8b-2ffe82a776ca.png)



```
### Test 1 - Do Fantasy Points Relate to Wins?
```Markdown
* For this first test I summed the total fantasy points scored by each team throughout the season. 
![image2](![image2](https://user-images.githubusercontent.com/89327000/144916715-9307e68f-7dba-4655-ba24-22f017b1f426.png)
* Based on this graph, there seems to be a positive relationship between fantasy points and wins. 
* When using the Pearson correlation formula: 
     * Correlation = 0.7735
     * The 95 percent confidence interval is from 0.5817 to 0.8838. 
* There definitely seems to be a correlation between the two variables. 
* To try and find a stronger relationship, I next tested fantasy points in relation to points scored. 
![image3](https://user-images.githubusercontent.com/89327000/144917574-e3a5b38e-7f49-439e-99cf-9d4495571302.png)
* This graph also has a positive relationship. 
* When using the Pearson correlation formula: 
     * Correlation = 0.8830
     * The 95 percent confidence interval is from 0.7720 to 0.9417. 
* The correlation between fantasy points and points for is stronger than the correlation between fantasy points and wins. 
* This means we can conclude that team fantasy points are a better predictor of points scored than wins. 


```


For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NolanJolicoeur/Official-DSA/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
