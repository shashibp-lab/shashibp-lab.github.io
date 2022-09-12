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