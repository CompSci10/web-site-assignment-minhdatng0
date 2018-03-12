# web-site-assignment
In this assignment you will be creating a multi-site [responsive web site](https://en.wikipedia.org/wiki/Responsive_web_design) hosted on GitHub using the [Bootstrap framework](http://getbootstrap.com/). To get full marks for the various components it is important that you follow the instructions. 

## Set up Bootstrap
Bootstrap is a free and open-source front-end library for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. The first version of Bootstrap was released on january 31, 2012 and was developed by developers at twitter. Bootstrap is using git for sourcecontrol management and is [hosted at GitHub](https://github.com/twbs/bootstrap). To date there has been nearly 18000 commits by almost 1000 people contributing to the Bootstrap framework.

To set up a Bootstrap web page template follow the steps below.

1. Familiarize yourself with Bootstrap and responsive web sites by watching the following videos:
 * https://youtu.be/DX-LoNaUr6w
 * https://youtu.be/gqOEoUR5RHg (1hr video tutorial) It is recommended that you watch the entire video and then use it as a reference when you are working on your site. Note the time stamped table of content in the video discription. 

2. Create a new public repository by clicking on the green ```New Repository``` button on your GitHub landing page. Your new repository has to be named ```your-user-name.github.io``` where you replace ```you-user-name``` with your GitHub user name, for example GitHub user Tony-Stark-CS would name his repository ```Tony-Stark-CS.github.io```. It is very important that your repository is named exactly this way or it will not work. 

3. Clone the remote respository to your Raspberry Pi.

4. In the next few steps you will download a template index.html page and add the Bootstrap framwork to your local repository. Go to https://getbootstrap.com and click on the Examples link in the navigation bar. Select the Album Example (click on the thumb nail). Download the web page (CTRL + S) to your local repository. Name the downloade file `index.html`.

5. Go to your local repository in your terminal. Do `ls` to check the files in your working directory for the assignment. You should be able to see the `index.html` file and a `index_files` folder. The folder contains the CSS files and required JavaScripts for Bootstrap to work. Commit and push.

7. Your "web page" is now live (although it currently only has the contents of the template you are using). The URL for your web page is ```https://tony-stark-cs.github.io/index.html``` (where you replace ```tony-stark-cs``` with your own GitHub user name. Every time you update your webpage and commit (and sync/push if you work locally) the changes will be reflected on this web page. Check that you are able to access the site at the designated URL. 

8. You are now ready to start turning the `index.html` to the first page of your web site. When you are working on the web page make sure you open it locally (using CTRL-O) and reload it every time you save new markup rather than reloading your live site to check how changes look. There is often a slight delay before the changes take effect on the live site and it is much more efficient to use the local site for checking.

## Creating a web page
Now that you have your basic template for a web page you will add contents to it and format it using HTML, CSS and the Bootstrap framwork. For this part of the assignment you are required to do online research to decide what feature of the Bootstrap framework you want to use and to understand the various components and features that are part of the Bootstrap framework and how incorporate them into your web site. The main [Bootstrap web site](http://getbootstrap.com/) is the best resource for information on the capabilities of the framwork and for code examples. 

Your website will be featuring an artist (e.g. musician, music group, painter, dancer, author, poet, etc.) of your choice and will consist of the following three inter-linked web pages:
* `index.html` - landing page that will introduce the artist and link to the other pages.
* `biography.html` - subpage that will provide a brief professional history of the artist.
* `works.html` - a subpage listing all (or selected) works (e.g. albums, concerts, exhibits, books, paintings etc).
 
It is up to you to decide how to format the pages and the type of information to include. To recieve a 50% your site has to include the following components:
* At least `index.html`, `biography.html` and `works.html` pages.
* At least 5 embedded images (images must be included in a separate image directory in your repository).
* At least 5 links to other sites.
* Appropriate written information.
* Proper heading tags, `<h1>`, `<h2>`, etc.
* At least one ordered list (`<ol>`) and one unordered list (`<ul>`).
* Each page has to include a `<hr>` tag separating the footer from the rest of the page.
* The footer section has to include today's date, a "Created by ..." statement and a link to the hosting GitHub repository.
* The head-section of all the pages have to be properly formated, e.g. include the `<title>` tag giving the page title e.g. `<title>ABBA by Dr. P</title>`, etc.
* Web site has to be attractive, properly formatted and sub pages have to have a consistent look and feel (in this assignment - looks matter!).
* Use of proper English language (grammar and spelling).
 
To get a mark of >50% your site has to include all of the above + the following components:
* Up to 60% - All of the above + modifications of the CSS style sheet (in the `css` folder), e.g. background color, link color, font, page dimensions etc.
* Up to 70% - All of the above + [three column grid formatting](http://getbootstrap.com/css/#grid)
* Up to 80% - All of the above + [Navbar](http://getbootstrap.com/components/#navbar) with appropriate links (e.g. to subpages)
* Up to 90% - All of the above + a [carousel with images](http://getbootstrap.com/javascript/#carousel).
* Up to 100% - All of the above + three levels of responsiveness, large screen (e.g. computer monitor), medium screen (e.g. tablet) and small screen (e.g. cell phone). It would make sense to match the three levels of responsiveness to the three column grid layout (three columns <-> two columns <-> single column). 
