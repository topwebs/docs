---
title: Cygnet: Recreating the Demo - About Us Page
description: Your Guide to Recreating Elements of the Cygnet Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cygnet:Cygnet

---

Introduction
-----

The **About Us** example page demonstrates how you can create a beautiful page with the Cygnet template. Here is some information to help you replicate this page as it appears in the demo.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

Modules
-----

Below is a brief rundown of the modules used to make up the demo page.

![](assets/page_aboutus.jpeg)

:   1. **Custom HTML - About Us** [10%, 45%, se]
    2. **Breadcrumbs** [17%, 13%, se]
    3. **Custom HTML - About Us: Introduction** [20%, 13%, se]
    4. **Custom HTML - Our Mission** [36%, 13%, se]
    5. **Article Content** [55%, 13%, se]
    6. **Custom HTML - We Always Try to Create a Difference** [68%, 28%, se]
    7. **Custom HTML - Cygnet Demo** [75%, 13%, se]
    8. **Custom HTML - Sample Contact Info** [75%, 51%, se]

1. [Custom HTML - About Us](aboutus.md#custom-html---about-us)
2. [Breadcrumbs](aboutus.md#breadcrumbs)
3. [Custom HTML - About Us: Introduction](aboutus.md#custom-html---about-us:-introduction)
4. [Custom HTML - Our Mission](aboutus.md#custom-html---about-us:-our-mission---our-values---our-solution)
5. [Article Content](aboutus.md#mainbody)
6. [Custom HTML - We Always Try to Create a Difference](aboutus.md#custom-html---we-always-try-to-create-a-difference)
7. [Custom HTML - Cygnet Demo](aboutus.md#custom-html---cygnet-demo)
8. [Custom HTML - Sample Contact Info](aboutus.md#custom-html---sample-contact-info)

### Custom HTML - About Us

![](assets/page_aboutus_1.jpeg)

#### Module

| Option     | Setting                                                       |
| :-----     | :-----                                                        |
| Title      | `About Us[span class="rt-title-tag"]Welcome to Cygnet[/span]` |
| Show Title | Yes                                                           |
| Position   | showcase-a                                                    |
| Status     | Published                                                     |
| Access     | Public                                                        |

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

#### Content

~~~ .html
&nbsp;
~~~

#### Options

| Option                    | Setting |
| :-----                    | :-----  |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

| Option              | Setting                                                                        |
| :-----              | :-----                                                                         |
| Module Class Suffix | `rt-top-large-padding nomarginall rt-center rt-title-large rt-nomodulecontent` |

### Breadcrumbs

![](assets/page_aboutus_2.jpeg)

#### Module

|        Option       |    Setting    |
| :------------------ | :------------ |
| Title               | `Breadcrumbs` |
| Show You Are Here   | No            |
| Show Home           | Yes           |
| Text for Home Entry |               |
| Show Last           | Yes           |
| Text Separator      |               |
| Show Title          | Hide          |
| Position            | breadcrumb    |
| Status              | Published     |
| Access              | Public        |

##### Advanced

|        Option       |     Setting     |
| :------------------ | :-------------- |
| Module Class Suffix | ` hidden-phone` |

### Custom HTML - About Us: Introduction

![](assets/page_aboutus_3.jpeg)

#### Module

|   Option   |                   Setting                    |
| :--------- | :------------------------------------------- |
| Title      | `About Us: Introduction - Mission Statement` |
| Show Title | Hide                                         |
| Position   | feature-a                                    |
| Status     | Published                                    |
| Access     | Public                                       |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-01.jpg" alt="image" /></span>
            </div>
        </div>

        <div class="gantry-width-50">
            <div class="gantry-width-spacer">
                <h3>Introduction</h3>
                <p>Globally incubate standards compliant channels before scalable benefits. Quickly disseminate superior deliverables whereas web-enabled applications. Quickly drive clicks-and-mortar catalysts for change.</p>
                <div class="hidden-tablet">
                    <h3>More About Us</h3>
                    <p>Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration and idea-sharing.</p>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

| Option              | Setting                            |
| :------------------ | :--------------------------------- |
| Module Class Suffix | `box2 nomarginall`                 |

### Custom HTML - About Us: Our Mission - Our Values - Our Solution

![](assets/page_aboutus_4.jpeg)

#### Module

|   Option   |                       Setting                       |
| :--------- | :-------------------------------------------------- |
| Title      | `About Us: Our Mission - Our Values - Our Solution` |
| Show Title | Hide                                                |
| Position   | expandedbottom-a                                    |
| Status     | Published                                           |
| Access     | Public                                              |

#### Content

~~~ .html
<div class="gantry-row">
    <div class="gantry-width-container">
        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-02.jpg" alt="image" /></span>
                <h4>Our Mission</h4>
                <p>Objectively innovate empowered manufactured products whereas parallel platforms. Holistically predominate extensible testing procedures for reliable supply chains.</p>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-03.jpg" alt="image" /></span>
                <h4>Our Values</h4>
                <p>Proactively envisioned multimedia based expertise and cross-media growth strategies. Seamlessly visualize quality intellectual capital without superior collaboration.</p>
            </div>
        </div>

        <div class="gantry-width-33">
            <div class="gantry-width-spacer">
                <span class="rt-image"><img src="images/rocketlauncher/pages/about-us/img-04.jpg" alt="image" /></span>
                <h4>Our Solution</h4>
                <p>Engage worldwide methodologies with web-enabled technology. Interactively coordinate proactive e-commerce via process-centric outside the box thinking.</p>
            </div>
        </div>
    </div>
</div>

<div class="clear"></div>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

| Option              | Setting            |
| :------------------ | :----------------- |
| Module Class Suffix | `box3 nomarginall` |

### Custom HTML - We Always Try to Create a Difference

![](assets/page_aboutus_6.jpeg)

#### Module

|   Option   |                Setting                 |
| :--------- | :------------------------------------- |
| Title      | `We Always Try to Create a Difference` |
| Show Title | Show                                   |
| Position   | extension-a                            |
| Status     | Published                              |
| Access     | Public                                 |

#### Content

~~~ .html
<p>Utilized with Versatile and Flexible Features Powered by the Gantry Framework.</p>

<p><a href="http://www.rockettheme.com/joomla/templates/cygnet" class="readon largemargintop">Download Cygnet</a></p>
~~~

#### Options

|           Option          | Setting |
| :------------------------ | :------ |
| Prepare Content           | No      |
| Select a Background-Image | Blank   |

#### Advanced

| Option              | Setting                      |
| :------------------ | :----------                  |
| Module Class Suffix | `box4 rt-center nomarginall` |

### Custom HTML - Cygnet Demo

![](assets/page_aboutus_7.jpeg)

#### Module

| Option     | Setting        |
| :--------- | :------------- |
| Title      | `Cygnet Demo`  |
| Show Title | Yes            |
| Position   | footer-a       |
| Status     | Published      |
| Access     | Public         |

#### Content

~~~ .html
<p class="hidden-phone">These examples are intended to show how Cygnet can be constructed on your site, above and beyond the frontpage demonstration. These include Joomla content and component pages, with varying modular content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/joomla/templates/cygnet">Cygnet RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

### Custom HTML - Sample Contact Info

![](assets/page_aboutus_8.jpeg)

#### Module

| Option     | Setting               |
| :--------- | :-------------------- |
| Title      | `Sample Contact Info` |
| Show Title | Yes                   |
| Position   | footer-b              |
| Status     | Published             |
| Access     | Public                |

#### Content

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="images/rocketlauncher/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Cygnet Theme, LLC</span><br />
            <span>123 Joomla! Boulevard</span><br />
            <span>Seattle, WA 00000, USA</span><br />
            <span><a href="#">noreply@domain.com</a></span>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

#### Options

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background-Image | Blank       |

#### Advanced

| Option              | Setting           |
| :----------         | :----------       |
| Module Class Suffix | `rt-phone-center` |

Mainbody
-----

![](assets/page_aboutus_5.jpeg)

The page's content body is set in the **About Us** article. You will find the content used in the article below.

~~~ .html
<h3>Cygnet, the Powerful Template</h3>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>

<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas. Dynamically innovate resource-leveling customer service for state of the art customer service.</p>

<p><a href="http://www.rockettheme.com/joomla/templates/cygnet" class="readon">Learn More</a></p>
~~~