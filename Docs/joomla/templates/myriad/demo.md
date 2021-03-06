---
title: Myriad: Recreating the Demo
description: Your Guide to Recreating Elements of the Myriad (Gantry 5 Edition) Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/myriad:Myriad

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Myriad can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Myriad Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Particles
-----

Here is a list of particles that are available in Myriad, as well as links to documentation to help you get started:

>> All Home Particles can be edited via Templates > Myriad - Home - Particles > Layout. Any additional particles that are found in the Subpages of our Myriad RocketLauncher can be located via your Joomla Administrator > Extensions > Modules. Joomla allows you to search for Modules by Page (see Search Tools > Select Page in Module Manager), so finding these modules should prove to be simple.

* Template Particles
    - [Case Studies](particle_case.md)
    * [Contact](particle_contact.md)
    * [Content List](particle_contentlist.md)
    * [Content Tabs](particle_contenttabs.md)
    * [Features Slider](particle_featuresslider.md)
    * [Joomla Articles](particle_joomla.md)
    * [Headlines](particle_headlines.md)
    * [Image Grid](particle_image.md)
    * [Info List](particle_info.md)
    * [Lists](particle_lists.md)
    * [Newsletter](particle_newsletter.md)
    * [Promo Image](particle_promoimage.md)
    * [Simple Counter](particle_simplecounter.md)
    * [Strips Slider](particle_stripsslider.md)
    * [Tab Image](particle_tabimage.md)
    * [Testimonial](particle_testimonial.md)
* Core Particles 
    - [Logo](http://docs.gantry.org/gantry5/particles/logo)
    - [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    - [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    - [Social](http://docs.gantry.org/gantry5/particles/social)
    - [Positions](http://docs.gantry.org/gantry5/particles/position)
    - [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    - [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    - [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    - [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    - [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recreating the Front Page
-----

The front page of the Myriad demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Myriad demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

If you did not choose to 'Install Sample Data' upon installing the Myriad theme, we have included a convenient layout preset that enables you to load the home page as seen in our demo. This preset is called **Home** and it includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access this preset by selecting **Load** in the **Layout Manager**.

>> Note: We have made presets available for several of our additional demo pages, including: **About Us**, **Portfolio**, **Services** and **Team**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Myriad has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Myriad > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Myriad** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
