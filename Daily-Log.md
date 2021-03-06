# Daily Log

_Welcome to my **daily progress log**!_

_This log is slightly **different** from my [blog's topic log](https://www.aniqa.io/r1-topic-log/) or [my GitHub topic log](https://github.com/aniqatc/learning-journal/blob/main/Topic-Log.md) that I've been contributing to recently. The topic log includes standalone blog posts that include my detailed progress updates on what I've learned, challenges I've faced, projects I'm working on, and the list of resources that were used during my learning over the course of a few days for a **single** topic._

_For my **daily log**, however, it will be less formal and more simple! I'll be using this daily log **to document my daily progress** regardless of the topic that I'm on - basically how everyone else does it. For those quick, short updates, you can visit this repo (⭐️ it to stay updated); or if you fancy more rich content, then visit the [blog version for my daily updates](https://www.aniqa.io/r1-daily-log/)._

### Before + Day 0

I wrote some blog posts about some of the fundamentals I learned & included the resources I used to learn them:

- [Prior to #100DaysOfCode: Research & Plan](https://www.aniqa.io/prior-r1/)
- [Topic 0 of #100DaysOfCode: Web & Internet Protocols](https://www.aniqa.io/r1-topic-0/)
- [Topic 1 of #100DaysOfCode: Bash/zsh Command Line](https://www.aniqa.io/r1-topic-1/)
  

<details><summary><b>Day 1: Navigating Chrome Developer Tools & Taking Notes</b></summary>
  
### Day 1

I've spent the past few days learning about Google's Chrome Developer Tools and practiced using almost all of the main features on [my website](https://www.aniqa.io). It was honestly lots of fun messing around with the code, learning more about the security and network protocols that my website is using (which also ties into my understanding of [Web & Internet Protocols](https://www.aniqa.io/r1-topic-0/)), and how to find and fix issues with my code. *There were times that I got lost just using the tool, especially the Element, Console, and Network panels.*

I have so far gone over the following panels: Application, Lighthouse, Adblock, Element, Network, Sources, Security, Console, and customizing Settings. I'm hoping to complete my review of the Memory and Performance tab tomorrow. After doing so, I'll write up my **Topic 2: Chrome Developer Tools** blog post before moving onto my next section of learning.

Side note: I switched my notes over to Nota (a markdown editor) which will make it easier and faster to publish content to my blog more frequently. I'm now working on transforming my blog into a digital garden.

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/nota.gif"></p>
  
</details>

<details><summary><b>Day 2: Switching Ghost Blog to Static Site Generators</b></summary>

### Day 2

I've decided to take a short break from tutorial learning and blogging. Although I have a blog hosted on Ghost Pro that works perfectly fine, I still feel somewhat limited in sharing content and editing my theme. In addition to that, there isn't really a theme that fits my idea of simplicity with most themes being media-rich, and I'm not exactly ready to create my own. _But that doesn't mean I have to settle_ - I want a true **digital garden**. A place that I can share high-quality pieces of writing but also, share my unedited thoughts and notes to portray a _true_ #LearningInPublic journey. I want it to be content-focused and absent of images that take up space. I also want to have full flexibility to edit the codebase whenever I learn something new, like my own personal playground to test out new languages and frameworks.

So, today, I learned about Static Site Generators (SSGs) and set up two different, minimal and content-focused themes:

- ▲ Hugo theme deployed on Vercel
- ◉ Gatsby theme deployed on Gatsby Cloud

*I also learned how to use Digital Ocean and Netlify to deploy websites, however, I'll be sticking to the above for now.*

I'm still deciding on which duo I prefer so I'll be playing around with both to see what fits my needs better! Switching over to an SSG from Ghost will be my project for the next few days.

  </details>
  
<details><summary><b>Day 3: Officially Building With Gatsby</b></summary>

### Day 3

I've realized that Hugo is easier to edit and customize than Gatsby. This is likely because of my limited coding knowledge (basic HTML, CSS) but it's definitely the SSG I'd recommend to newbies. That being said, Gatsby just has so much more that you can do with it - with [countless plugins](https://www.gatsbyjs.com/plugins) so that you don't have to create your own. It's definitely been far more tricky to edit since I barely know JavaScript, let alone React. But I just can't let go of the customization that comes with using Gatsby even if Hugo is easier to maneuver. **So, I've decided to stick to Gatsby!**

Luckily, combining Gatsby's very thorough documentation, individual plugin READMEs, my limited but sufficient coding knowledge, and making connections between theme files is proving to be enough to customize the starter-theme to my liking! 

Also, worth noting, I added ![wakatime](https://wakatime.com/badge/user/c1c1c183-d190-42bd-ae4f-09370e6fbbc6.svg) to VSCode to record my time spent coding! 

  </details>
  
<details><summary><b>Day 4: Adding React Feather Icons</b></summary>

### Day 4

I'm finally adding the final touches to my Gatsby theme so I'll be back to learning from tutorials & blogging my journey again soon!

Today, I used open-source [React icons](https://feathericons.com/) called `react-feather` to add social media icons to my navigation bar and share buttons to all my posts. I installed the icons using `npm` on my Terminal. From there it was easy - I declared the usage of these icons by 'importing' the ones I'll be using and then, set variables for the icon size and line thickness. To further customize the icons, I used `:hover` with color and transform in a separate `.css` file.

I'm pleased with the final results:
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/react-feather-icons.gif"></p>

In addition to the icons, I also learned about dark mode practices and changed my dark mode theme colors accordingly!

  </details>
  
<details><summary><b>Day 5: Using Rough Notation</b></summary>

### Day 5

I discovered a small JavaScript library called [Rough Notation](https://roughnotation.com) that allowed me to add customizable and animated annotations on webpages. The annotations can be customized by color, size, padding and animation order, duration, and delays.

I tested it out on my new blog theme by injecting it into a `.mdx` file! It was easy to implement and a fun library to play around with. 

Here's what it looks like in my light mode (slowed down by 50%):
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/rough-notation-light.gif"></p>

Here's what it looks like in my dark mode (slowed down by 50%):
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/rough-notation-dark.gif"></p>

  </details>
  
<details><summary><b>Day 6: Adding More Functionality to Gatsby Site Using Gatsby Plugins</b></summary>

### Day 6

I've finally completed my new blog theme using Gatsby which is currently deployed on Vercel. While all the stylistic and layout choices have been decided in the previous days, I spent most of today transferring over my previous blog content from the Ghost platform to Markdown content for my new blog. 

It took some time to get all the blog posts formatted, especially because I faced some bumps along the way. For example:
- I needed to add import `react-twitter-widgets` into some of my `.mdx` files that hold my blog posts to get relevant tweets to show up among my content
- I needed to add support for `.gif` files by installing an additional Gatsby plugin which conflicted with my existing plugins so I had to find a fix for that. Once I figured out the best combination of plugins, I updated that information within the my `gatsby.config.js` file.

Regardless, I'm honestly excited whenever I bump into an issue - it's exciting to fix! Lastly, I added Google Analytics support by adding in `gatsby-plugin-google-gtag` to my `gatsby.config.js` file. 

*Side note: I might not be using Google Analytics for long - I discovered [Umami](https://umami.is/) today and love everything about it (from the UI to the fact it's free and open-source and provides such beautiful infographics). I would've already implemented it honestly but it's definitely a little more complicated than Google Analytics to install + I've taken too long of a break from my syllabus to build a new blog so I'll have to come back to it later.*

  </details>
  
<details><summary><b>Day 7: Adding Progressive Web App (PWA) Support</b></summary>

### Day 7

As a final step to completing my blog *(who am I kidding - I can't stop messing with it)*, I turned my ordinary Gatsby blog into a Progressive Web App (PWA). PWAs provide users with an option to install a website as an application to their computer or mobile device using any browser. This feature is made possible with the use of service worker(s) and a web manifest. *It really works!* 

For example, on my Google Chrome browser, the input bar has an additional icon and upon clicking it, an option comes up to install the website. *FYI, many well-known websites have this feature, including Twitter!*

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/install-pwa-aniqa.png"></p>

Once installed, my website can be accessed like any other native application on your computer!

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/in-dock-aniqa.png"></p>

The same rules apply even on mobile! The website can be added to your Home Screen by going into your browser options and simply clicking the relevant option *(for Safari on my iPhone, all I had to click was 'Add to Home Screen')*. You can then access the blog straight from your Home Screen, independent of a browser! 

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/mobile-pwa.jpeg"></p>

  </details>
  
<details><summary><b>Day 8: Adding Mobile-Responsiveness to Images & Columned Content</b></summary>

### Day 8

I noticed an annoying bug on my website when accessed through mobile: the images were not resizing down to a smaller size on mobile. Since I've always used Wordpress and Ghost in the past, I never had to think about making my images responsive to different screen sizes since it was always optimized in themes I bought.

For the fix, I learned the CSS property, `max-width:100%`. Simply adding the `style="max-width:100%"` to all my images, they resized to fit the screen no matter how small or large. However, having to add the property inline was annoying and I may not remember to include it every time that I post, so I added the property to my main stylesheet making sure that the style applies to any `<img>` tag.

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/max-width.gif"></p>

Additionally, I learned how to use `grid-template-column` - *another CSS property* to create columns in my content.

  </details>
  
<details><summary><b>Day 9: Adding Support for .md Files & Adding <code>react-accessible-accordion</code></b></summary>

### Day 9

I added a new post template to my blog for notes! While all my blog posts are written in `.mdx` files using VS Code, my notes are written in `.md` using a simple Markdown editor. So, I needed a separate template that would be compatible with converting `.md` files. After doing so, I tested to see if it works and if I'm successfully able to create custom slugs for each note file -- and fortunately, it worked!

I also wanted a separate note listing page and I opted to use `react-accessible-accordion` which allows for collapsible rows of information. For my usage, I wanted to use the Accordion styled rows to link to my notes and make them separated by subjects.

Here's what it's currently looking like:

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/accordion.gif"></p>

  </details>
  
<details><summary><b>Day 10 + 11: Building A Knowledge Base for Digital Garden</b></summary>

### Day 10 + 11

Ever since I discovered 'Second-Brain-' and Digital Garden-styled personal websites, I've really wanted one of my own. Now, I'm not particularly ready to create a theme from scratch and while there are some great themes out there, I simply do not connect to any of the available digital garden themes. To be frank, I'd only be satisfied with something similar to <a href="https://brianlovin.com">Brian Lovin's website</a>. And again, I'm just not there yet. So I'm settling and trying to customize my current blog design as much as possible while still keeping it simple. It doesn't have everything I'd like but it gets the job done.

That being said, I've been building my own 'second-brain' in my private, digital notebook and I didn't even know it. The only thing is - I never intended on anyone seeing it so it might have parts that literally no one except me would understand. But I really want to immerse in learning and building in public and creating my own second-brain. So, the past few days (technically, more than Day 10 & 11 but whatever), I've been editing my notes little-by-little so that it's readable for others.

I'm really excited to share these notes - I really think it'll be helpful to others!

  </details>
  
<details><summary><b>Day 12: Adding Gradient Hover Over Links + Using <code>:not()</code></b></summary>

### Day 12

I added a new style to all the links on my website. There's a thin gradient underline on all of the links on my site and upon hover, the link is highlighted with a beautiful light gradient. While most of my site is quite simple (in my opinion), I thought the addition of this small stylistic detail might add a little more personality. 

Here's what it looks like upon hover in light mode:

<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/link-hover-light.gif"></p>

Here's what it looks like upon hover in dark mode:
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/link-hover-dark.gif"></p>

However, I did face an issue with the hover style effecting icon and image links, like my avatar in my site's header. 
<p align="center"><img src="https://github.com/aniqatc/100-days-of-code/blob/main/Assets/link-hover-issue.gif"></p>

To combat this particular issue, I learned of a new CSS property that involves using `:not( )`. For example, originally, I was selecting all links in my CSS file by applying the gradient and hover style to `a` to select all links -- this would select everything, including the images and icons that are linked to a different page. So, the `:not( )` property allows me to identify the classes that I'd like to exclude from being effected by the global `a` style that I'm implementing. For example, the syntax would be as follows: 
```
a:not(except-header-link) { 
include styles here
}
```

This solved the issue! 

  </details>
  
<details><summary><b>Day 13 + 14: Adding Separate Note Template & Section for Note Listings</b></summary>

### Day 13 + 14

On Day 9 *(mentioned above)*, I used `react-accessible-accordion` to create a listing page for all my notes. I realized that I'd rather utilize the Accordion design for shorter pieces of information like a *"Today I Learned" code snippet page*. 

However, for my note pages, I added a filesystem-style listing page instead. I feel that this is a better way to organize notes, especially as my notes grow into the hundreds and possibly, thousands. It provides an option to view the notes as if you're navigating my personal Finder (file manager).

Here's a .gif of how the note-system is currently organized:

<p align="center"><img src="https://github.com/aniqatc/learning-journal/blob/main/Assets/wiki-system.gif?raw=true"></p>

I've also removed the Subscribe Form from the footer since it would show up on every single page - now, it only shows up on the Homepage. All other pages have a new footer design that works as a secondary menu to my most important links *(which includes a quick path back to blog listings, wiki entries, TIL log, master list of resources, my twitter and my email list sign-up)* so that users do not have to scroll all the way back up to the beginning of the page to navigate my website. The icons I utilized for the secondary footer are the same as the icons used throughout the rest of my website: `react-feather`.

<p align="center"><img src="https://github.com/aniqatc/learning-journal/blob/main/Assets/secondary-footer.png?raw=true"></p>

  </details>
  
<details><summary><b>Day 15: CSS Styling Subscribe Form, Wiki Section, Code Syntax + Added Work-In-Progress Banner</b></summary>

### Day 15

My website has been a work-in-progress for about a month now. So, although I'm nearing the end of any major changes I have planned for this version of my website, I felt that I should indicate to any visitors that my website is still under construction:

<p align="center"><img src="https://github.com/aniqatc/learning-journal/blob/main/Assets/site-under-construction.png?raw=true"></p>

Majority of my website is complete and functional with content available in the blog section. However, there is some sample content in certain corners of my website like the **Today I Learned (/til)** or **Wiki (/wiki)** sections. So, I made sure to specify that in the banner so that I don't completely deter every visitor away with a bunch of *lorem ipsum* pages. I should've created such a banner a while ago but I thought I'd be done by now. Boy, was I wrong - I know very little coding so creating this website has thrown me into a crash course on all things Gatsbyjs & web development. Anyways, hopefully I won't need to keep the *under construction* banner up for too long.

**Additional changes that I made today:**

**1. Subscribe Form:**
  -  Edited the CSS to make it more responsive, specifically for smaller phones
  -  Edited the overall style of the Subscription Form to make it stand out a little more (considering the fact that most of my site is quite simple)
<p align="center"><img src="https://github.com/aniqatc/learning-journal/blob/main/Assets/subscribe-form.png?raw=true"></p>

**2. Wiki:**
  - Added custom styling to the Wiki page
  - Utilized `react-feather` icons for the Wiki-system

**3. Code Syntax Highlighting:**
  - While the default syles are quite nice, I made some edits to the code snippet styling to make sure that the color scheme matches the rest of my website
  - Added styles for inline code

  </details>
  
<details><summary><b>Day 16: Using Gatsby's GraphQL Explorer to Customize Wiki Section</b></summary>

### Day 16

Today was a big day in terms of understanding the possibilities of building with Gatsby. Although I've spent the past month playing around with Gatsby, I have tried my best to steer clear of **GraphQL**. I have been intimidated by it especially with my lack of experience so far. I just wanted my own website up-and-running with some level of organization and I was able to do a lot without touching too much GraphQL queries besides the ones that are already built in my code. But I've realized I have way too much fun playing around with coding and learning along the way so I've just been falling in deeper and deeper with the Gatsby system.

Luckily, I've been able to solve a lot of problems on my own. But now that I wanted my own **wiki** section in addition to my existing blog function - things were getting complicated and I didn't care because I want what I want. So, it was time to use GraphQL.

Gatsby has a GraphQL explorer that can be accessed via `http://localhost:8000/___graphql` and can be accessed every time that you host your site on localhost:

<p align="center"><img src="https://github.com/aniqatc/learning-journal/blob/main/Assets/gatsby-graphql.png?raw=true"></p>

Through this IDE, it's actually **EASY** as hell to create queries that can be used to pull data. Now, I won't go over it in detail here (cause this is just my journal and I doubt anyone reads this) but I'll share what I wanted to accomplish: **to pull frontmatter data from my individual wiki entries to use in SEO-optimization, content organization AND adding detail to the template**.

<p align="center"><img src="https://github.com/aniqatc/learning-journal/blob/main/Assets/graphql-example.png?raw=true"></p>

So, I used Graphql to create queries specifically for data inputted into the frontmatter of my wikis. Since my wiki section is completely new and unoptimized, it doesn't have any tagging system or organization in place or built-in SEO. In fact, the title doesn't even get queried and pulled into my note template. So, I used the IDE to identify the following frontmatter: title, topic, stage, date and description.

Then, I added and identified the Graphql queries (in the appropriate syntax) into my wiki templates so that I could now have each wiki entry automatically display the title, topic, stage, and date at the beginning of each entry like a blog post! 

For SEO, I used `react-helmet` within my wiki template so that it can pull title and description directly from the frontmatter of each wiki entry to use as SEO metadata. I confirmed that the SEO metadata was working by going into Chrome Developer Tools and checking for all the `<meta>` tags in between the `<head>` section of my code and saw that the browser was correctly identifying the metadata. Previously, it was showing general website metadata and not post-specific information.

  </details>
  
<details><summary><b>Day 17: CSS Styling for Blog Header, Wiki Note Header + Added Tagging System for Wiki + Create Syllabus Page</b></summary>

### Day 17

**I'm a few commits away from completing my digital garden!** Today, I got a lot of styling and organization done! I'm quite satisfied with how everything is starting to look and function. Here's what I did **(hint: it involves lots of CSS)**:


- I changed the styling of the header for my [blog posts](https://www.aniqa.io/full-stack-development-path-goals), (previously was aligned to the left, plain text styling):

<p align="center"><img src="https://raw.githubusercontent.com/aniqatc/v1-aniqa/master/static/blog-post-design.gif"></p>


- I added frontmatter data (title, date, stage, topic, and author) to my [wiki note header section](https://www.aniqa.io/wiki/binary/bits-and-bytes) (previously had nothing except body of text):
<p align="center"><img src="https://raw.githubusercontent.com/aniqatc/v1-aniqa/master/static/wiki-note-design.gif"></p>


- I added styling to the details that were pulled into the wiki template. Additionally, to clarify, the 'stage' value represents whether a note is a '🌱 Seedling' which is an incomplete note or '🪴 Evergreen' for notes that likely won't have any information added to it anymore.
<p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/wiki-details.png"></p>


- Added a **[syllabus page](https://www.aniqa.io/resources)** to include information about resources I use to learn and the topics I'm learning just like a syllabus
- Added `react-accessible-accordion` and `react-tabs` to the **syllabus page**
- Edited the styling of both the `react-accessible-accordion` and `react-tabs` to fit the styling of the rest of my website:
<p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/react-tabs.gif"></p>


  </details>
  
<details><summary><b>Day 18: Build Syllabus Page With <code>react-accessible-accordion</code> & <code>react-tabs</code></b></summary>

### Day 18

While all of the stylistic changes are mostly complete for my personal website, I still need to fill certain pages with content. A few weeks back, when I first started this journey to learn web development, I created my own syllabus of sorts. I did serious research on the best resources, how to learn effectively, and the topics I'd need to go over to be a successful developer. I ended up building a long checklist of topics that I'm now using as my guide. I don't particularly think that I need to master every single topic inside-and-out because that would quite literally take a lifetime, but I plan on at least getting an introductory-to-intermediate understanding on most topics. 

I've gotten a lot of requests to share the syllabus, hence, I created my <a href="https://www.aniqa.io/syllabus">Syllabus</a> page. On the syllabus page, I'm using `react-accessible-accordion` and `react-tabs` to organize two list: **Checklist** and **Resources**.

- `react-tabs` was utilized to separate the information under **Checklist** and **Resources**:
<p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/tab-syllabus.gif"></p>

- `react-accessible-accordion` was used to separate the lists of resources and lists of topics by subject so that it's easier to navigate to the information you need:
<p align="center"><img src="/Assets/detail-syllabus.gif"></p>

So far, I've added the topics I've already completed my learning for. I'll be adding the rest in the coming days (along with the content for my <a href="https://www.aniqa.io/wiki">Wiki section</a>).

  </details>
  
   
  <details><summary><b>Day 19 + 20: Add Content to Resource & Checklist Sections on Syllabus</b></summary>
    
### Day 19 + 20
    
As mentioned in Day 17 & 18, I've been working on the [Syllabus](https://www.aniqa.io/syllabus) page on my [website](https://www.aniqa.io). The page serves as my own personal Full Stack Software Development roadmap, checklist, and list of resources to use.
    
 Most of yesterday and today, I mostly worked on adding additional content for the resource and checklist section. The page currently shows the following information (although, a few may not be complete *just yet*):
<p align="center"><img src="https://github.com/aniqatc/learning-journal/blob/main/Assets/current-syllabus-list.png?raw=true"></p>
    
Once all the content is uploaded to the Syllabus page, I'll be working on making more wiki entries!
  </details>
  
<details><summary><b>Day 21 - 23: Add Additional Styling to Wiki Section & Upload Content</b></summary>
    
### Day 21 - 23

  My [syllabus page](https://www.aniqa.io/syllabus) is coming along beautifully. The <b>checklist tab</b> is mostly complete, however, the <b>resources tab</b> has a view empty spots. This is because I have not yet vetted and confirmed the best resources for those specific topics. I still think it's a pretty solid <i>plan</i> for beginners that want to dive deep!
  
  Anyways, for <b>Days 21 to 23</b>, I reviewed my previous notes regarding [web fundamentals](https://www.aniqa.io/wiki/web) and [web security fundamentals](https://www.aniqa.io/wiki/security) and uploaded them to the [wiki section](https://www.aniqa.io/wiki) of my website! So far, I was able to add notes regarding the following topics:
  
  <p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/wiki-web-entries.png" style="width:600px;"></p>
  
  I have dozens more of these entries covering several more topics that will continue to be uploaded in the coming days and weeks.
  
  Additionally, I added a repository version of all my [wiki entries](https://www.github.com/aniqatc/wiki) for those that prefer to view notes on the GitHub platform instead.
      
</details>
  

<details><summary><b>Day 24: Add Key to Understand Wiki Entry Stages</b></summary>
  
<h3>Day 24</h3>

In order to truly adopt the digital garden concept, I had added a frontmatter data entry for <b>Stage</b> which would represent whether my note was newly uploaded, still being edited but somewhat complete, or if it's entirely complete and will likely not be modified. To represent each, I used the following terms:
  
  - 🌱 Seedling
  - 🌿 Sapling
  - 🌳 Evergreen
  
While each of these terms were clearly displayed on each of the posts, I could see how some might not understand the exact meaning for each. So, I added a simple <b>key</b> to the <a href="https://www.aniqa.io/wiki">wiki index</a> using the following design:
  
<p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/wiki-key.gif"></p>
    
</details>
  
  
    
<details><summary><b>Day 25: Use GraphQL StaticQuery Hook to Customize Wiki Entry List</b></summary>
    
<h3>Day 25</h3>

Previously, the Wiki section displayed the current list of entries using the relative URL path for each individual entry:
    
<p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/wiki-list-%5Bdefault%5D.png"></p>
  
While many can assume the contents of each entry based on the URL path, it still feels unfinished and repetitive to me. I'd rather the individual title appear in place of the URL path providing a <b>more clear understanding</b> of each entry alongside the stage and/or topic each entry falls under.
  
  To do so, I used the <b>GrapQL Explorer</b> that is accessed at <code>http://localhost:8000/___graphql</code>.
  
  
  <i>More details coming soon</i>.

</details>
  
  
<details><summary><b>Day 26: Adding 'Keywords' Meta Tag for Additional SEO</b></summary>
    
<h3>Day 26</h3>

  Apparently, there used to be a meta tag for <b>keywords</b> that was used to specify tags that relate to a website's content (or individual page content) but it has become obsolete because it was abused by website creators that would spam their keyword list with thousands of keywords to rank high for various Google search results. 
  
  Despite knowing that piece of information, I wanted to add the keyword meta tag <i>anyways</i>. Some say that other search engines (e.g Bing, etc) may still use the keywords meta tag when bots are crawling a website. I figured it couldn't hurt to add an additional tag with information that could potentially help my website rank higher in search results. 
  
  Here's what the current state of my <code>seo.tsx</code> file looks like:
  
 <p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/seo-code.png" style="width:520px;"></p>
  
  You'll see that all the key SEO tags <i>(title, description, image, author & icon, etc)</i> and social media sharing <i>(Twitter Cards)</i> are already specified. Unless otherwise specified for a specific page, all pages will show the <b>default information</b> for all these tags which is specified in my <code>gatsby.config.js</code> file. For example, all blog posts will show the description that is specified in the Markdown file for each individual post, however, if a description is not specified, the general site description will be used instead.
  
  <b>Here's how:</b>
  
 In order to add the <code>keywords</code> tag, I needed to first query the data using <b>GraphQL</b>. With the help of Gatsby's GraphQL Explorer, I was able to find the <code>edges</code> and <code>nodes</code> that pointed to the <code>keywords</code> data point. This information was added to the <b>frontmatter</b> of my Markdown files for both <a href="https://www.aniqa.io/blog">blog posts</a> and <a href="https://www.aniqa.io/wiki">wiki note entries</a>. Then, I added the GraphQL query to the relevant component files for blog posts and wiki entries.
  
  After doing so, I would be able to pull the information to <code>seo.tsx</code> file that utilizes <code>react-helmet</code> for the SEO meta tags. Once I defined <code>keywords</code>, I was able to add the following code to define the meta tag so that it can be called and used within other component files:
  
  ```
  <meta name="keywords" content={keywords} />
  ```

  Lastly, I had to add the <code>keyword</code> attribute to the individual layout files for my blog posts and wiki entries -- since they already utilized the <b>SEO</b> component, I only needed to add the highlighted section:
  
   <p align="center"><img src="https://raw.githubusercontent.com/aniqatc/learning-journal/main/Assets/import-seo-to-components.png"></p>
  
  <b>To ensure that this addition is working as intended:</b> I used Chrome Developer Tools, Element Panel to view if my keywords were successfully being pulled from my Markdown files and being displayed within the <code>keyword</code> meta tag's <code>content</code> attribute. <b>It is working!</b>
  
  
</details>
  

<hr/>
 

  <b>Quick notes about completion of <a href="https://www.aniqa.io/wiki">Wiki section</a>.</b>
  
**FYI, I have over 50 pages of notes totaling tens of thousands of words and dozens of images covering web fundamentals, chrome developer tools, command line, git, Github and GatsbyJS for the wiki section.** What I'm trying to say here is that it took a long time to get everything organized and edited to be presentable. My hope is that once everything is uploaded, I can rest easy and start working on other projects that I have planned!
  
