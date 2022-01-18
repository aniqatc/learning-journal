# 100 Days of Code R1: Daily Log

_Welcome to my **daily progress log**!_

_This log is slightly **different** from my [blog's topic log](https://www.aniqa.io/r1-topic-log/) or [my GitHub topic log](https://github.com/aniqatc/100-days-of-code/blob/main/R1-Topic-Log.md) that I've been contributing to recently. The topic log includes standalone blog posts that include my detailed progress updates on what I've learned, challenges I've faced, projects I'm working on, and the list of resources that were used during my learning over the course of a few days for a **single** topic. I started writing up these 'topic' posts because I didn't want to scatter useful information relating to a single topic across several different posts for several different days. Instead, I grouped the consecutive days together and wrote about my learning experience based on the specified topic (and sub-topics). [Those posts](https://www.aniqa.io/r1-topic-log/) ended up being over 1500 - 2000 words long each so they couldn't be contained into a single log, otherwise, you'd be scrolling forever._

_For my **daily log**, however, it will be less formal and more simple! I'll be using this daily log **to document my daily progress** regardless of the topic that I'm on - basically how everyone else does it. For those quick, short updates, you can visit this repo (⭐️ it to stay updated); or if you fancy more rich content, then visit the [blog version for my daily updates](https://www.aniqa.io/r1-daily-log/)._

---

### Before + Day 0

I wrote some blog posts about some of the fundamentals I learned & included the resources I used to learn them:

- [Prior to #100DaysOfCode: Research & Plan](https://www.aniqa.io/prior-r1/)
- [Topic 0 of #100DaysOfCode: Web & Internet Protocols](https://www.aniqa.io/r1-topic-0/)
- [Topic 1 of #100DaysOfCode: Bash/zsh Command Line](https://www.aniqa.io/r1-topic-1/)

---

### Day 1

I've spent the past few days learning about Google's Chrome Developer Tools and practiced using almost all of the main features on [my website](https://www.aniqa.io). It was honestly lots of fun messing around with the code, learning more about the security and network protocols that my website is using (which also ties into my understanding of [Web & Internet Protocols](https://www.aniqa.io/r1-topic-0/)), and how to find and fix issues with my code. *There were times that I got lost just using the tool, especially the Element, Console, and Network panels.*

I have so far gone over the following panels: Application, Lighthouse, Adblock, Element, Network, Sources, Security, Console, and customizing Settings. I'm hoping to complete my review of the Memory and Performance tab tomorrow. After doing so, I'll write up my **Topic 2: Chrome Developer Tools** blog post before moving onto my next section of learning.

Side note: I switched my notes over to Nota (a markdown editor) which will make it easier and faster to publish content to my blog more frequently. I'm now working on transforming my blog into a digital garden.

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/nota.gif"></p>

---

### Day 2

I've decided to take a short break from tutorial learning and blogging. Although I have a blog hosted on Ghost Pro that works perfectly fine, I still feel somewhat limited in sharing content and editing my theme. In addition to that, there isn't really a theme that fits my idea of simplicity with most themes being media-rich, and I'm not exactly ready to create my own. _But that doesn't mean I have to settle_ - I want a true **digital garden**. A place that I can share high-quality pieces of writing but also, share my unedited thoughts and notes to portray a _true_ #LearningInPublic journey. I want it to be content-focused and absent of images that take up space. I also want to have full flexibility to edit the codebase whenever I learn something new, like my own personal playground to test out new languages and frameworks.

So, today, I learned about Static Site Generators (SSGs) and set up two different, minimal and content-focused themes:

- ▲ Hugo theme deployed on Vercel
- ◉ Gatsby theme deployed on Gatsby Cloud

*I also learned how to use Digital Ocean and Netlify to deploy websites, however, I'll be sticking to the above for now.*

I'm still deciding on which duo I prefer so I'll be playing around with both to see what fits my needs better! Switching over to an SSG from Ghost will be my project for the next few days.

---

### Day 3

I've realized that Hugo is easier to edit and customize than Gatsby. This is likely because of my limited coding knowledge (basic HTML, CSS) but it's definitely the SSG I'd recommend to newbies. That being said, Gatsby just has so much more that you can do with it - with [countless plugins](https://www.gatsbyjs.com/plugins) so that you don't have to create your own. It's definitely been far more tricky to edit since I barely know JavaScript, let alone React. But I just can't let go of the customization that comes with using Gatsby even if Hugo is easier to maneuver. **So, I've decided to stick to Gatsby!**

Luckily, combining Gatsby's very thorough documentation, individual plugin READMEs, my limited but sufficient coding knowledge, and making connections between theme files is proving to be enough to customize the starter-theme to my liking! 

Also, worth noting, I added ![wakatime](https://wakatime.com/badge/user/c1c1c183-d190-42bd-ae4f-09370e6fbbc6.svg) to VSCode to record my time spent coding! 

---

### Day 4

I'm finally adding the final touches to my Gatsby theme so I'll be back to learning from tutorials & blogging my journey again soon!

Today, I used open-source React icons called **[react-feather](https://feathericons.com/)** to add social media icons to my navigation bar and share buttons to all my posts. I installed the icons using npm on my Terminal. From there it was easy - I declared the usage of these icons by 'importing' the ones I'll be using and then, set variables for the icon size and line thickness. To further customize the icons, I used ':hover' with color and transform in a separate .css file.

I'm pleased with the final results:
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/react-feather-icons.gif"></p>

In addition to the icons, I also learned about dark mode practices and changed my dark mode theme colors accordingly!

---

### Day 5

I discovered a small JavaScript library called [Rough Notation](https://roughnotation.com) that allowed me to add customizable and animated annotations on webpages. The annotations can be customized by color, size, padding and animation order, duration, and delays.

I tested it out on my new blog theme by injecting it into a .mdx file! It was easy to implement and a fun library to play around with. 

Here's what it looks like in my light mode (slowed down by 50%):
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/rough-notation-light.gif"></p>

Here's what it looks like in my dark mode (slowed down by 50%):
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/rough-notation-dark.gif"></p>

---

### Day 6

I've finally completed my new blog theme using Gatsby which is currently deployed on Vercel. While all the stylistic and layout choices have been decided in the previous days, I spent most of today transferring over my previous blog content from the Ghost platform to Markdown content for my new blog. 

It took some time to get all the blog posts formatted, especially because I faced some bumps along the way. For example:
- I needed to add import `react-twitter-widgets` into some of my `.mdx` files that hold my blog posts to get relevent tweets to show up among my content
- I needed to add support for `.gif` files by installing an additional Gatsby plugin which conflicted with my existing plugins so I had to find a fix for that. Once I figured out the best combination of plugins, I updated that information within the my `gatsby.config.js` file.

Regardless, I'm honestly excited whenever I bump into an issue - it's exciting to fix! Lastly, I added Google Analytics support by adding in `gatsby-plugin-google-gtag` to my `gatsby.config.js` file. 

*Side note: I might not be using Google Analytics for long - I discovered [Umami](https://umami.is/) today and love everything about it (from the UI to the fact it's free and open-source and provides such beautiful infographics). I would've already implemented it honestly but it's definitely a little more complicated than Google Analytics to install + I've taken too long of a break from my syllabus to build a new blog so I'll have to come back to it later.*
