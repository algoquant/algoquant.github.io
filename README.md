### This is the repository for <a href="https://algoquant.github.io/" title="algoquant's Home Page on GitHub" target="_blank"> *algoquant's Home Page on GitHub* </a>

The website is hosted on GitHub Pages at <a href="https://algoquant.github.io/" title="algoquant's Home Page on GitHub" target="_blank"> https://algoquant.github.io/ </a>

### Website design

The website was created using [*Jekyll*](http://jekyllrb.com), and its theme was adapted from the 
<a href="https://github.com/pietromenna/jekyll-architect-theme" target="_blank"> Jekyll-Architect theme</a> 
by 
<a href="https://github.com/pietromenna" target="_blank"> Pietro Menna</a>, 
and the 
<a href="https://github.com/daattali/beautiful-jekyll" target="_blank"> Beautiful-Jekyll theme</a> 
by 
<a href="https://github.com/daattali" target="_blank"> Dean Attali</a>.

[*Jekyll*](http://jekyllrb.com) is a website generator which compiles *markdown* files into *HTML*.  You can find more information about *Jekyll* here: [*Jekyll* web page](http://jekyllrb.com)

A *Jekyll theme* is a set of *HTML* and *CSS* files that determine the appearance of a website, like the fonts, colors, shading, and page layouts.  A *Jekyll theme* can be adapted to create websites with the same appearance as the theme has.  Here you can find more: <a href="http://jekyll.tips/templates/" target="_blank">*Jekyll themes*</a>  


### Website structure

The website code is written in *markdown*, *HTML*, *CSS*, *YAML*, and [*liquid*](https://shopify.github.io/liquid/).  The website consists of directories containing several different types of files:

* the website parameters and settings are in the *\_config.yml* file (written in YAML) in the *root* directory,  
* the parameters for the *Jekyll* processor are in the *Gemfile* file in the *root* directory,  
* the website contents are written in markdown and R Markdown files collected in the *\_pages* and *\_posts* directories,  
* the page layouts are written in HTML files collected in the *\_layouts* and *\_includes* directories,  
* the page designs are in CSS files collected in the *stylesheets* directory,  
The markdown and HTML files also contain [liquid](https://shopify.github.io/liquid/) code for referencing website parameters and settings.  


### Website download

You can download the website files from here:  
<a href="https://github.com/algoquant/algoquant.github.io/archive/master.zip" class="button">
  <small>Download theme</small>.zip file</a>  
<a href="https://github.com/algoquant/algoquant.github.io/archive/master.tar.gz" class="button">
  <small>Download theme</small>.tar.gz file</a>

Once you have downloaded the archive, you can unzip the website files into a directory on your computer.  But be aware that my website isn't a static website theme, but rather it's a complete website, and its contents change over time.

You can then replace the contents of the *markdown* files in the *\_pages* and *\_posts* directories with your own.  You must also modify the website parameters in the *\_config.yml* file.  Do the following:

* replace the contents of *markdown* and *R Markdown* files,  
* modify the website parameters in the *\_config.yml* file,  


### Jekyll installation

You can install the website on your computer, but you must first install *Ruby*, *Jekyll*, and *bundler*.  I installed the website under *Windows* (which I hate, but have been forced to use it at work, and have continued to use it due to inertia).  If you're also using *Windows*, then you can first install <a href="https://chocolatey.org/" target="_blank">*chocolatey*</a>, which is a package manager for *Windows*).  

You can then install *Ruby*, *Jekyll*, and *bundler* with the following commands in a *command* window, each time reopening the *command* window, and installing one by one:  
`choco install ruby -y`  
`gem install jekyll`  
`gem install bundler`  

You can find more detailed instructions here:  
<a href="https://www.ruby-lang.org/en/downloads/" target="_blank">install *Ruby*</a>  
<a href="https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/" target="_blank">install *Jekyll*</a>  
<a href="http://jwillmer.de/blog/tutorial/how-to-install-jekyll-and-pages-gem-on-windows-10-x46" target="_blank">install *Ruby* and *Jekyll* on Windows</a>

You may also need to install the *Ruby* development kit for compiling *Ruby* gems (packages that provide extra functionality):  
<a href="https://jekyllrb.com/docs/installation/" target="_blank">install *Ruby devkit* installation </a>  
<a href="https://github.com/oneclick/rubyinstaller/wiki/Development-Kit" target="_blank"> install *Ruby devkit* installer </a>


### Website installation

<a href="http://jekyllrb.com" target="_blank"> *Jekyll* </a> is a website generator which compiles *markdown* files containing the website content, together with *HTML* and *CSS* theme files, into *HTML* files ready to be served on the website.  

After you've installed *Ruby*, *Jekyll*, and *bundler*, you can then install the website on your computer, by opening a *command* window, navigating to the website directory, and executing the following commands:  
`bundle install`  
`bundle exec jekyll serve`

If you later add gems in the *\_config.yml* file, then you may need to execute the commands:  
`bundle update`  
`bundle exec jekyll serve`

The command `jekyll serve` builds the static website files in the *\_site* sub-directory, and starts a web server running locally on your computer.  You can view the website in your browser under the address:  
<a href="http://localhost:4000/" title="website on your computer" target="_blank"> http://localhost:4000/ </a>

The command `bundle exec jekyll serve` runs the <a href="http://bundler.io/" target="_blank"> *Ruby bundler* </a> which builds the website using all the gems specified in the *Gemfile*, and manages all the software dependencies.  
The command `bundle exec jekyll serve --trace --verbose` provides extra information about the build process. 

Once you're satisfied with the website build on your computer, you can then upload it to GitHub by following these instructions: <a href="https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/" target="_blank"> *GitHub* instructions </a>


### Adding Disqus comments, Sharing on LinkedIn

<https://harringa.com/posts/2015/12/19/adding-disqus-to-jekyll-site/>  
<http://sgeos.github.io/jekyll/disqus/2016/02/14/adding-disqus-to-a-jekyll-blog.html>  
<https://developer.linkedin.com/docs/share-on-linkedin>  
<https://superdevresources.com/share-buttons-jekyll/>  


### Additional references

Here are some blogs and tutorials about building static websites on GitHub using Jekyll: 

* <a href="http://literaturegeek.com/2016/04/20/building-static-website-with-jekyll-github-pages" target="_blank"> Very good and detailed tutorial </a>
* <a href="https://24ways.org/2013/get-started-with-github-pages/" target="_blank"> Simple tutorial </a>

http://pixelcog.com/blog/2013/jekyll-from-scratch-introduction/  
http://pixelcog.com/blog/2013/jekyll-from-scratch-core-architecture/  
http://pixelcog.com/blog/2013/jekyll-from-scratch-extending-jekyll/


* <a href="http://jekyllrb.com/docs/home/" target="_blank"> *Jekyll* home </a>
* <a href="http://jekyll.tips/" target="_blank">*Jekyll* tutorials</a>
* <a href="http://jekyll.tips/jekyll-casts/jekyll-file-structure/" target="_blank">*Jekyll* file structure</a>
* <a href="https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/" target="_blank"> *Jekyll Now* for easy building of websites (I haven't used it) </a>
* <a href="http://jekyll.tips/jekyll-casts/install-jekyll-on-windows/" target="_blank">Install *Jekyll* on Windows</a>
* <a href="http://jekyll.tips/templates/" target="_blank"> *Jekyll themes* </a>

GitHub Pages help:  
<https://pages.github.com/>
<https://help.github.com/categories/github-pages-basics/>  
<https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/>  
<https://help.github.com/articles/creating-pages-with-the-automatic-generator/>  
<https://help.github.com/articles/configuring-jekyll/>  
<https://help.github.com/articles/user-organization-and-project-pages/>  
<https://help.github.com/categories/customizing-github-pages/>  
<https://blog.r3bl.me/en/jekyll-blogging-like-a-pro/>  


### Nice Jekyll themes

* <a href="https://github.com/jekyll/jekyll/wiki/Themes" target="_blank"> repository of *Jekyll themes* </a>
* <a href="https://github.com/mmistakes/skinny-bones-jekyll" target="_blank"> simple and customizable *Jekyll* theme </a>
* <a href="https://github.com/scotte/jekyll-clean" target="_blank"> simple *Jekyll* theme with menu and sidebar </a>
* <a href="https://github.com/tomjohnson1492/documentation-theme-jekyll" target="_blank"> fancy *Jekyll* theme with menu and sidebar </a>
* <a href="https://github.com/JustusAdam/justusadam.github.io" target="_blank"> *Jekyll* theme with sidebar </a>
<>  

Command for creating template Jekyll directory (uses very simple page layout and theme):  
`bundle exec jekyll new C:/Develop/web/site_template --force`


### More references about building websites on GitHub using Jekyll

<https://ines.io/blog/the-ultimate-guide-static-websites-jekyll>  
<https://davidwalsh.name/introduction-static-site-generators>  
<https://mademistakes.com/articles/using-jekyll-2016/>  


## Below are more references about building websites

### Building websites using *R Markdown* and *knitr*

I use *R* for all my work, so in the future I may also try building my websites using *R Markdown* and *knitr*.  Here are some references about building websites using *R Markdown* and *knitr*:

* <a href="https://rmarkdown.rstudio.com/rmarkdown_websites.html" target="_blank"> R Markdown websites </a>
* <a href="https://brendanrocks.com/blogging-with-rmarkdown-knitr-jekyll/" target="_blank"> Building websites using R Markdown and knitr </a>

<https://github.com/yihui/knitr-jekyll>  
<https://github.com/yihui/servr>  
<https://github.com/homerhanumat/homerhanumat.github.io>  
<http://statistics.rainandrhino.org/knitr-hyde/>  
<http://statistics.rainandrhino.org/knitr-lanyon/>  
<http://statistics.rainandrhino.org/2015/12/15/jekyll-r-blogger-knitr-hyde.html>  
<http://www.sciviews.org/blog/The-SciViews-Jekyll-Template/>  
<https://help.github.com/articles/using-a-custom-domain-with-github-pages/>  

[Hacking *htmlwidgets* into website using *rmarkdown*](https://brendanrocks.com/htmlwidgets-knitr-jekyll/){:target="_blank"}  
[Hacking *htmlwidgets* into website using *Jekyll*](http://benjcunningham.org/2016/06/13/hacking-together-htmlwidgets-for-jekyll.html){:target="_blank"}  

