# eXabyte '22

# Instructions

- fork the repo.
- create a new branch with the name of the page you are working on.
- put you work in a folder with the name of the task you are working on.
- add your work and create a merge request.

# adding navbar in pages

1. link the navbar.js and navbar.css files
2. add "selected" class in the li of the respective page
3. copy the "menu" icon form navbar/navbar.txt and paste

```
   <img
      class="open"
      onclick="openNav()"
      src="https://img.icons8.com/ios-glyphs/30/ffffff/menu--v1.png"
   />
```

4. copy the code snippet of navbar from navbar/navbar.txt and paste in the bottom of pages
   [for example please check about/about.html]

```
    <div class="sidebar" id="mySidebar">
        <button class="close" onclick="closeNav()">close</button>
        <div class="options__container">
          <ul>
            <li><a href="">Home</a></li>
            <li class="selected"><a href="">About Us</a></li>
            <li><a href="">Events</a></li>
            <li><a href="">Magazines</a></li>
            <li><a href="">Our team</a></li>
            <li><a href="">Sponsors</a></li>
            <li><a href="../contact/contact.html">Contact us</a></li>
          </ul>
        </div>
        <div class="icons__container">
          <a href=""
            ><img
              src="https://img.icons8.com/ios/30/ffffff/facebook-new.png"
            /> </a
          ><a href=""
            ><img
              src="https://img.icons8.com/ios/30/ffffff/twitter--v1.png"
            /> </a
          ><a href=""
            ><img
              src="https://img.icons8.com/ios/30/ffffff/instagram-new--v1.png"
          /></a>
        </div>
    </div>
```
