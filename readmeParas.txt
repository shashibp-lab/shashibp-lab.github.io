new link should be added in the following format ?

 <!-- About --> 
 <li class="nav-item {% if page.title == 'about' %}active{% endif %}"> 
   <a class="nav-link" href="{{ '/' | relative_url }}">about 
     {%- if page.title == "about" -%} 
     <span class="sr-only">(current)</span> 
     {%- endif -%} 
   </a> 
 </li> 

for your substack link, you can have something like this:

<!-- Substack --> 
<li class="nav-item"><a class="nav-link" href="https://blog.aerospacenerd.com/">substack</a></li> 


_pages will have interesting content

* change address in _pages/about
"
This website in in progress......, Please ignore the contents
<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
" # this was commented out