## Background

Tabletop RPG’s are a very popular pastime, and it involves a large amount of paper, pens, dice, memory and writing. I know from personal experience of both playing and running games like this, that  most players are rather atrocious at remembering to bring such essentials with them; myself included. Because of this, I wanted to create a site that acted as some of those tools that a player or games master could not misplace or forget. Hence why the site is called RPG tool kit. 

## Evaluation

The problem I sought to solve had more faucets than I initially assumed. The first problems that came to mind were those that I successfully addressed to a degree; the dice roller being the first I chose to tackle.
Dice play a key role in any table top game, and there are several kinds; especially regarding dungeons and dragons. I would have liked to implement a way to add multiple rolls, or allow the user to add their own modifiers, but I already ran into issues getting the ‘roll’ function to parse the selected dice. Overall, I think the dice roller was a moderate success; it picks a random number as a dice does and has all the options available for most games played.
Another integral part of tabletop games that most players struggle with, or at least, I struggle with; is keeping track of spells or inventory. The reason I am addressing these at the same time, is the JavaScript used for both pages is effectively identical. This is because at the end of the day, they are effectively both just lists, populated by a user. 
for the spells, the list can be expanded and shortened using the buttons and has all the necessary columns for any game that may require it. The inventory works in the same way. I would have liked to include a search feature for when the list became overpopulated; but all the methods involved jQuery, which was outside the scope of the criteria, so I chose to avoid it. Another feature I would have ideally had is drop down menus for quantity would be ideal, and a search function would not go amiss either, perhaps a total weight calculator for the items in the inventory.
The site could benefit from more features, such as a character sheet editor and perhaps a page to find resources like handbooks and rulebooks. The former of the two, the character sheet, I had attempted. However, I could not make it functional and readable, whilst keeping it responsive. The other option was using an embedded document reader(www.pdftron.com was what I was considering), but that would be code I did not produce myself. 
I tested my site by hosting it on an apache server on a raspberry pi 1st gen. . Whilst excessive, it meant I could test the site easily on every device I had, alongside using the tools chrome provides. I also intend on using the site personally, so the self-hosting option made the most sense. The issues I immediately came across were with the scaling of the dice roller, as well as all the buttons for the two lists (inventory and spell book). The site itself is designed with mobile use in mind, more so than desktop. This is because in the case where the site is being used, often it will be through a mobile device. I decided this through personal experience, as most times I or most people play, they do not have a laptop Infront of them; however, everyone always has a phone to hand. This, however, was more difficult than I had anticipated with the tables. The two tables are too wide to fit on a narrow, portrait display, and require the device to be in landscape to fit.
##design
The design I decided upon was as simple as possible, whilst being easy to read and understand. This is because the site is a tool and should be easily used by anyone; the high contrast large lettering and simple layout means that any user can immediately ascertain what they are looking at or using, without being distracted by it.
##W3C accessibility
with the application of the site in mind, there was not a lot of need for any changes to comply with W3C accessibility standards, or with the GDPR. I did, however, pick high contrast colours. I did not want to opt for black and white, or the typically more garish pairings. I chose a dark teal-like colour, and a more pastel yellow. They are contrasting, but not entirely offensive to the eye at the same time. All the font is large, clear and plain, and the names of each component clear and concise. I labelled all elements of my pages, although, some failed to be recognised in testing. To test whether my site conforms to W3C standards, I used the accessibility tool in the inspector for chrome/ Firefox. With this, I was able to check whether the contrast and size of my text met standards, which they do, between AA and AAA. I also checked whether all elements were sufficiently labelled, which most are, apart from some form elements.
the main issues I had with accessibility though, were with making all the pages responsive. The dice roller and index went as planned, but the spell book and inventory were often oversized on most devices. The table is wider than it is long, and the entirety fits on a landscape display. 

## distance selling

my page sells nothing and requires no rights or any form of user information.





## wireframes

![index desktop](/assets/desktop_index.png)
![index mobile](/assets/mobile_index.png)
![dice roller desktop](/assets/desktop_dice.png)
![dice roller mobile](/assets/mobile_dice.png)
![spellbook/inventory](/assets/inventory.png)
