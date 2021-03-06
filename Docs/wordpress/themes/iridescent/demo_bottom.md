---
title: Iridescent: Recreating the Demo - Bottom
description: Your Guide to Recreating Elements of the Iridescent Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/iridescent:Iridescent

---

Bottom Section
-----

![Bottom](assets/demo_7.jpeg)

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 37%, se]
    3. **Text 3** [20%, 68%, se]

Here is the widget breakdown for the Bottom section:

* Text
* Gantry Divider
* Text
* Gantry Divider
* Text

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>All demo content is for sample purposes only. All content images are freely available from <a href="http://unsplash.com/">Unsplash</a>.</p>
<p><span class="hidden-tablet"> Use the <a href="http://www.rockettheme.com/wordpress/themes/iridescent">RocketLauncher</a> to install a demo equivalent onto your site.</span></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |                      Setting                       |
| :---------------- | :------------------------------------------------- |
| Title             | `Demo Info`                                        |
| Custom Variations | `fp-bottom-a rt-modtitle-uppercase wow fadeInDown` |

Leaving everything else at its default setting, select **Save**.

#### Gantry Divider

This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/blog">Read the Latest Blog Post</a></p>
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/the-team">View our Global Team</a></p>
<p class="smallmarginbottom"><a href="http://www.rockettheme.com/promotions">Enjoy a Promotion</a></p>
<p class="smallmarginbottom"><a href="http://www.shareasale.com/shareasale.cfm?merchantID=30300">Become an Affiliate</a></p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |                             Setting                             |
| :---------------- | :-------------------------------------------------------------- |
| Title             | `About RocketTheme`                                             |
| Custom Variations | `fp-bottom-b rt-modtitle-uppercase hidden-phone wow fadeInDown` |

Leaving everything else at its default setting, select **Save**.

#### Text 3

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Sign up and we'll let you know about our new stuff and products.</p>

<form class="fp-bottom-form" onsubmit="window.open('http://feedburner.google.com/fb/a/mailverify?uri=rocketthemeblog', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true" target="popupwindow" method="post" action="http://feedburner.google.com/fb/a/mailverify">
  <input type="text" name="email" class="inputbox" placeholder="Your Email" />
  <input type="hidden" name="uri" value="rocketthemeblog" />
  <input type="hidden" value="en_US" name="loc" />
  <input type="submit" value="Join" class="readon" name="Submit" />
</form>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

|       Option      |                             Setting                             |
| :---------------- | :-------------------------------------------------------------- |
| Title             | `Newsletter`                                                    |
| Custom Variations | `fp-bottom-c rt-modtitle-uppercase hidden-phone wow fadeInDown` |

Leaving everything else at its default setting, select **Save**.
