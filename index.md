---
title: "Framework for Leading Change"
date: "2022-10-20"
---

<header>

<head>
    <title>Building a Horizontal Navigation Bar</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Arial', sans-serif;
        }

        .navbar {
            display: flex;
            position: sticky;
            align-items: center;
            justify-content: space-between;
            top: 0px;
            background: rgb(255 127 39);
            background-blend-mode: darken;
            background-size: cover;
            color: white;
            padding: 10px 20px;
        }

        .nav-list {
            display: flex;
            list-style: none;
        }

        .nav-list li {
            margin-right: 20px;
        }

        .nav-list li:last-child {
            margin-right: 0;
        }

        .nav-list li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
            transition: color 0.3s ease-in-out;
        }

        .nav-list li a:hover {
            color: #ffd700;
            /* Change the color on hover */
        }

        .rightNav {
            text-align: right;
        }

        #search {
            padding: 8px;
            font-size: 16px;
            border: 2px solid #fff;
            border-radius: 5px;
        }

        .btn {
            background-color: #ffd700;
            color: #000;
            border: none;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease-in-out;
        }

        .btn:hover {
            background-color: #000;
            /* Change the background color on hover */
            color: #ffd700;
        }
    </style>
</head>

<body>
    <nav class="navbar">
        <ul class="nav-list">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <div class="rightNav">
            <input type="text" name="search" id="search" placeholder="Search">
            <button class="btn btn-sm">Search</button>
        </div>
    </nav>
  
  <nav class="nav--primary__container" aria-label="Top menu"><div class="container"><button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nav--primary" aria-controls="nav--primary" aria-expanded="false">Menu</button></div><ul id="nav--primary" class="nav nav--primary container"><li id="menu-item-864" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-3 current_page_item menu-item-has-children menu-item-864"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/" aria-current="page">Framework for Leading Change</a> <button aria-expanded="false" class="sub-menu--button" aria-controls="sub-menu-1"><span class="sr-only">Toggle submenu for Framework for Leading Change</span></button><ul class="sub-menu" aria-label="submenu" id="sub-menu-1"> <li id="menu-item-863" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-863"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/where-should-we-start/">Where should we start?</a></li> </ul> </li> <li id="menu-item-1451" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children menu-item-1451"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/navigating-the-world-of-change/">Deepening our understanding</a> <button aria-expanded="false" class="sub-menu--button" aria-controls="sub-menu-2"><span class="sr-only">Toggle submenu for Deepening our understanding</span></button><ul class="sub-menu" aria-label="submenu" id="sub-menu-2"> <li id="menu-item-875" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-875"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/navigating-the-world-of-change/">Navigating the world of change</a></li> <li id="menu-item-1005" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1005"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/laying-our-foundation-for-successful-change/">Laying our foundation for successful change</a></li> </ul> </li> <li id="menu-item-1452" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children menu-item-1452"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/understanding-our-context/">Strategizing and planning</a> <button aria-expanded="false" class="sub-menu--button" aria-controls="sub-menu-3"><span class="sr-only">Toggle submenu for Strategizing and planning</span></button><ul class="sub-menu" aria-label="submenu" id="sub-menu-3"> <li id="menu-item-1035" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1035"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/understanding-our-context/">Understanding our context</a></li> <li id="menu-item-780" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-780"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/capacity-readiness-and-impact/">Capacity, readiness and impact</a></li> <li id="menu-item-1318" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1318"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/getting-people-on-board/">Getting people on board</a></li> <li id="menu-item-1335" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1335"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/developing-our-plans/">Developing our plans</a></li> </ul> </li> <li id="menu-item-1453" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children menu-item-1453"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/implementing-the-change/">Navigating our change</a> <button aria-expanded="false" class="sub-menu--button" aria-controls="sub-menu-4"><span class="sr-only">Toggle submenu for Navigating our change</span></button><ul class="sub-menu" aria-label="submenu" id="sub-menu-4"> <li id="menu-item-1389" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1389"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/implementing-the-change/">Implementing the change</a></li> </ul> </li> <li id="menu-item-1454" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children menu-item-1454"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/reaching-our-waypoint/">Reaching our waypoint</a> <button aria-expanded="false" class="sub-menu--button" aria-controls="sub-menu-5"><span class="sr-only">Toggle submenu for Reaching our waypoint</span></button><ul class="sub-menu" aria-label="submenu" id="sub-menu-5"> <li id="menu-item-1408" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1408"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/reaching-our-waypoint/">Living with the change</a></li> </ul> </li> <li id="menu-item-1514" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1514"><a href="https://articles.alpha.canada.ca/framework-for-leading-change/contact-us/">Contact us</a></li> </ul></nav>
 </header>

  
This framework is designed to strengthen our ability to lead different types of change in the public service, from incremental to transformational. It offers a flexible approach that can be adapted depending on the context, and introduces concepts and methods that guide us in planning and implementing our activities. Using the framework to lead change can increase both the chances of success for a particular initiative and also offers a path to build on our success to support future change.

Working under the premise that no single change methodology provides solutions to every challenge, this framework pulls from a range of different models throughout. It follows the major phases of recognized best practices in leading change.

The framework is divided into four parts (inspired by the upstream, midstream, downstream model often used to [identify the social determinants of health](https://www.rand.org/content/dam/rand/pubs/working_papers/WR1000/WR1096/RAND_WR1096.pdf)).

* * *

## **Using the framework**

Conceptually, we can think of ourselves as explorers, navigating our way through partially charted waters to an uncertain future. Thinking about it this way can broaden our understanding of the change itself and of what will be required to reach our waypoint.

There are four parts to the framework. Divided among the four parts are eight sections. Below is an outline of the sections and where they fit within the four parts. The outline provides a good idea of the full process. Just to note, while the process does follow a particular path, there are times when we will need to go back and revise aspects of certain sections. Going back to earlier sections is a regular part of leading change and should not be considered a setback.

* * *

**Deepening our understanding of how to navigate change**

<img src="images/FLC-Deepening.png" width="150">

**1.** [Navigating the world of change](navigating-the-world-of-change/) provides us with essential concepts that will help us to develop our strategy and implement our plan.

**2.** [Laying our foundation for successful change](laying-our-foundation-for-successful-change/) covers the “why” of the change, the conditions that need to be fulfilled for us to succeed, and some of the ways we can bring it about. In this phase we set the stage for the strategy we will use to navigate our change.

### How can this section help us?

Our knowledge of how to navigate (for our purposes, our knowledge of the latest change methodologies, techniques and concepts) is fundamental in determining how effective we are in our planning and navigating phases. If we don’t know the fundamentals of how to navigate, we might end up somewhere we do not want to be.

* * *

**Strategizing and Planning our route**

<img src="images/FLC-Strategizing.png" width="150">

**3.** [Understanding our context](understanding-our-context/) involves assessing our environment and culture, both to see where our change fits within the broader organization, and so we can determine the best approach to support it.

**4.** [Capacity, readiness and impact](capacity-readiness-and-impact/) provides an opportunity for us to refine our understanding of how ready we are for change, the impact it will have on key players, and how we will work with them throughout the change.

**5.** [Getting people on board](getting-people-on-board/) includes the engagement activities necessary to ensure the change is successful, depending on the type of change we are leading and who is taking part in it.

**6.** [Developing our plans](developing-our-plans/) involves creating and integrating the various plans (e.g., engagement, communications) that will guide us when rolling out the change.

### How can this section help us?

Planning is an essential phase when exploring, but we need to be ready and capable of pivoting. On our trip, we will almost inevitably we run into unexpected situations like a tree fallen in the river. That’s the unexpected nature of change. Yet, with a deep understanding of how to navigate, we can pivot, alter course, double back, or give up altogether (when absolutely necessary).

* * *

**Navigating our change**

<img src="images/FLC-Navigating.png" width="150">

**7.** [Implementing the change](implementing-the-change/) involves carrying out the activities developed in the first sections, including being flexible, soliciting feedback, and adapting as we go.

### How can this section help us?

Deep engagement and collaboration is essential to be able to get to our waypoint. We can only reach our goal if everyone involved agrees on the destination and participates in the journey.

* * *

**Reaching our waypoint**

<img src="images/FLC-Waypoint.png" width="150">

**8.** [Living with the change](reaching-our-waypoint/) is about ensuring the change is sustainable and that we can continue to build on our successful outcome, which will help strengthen the organization in facing future change.

### How can this section help us?

While reaching the waypoint is the goal, it is not the end of our journey. As explorers we will eventually want to reach new destinations. We could run out of food sources, predators may move into the area, or we could glimpse new, more fruitful land in the distance. No matter the reason, the work we do in this phase (such as consolidating lessons learn) will help make the journey smoother for those coming behind us, and make the next part of our journey easier.

* * *

[Where should we start in the Framework?](where-should-we-start/)

[Get started](navigating-the-world-of-change/)

* * *
