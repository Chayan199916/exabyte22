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
4. [important] please add 50px margin right in middle section for mobile & tablet view. Otherwise middle content will be covered by the page indicators in right side.

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
      <!--right navbar-->
      <div class="sidebar" id="mySidebar">
        <img
          class="close"
          onclick="closeNav()"
          src="https://img.icons8.com/ios-glyphs/30/ffffff/delete-sign.png"
        />
        <div class="options__container">
          <ul>
            <li>
              <a href="">Home</a
              ><a href=""
                ><img
                  src="https://img.icons8.com/material-rounded/50/808080/home.png"
              /></a>
            </li>
            <li class="selected">
              <a href="">About Us</a
              ><a href=""
                ><img
                  src="https://img.icons8.com/material-outlined/50/808080/about.png"
              /></a>
            </li>
            <li>
              <a href="">Events</a
              ><a href=""
                ><img
                  src="https://img.icons8.com/external-sbts2018-outline-sbts2018/50/808080/external-events-social-media-basic-1-sbts2018-outline-sbts2018.png"
              /></a>
            </li>
            <li>
              <a href="">Magazines</a
              ><a href=""
                ><img
                  src="https://img.icons8.com/external-kiranshastry-lineal-kiranshastry/50/808080/external-magazine-advertising-kiranshastry-lineal-kiranshastry.png"
              /></a>
            </li>
            <li>
              <a href="">Our team</a
              ><a href=""
                ><img
                  src="https://img.icons8.com/external-sbts2018-outline-sbts2018/50/808080/external-team-work-from-home-sbts2018-outline-sbts2018.png"
              /></a>
            </li>
            <li>
              <a href="">Sponsors</a
              ><a href=""
                ><img
                  src="https://img.icons8.com/external-wanicon-lineal-wanicon/50/808080/external-sponsored-digital-content-wanicon-lineal-wanicon.png"
              /></a>
            </li>
            <li>
              <a href="../contact/contact.html">Contact us</a
              ><a href="../contact/contact.html"
                ><img
                  src="https://img.icons8.com/ios/50/808080/online-support.png"
              /></a>
            </li>
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
