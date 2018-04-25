# Distribution of Eocene Primates: a Google Earth Interactive

	By: Kelsey Ellis - Updated Version 2018-04-24
	Final project for the Primate Evolution course at the University of Texas at Austin

***

### Background

The current **Primate Fossil Database** has limited information about where fossil primates are found. The static maps provide students with a general sense of superfamily distribution, but not the geographic distribution of genera or species, nor how prolific some genera are in comparison to others (Fig. 1).

![Static Map](/images/Image02.jpg)
>Figure 1. Current static map found for the Eocene epoch on Fossil Primate Database.
 
Thus, my project aims to update the Primate Fossil Database website to include interactive Google Earth maps of fossiliferous sites that allow students to link to the localities of where specific fossils are found in Google Earth, as well as link to fossil primate information on the Primate Fossil Database website from Google Earth.

***
### Implementation

First, for each fossil primate with a subpage I would like to build a hyperlink to the Google Earth distribution map. This hyperlink could easily be placed under the distribution heading within the characteristic table at the top of each fossil page (Fig. 2).

![Figure 2](/images/Image03.jpg)
>Figure 2. Example of how hyperlink should be placed within the characteristic table that will link to Google Earth.

Here is a complete list of the fossil genera that will need hyperlinks added to their subpage:

**Omomyoids:** 
*Nannopithex, Necrolemur, Absarokius, Anaptomorphus, Pseudotetonius, Teilhardina, Tetonius, Shoshonius, Washakius, Hemiacodon, Macrotarsius, Omomys, Rooneyia*.

**Adapoids:** 
*Adapis, Leptadapis, Cantius, Notharctus, Pelycodus, Smilodectes, Donrussellia, Mahgarita, Hoanghonius*.

**Anthropoids:**
*Eosimias, Apidium, Parapithecus*.

Second, I would like to embed the entire Google Earth distribution map (created in Spreadsheet Mapper v3.1) at the bottom of the Eocene description page under the static map already provided (Fig. 3). The Google Earth file (.kmz) to be embedded is attached in the IT folder.

![Figure 3](/images/Image04.jpg)
>Figure 3. Example of where Google Earth map should be embedded below static map.

I have already provided links back to the Fossil Primate Database website within the Google Earth .kmz file. To embed the Google Earth interactive map, please follow the protocols for ‘Installing the Google Earth Plugin” and “Loading Additional Databases” found under [Google Earth APIs developer guide](https://developers.google.com/earth/documentation/index).

As a side note, we may want to update epoch maps to these more realistic maps, however, I am unable to add locational data:

*Eocene map*

![Figure 4](/images/Image05.jpg)

*Oligocene map*

![Figure 5](/images/Image06.jpg)

*Miocene map*

![Figure 6](/images/Image07.jpg)


***
### Tour/Tutorial

To get a better sense of the interactive capabilities of the Eocene Primate Distribution Map, I have uploaded the Google Earth .kmz file to my GitHub and provided links to download Google Earth.

This is located in the [Distribution of Eocene Primates](https://github.com/kelseyellis/Distribution_of_Eocene_Primates) folder in my GitHub account.  

Now that you’ve downloaded Google Earth and the Primate Fossil Placemarks, let’s take a little tour.

First, you will need to unhide the placemarks by clicking on the small arrow next to the checked box for the Distribution of Eocene Primates files.

![](/images/Image08.jpg)

The folders that are now visible represent geological formations in which primate fossils are found. 

Now let’s check out the Willwood Formation. To do so, scroll down towards the end of the column and double click on the folder titled Willwood.

![](/images/Image09.jpg)

Google Earth has now flown to Willwood, Wyoming and the placemarks representing Omomyoids (pink) and Adapoids (blue) are shown. 

If you click on one of the Teilhardina links in the left column, the corresponding placemark will be highlighted with a text bubble that contains images and links back to the Primate Fossil Database. It may be necessary to enter the username and password information for the website (currently withheld).

![](/images/Image10.jpg)

It is not always necessary to click on the genera links to the left, you may also click on the placemarks themselves to view the fossil information.  As you hover your mouse over each placemark the name of the genera will pop up. Let’s see if you can find one of the fossils attributed to Notharctus (hint: it will be a blue placemark).

![](/images/Image11.jpg)


