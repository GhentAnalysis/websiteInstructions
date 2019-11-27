The website https://epp.ugent.be/ was set up by Ward Van Driessche end 2018 with the help of Bart Vancauteren (IT department) and Sander Vanheule (manusje-van-alles)

Below, some information can be found on how to change the website.

READ ALL THE RULES EVEN IF YOU DON’T THINK YOU NEED THEM

Important to note is: the website uses wordpress, which makes implementations fairly easy and no knowledge of html/css is required. Problems can be easily found on Google!

Rule no 1: if you have a problem, google it!


# General information

If you want to make adjustments to the website, surf to https://epp.ugent.be/wp-admin

Username: ugentfysicaensterrenkunde
Ask password to someone who knows it

You’ll land on a wordpress design page where you can find everything you need to make adjustments

Rule no 2: please keep the plugins a bit up to date. Just press the “updates” button below “home” and “select all” and update

Regularly updating plugins has the disadvantage that the way something has to be changed/added/… changes. Usually, this is to your advantage. Don’t be a dinosaur that hates change.
PS: it is possible that the guidelines in this text are not always up-to-date just because of this.

Who is the admin? The current admin is bart.vancauteren@ugent.be (PLEASE KEEP THIS UP TO DATE), this can be found under “Settings”/”General”.

# Make a backup

On the side panel you can find a “All-in-One WP Migration” plugin, “export” the website to “file” (first option in the dropdown menu). This file can be used to “import” the entire website.

Rule no 3: before you make major adjustments, or at regular points in time: MAKE A BACKUP

# What are plugins?

Plugins are very useful tools that are provided by the large wordpress community. For example, there is no easy way to implement a table that lists a bunch of things, such as the PhD theses: https://epp.ugent.be/index.php/phdtheses/

Therefore, I searched for a table plugin that does exactly this! 

# How to install a plugin? 

Press “plugins” on the side panel, you’ll find a list of the installed plugins there. Press “add new” to implement a new plugin and don’t forget to activate it. How to use the plugin is usually explained on the page of that plugin.

How to change something on the website?

First, let me explain how the website is set up. Please read this first, before you make changes. It’ll make your life much easier.

The website uses “Pages” that each contain some information. The menu you can read on the main page of the website (About us, Research, etc.) simply links to a certain page. That’s it. No more, no less.

If you need to change a page: go to “Pages” on the left side panel, find the right page and edit!
Example: click on “2016-2017”, which is a page where the seminars of that year are listed. The text can be easily updated and get yourself a bit familiar with all the options. You can add quotes, color your text, add images, etc. I won’t go over all the options, have a look yourself and now you know where to find the source code of all the pages. If you want to duplicate some feature from another page, find the according page and see how it’s done. Don’t forget to update your page and check if all your implementations were correct!
Rule no 4: If you make changes, be consistent in style and try to make it nice to read. The person reading this is probably a physicist who doesn’t care too much for this, but all your effort in having a nice text is probably for nothing if it looks like it’s been copied from a telegram.

If you need to add a page: go to “Pages”, and “add new”. Now the page exists, but it’s not linked on the website anywhere. Go to “How to customize” in the text below how to do so.

# How to customize?

On the side panel, click “appearance” and then “customize”.
You’ll need this if you want to:
Change the general appearance of the website
Change the main page (text and/or images)
Change the bottom bar with the RSS feed etc
Change the menu (removing or adding items)

First, you can completely change the whole style of the website by changing the theme, which is now set to “Spacious”. I DO NOT RECOMMEND TO DO THIS BEFORE MAKING A BACKUP. AND YOU’LL NEED A LOT OF TIME TO SET EVERYTHING UP AGAIN.

You’ll find edit buttons on the page now, these are very handy if you want to make quick changes. For all others, you’ll need to go through the text below or find it yourself!

The bottom sidebars can be changed by pressing “widgets” and editing the “Footer Sidebar X” options

The menu can be changed by pressing “Menus” and “Primary”. You’ll see the structure of the menu in here. The workings are fairly easy: if a menu point is a collection of multiple pages but not a link in itself (e.g. Research), this is a custom link that doesn’t link to any page (URL = #).
Pages can be reshuffled with the mouse. Indentations indicate subsets of a link.
If you want to add something to the menu: press “add items”. Now you can choose between custom links (e.g. Research), pages (almost everything is a page) or other options which I haven’t used up to now. If the page already exists, simply locate it and click it. Now you can move it to the right place on the left. If the page does not exist yet, just add a new one (make sure it has a good name! This will also be the name of the url! For example, the page “IceCube” can be found under the link: https://epp.ugent.be/index.php/icecube/). The new page will now be empty, but can be changed in the “Pages” menu as explained in “how to change something on the website”.

The slider images on the main page can be changed by pressing “slider”. There is a maximum of 5 images. Add a title to the image and add a link to the correct page if required. For example, the CMS image links to the CMS page! The images should all have the same height/width ratio for an optimal display. Optimal dimensions are 950 (w) by 200 (h) pixels, or 1900 by 400. You can add a new image by pressing “change image” and select one from the library or if you want to add a new one, press “change image” and then “upload image”.

DON’T FORGET TO PRESS “PUBLISH” ONCE YOU’VE MADE CHANGES, OTHERWISE YOUR CHANGES ARE NOT SAVED

# How to add an image?

On the side panel, press “Media” if you want to look at all the images that are currently uploaded. If you want to add a new one, simply press “Add New”. If you have a problem with the upload size limit: talk to Bart Vancauteren.

# How to add a pdf?

This is a useful feature if one wants to upload a PhD thesis. This is the same procedure as uploading an image. This was made possible with a plugin called “PDF Embedder”.

# How to add a table?

Tables can be added with the “Tablepress” plugin. On the side panel, press “TablePress”. You’ll see a list of existing tables. New ones can be added by pressing “Add New”. Simply click on one of the tables to make changes. You can add new rows and columns with the buttons in the “Table Manipulation” menu.

How to add a pdf link in a table? Click on an empty cell and press “Insert Link” under “Table Manipulation”. The url you need to link is the url where the pdf can be found. You can find this url by going to the Media library and selecting your pdf. An url is shown there. 

Don’t forget to save changes!

How to add a table in a page? You’ll find a shortcode for the table under “Table Information”. E.g. [table id=2 /] 
Simply copy this into your page (under “Pages”) and the table will be added to the page!


# How to add an image gallery?

On the side panel, click “Robo Gallery”. This plugin was updated to the pro version, after payment (by prof. dr. Dirk Ryckbosch). The pro version allows to add multiple galleries to the website.

Under “Manage Galleries”, you can find a list of the current galleries that exists. 

# How to add a gallery to a page? 
Copy the shortcode of the gallery and plug this into your page (under “Pages”) and the gallery will be added to the page!

How to add a new gallery? Press “Add Gallery/Images” and go through the large list of options. Best to enable the cache of the gallery to load the website faster. Add images by pressing “Manage Images” and select the ones from the library or add new ones (more info: see “How to add an image”).

# How to change the email contact person?

Currently, emails are sent through smtp.ugent.be, meaning that the recipient should be a ugent email account. Currently this is set to be “eppwebsite@ugent.be”, which is linked the “dirk.ryckbosch@ugent.be”. If Dirk is no longer responsible for this website, you should ask the IT department to link your emailadress to eppwebsite@ugent.be.

If you want to change this, go “Contact” on the left side panel, where only one contact form is set up. Change the settings there. Again, a shortcode for this form is used to link to a page (“Contact” under “Pages”).

# How to remove/add/relocate a person?

Rule no 5: This is something that probably has to be done regularly! Please make time to do this, otherwise the website will look sloppy! (Tip: add a reminder in your agenda to look at this once every month).

We have split the people into several groups. 

Permanent staff: professors, long term contracts...
Research staff: PostDocs, temporary contracts…
PhD students
Master students
Graduated PhDs: this comes in handy to keep track of the people that graduated and can be important for these persons in later job hunting. Add information on their date of graduation and the title of their thesis. See below. This might seem less important as these people have left, but will bite you in the * if you don’t keep track. People forget.
Previous research staff: see bullet above.

Again, we use shortcodes in the “Members” page under “Pages”. These shortcodes are constructed with the “Team Members” plugin. You can find the settings in the side panel on the left under “Teams”. Copy a shortcode to a page and the team list will be shown on that page.
Click on “Members: phd” as an example. You’ll see the people listed as phd students here. Everything is pretty straightforward to implement. Be thorough and list multiple social links when possible. Members can be added by scrolling to the bottom and pressing “Add a Member”. ALWAYS upload a photo. Not having a photo looks very unprofessional! How to add a photo to the library can be found under “How to add an image” in this text.

Don’t forget to save! Press “Update” on the right

I have listed the people chronologically: the one who is here longest is put first. Some people have extra information that becomes visible when you click on it. For example, adding the following in the “Description/biography” will create a “More information” dropdown text.

[expand title="More information"]
Master 1 internship : Incredible
Master 2 internship : Wauw
PhD topic : Bla bla bla
[/expand]
Unfortunately I haven’t found a way to duplicate a contact from one team to another, you’ll have to do this by hand.

Please ask people to provide you with this information. Again: professionalism.

Rule no 6: In September (add this to your agenda!) you update the “Master Students”. Add them to “PhD Students” if they continue in the department or add them to “Graduated Master Students”. They deserve to be recognized for their work. Add their master thesis title to the biography and try to ask for a working email adres. If the PhD students are not up to date, change this as well (this probably should have been done already!). Look at the persons already in the new list and make sure everything is up-to-date for the new person in there! Oh, and maybe make a backup.

LinkedIn is becoming more and more important in the private industry (I hope this will still be true of somebody is reading this in 2020 or later), young students should really have this on their contact information.

