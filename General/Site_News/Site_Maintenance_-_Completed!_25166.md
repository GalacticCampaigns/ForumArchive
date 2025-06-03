# Site Maintenance - Completed!

### **Alicia** (2012-01-26 21:34:01)

The site will be down for maintenancefor an unknown period of time. It is recommended you like our facebook page to be kept informed of updates. The time the site will be down will be known closer to the downtime date.
Please keep an eye on this thread as this downtime may be delayed due to time restraints in the prep work. All changes are being prepared on a test forum to ensure things will go smoothly.
Feel free to assist in the testing by joining: <!-- m -->[http://galacticcampaigns.com/test/forum/](http://galacticcampaigns.com/test/forum/ "http://galacticcampaigns.com/test/forum/")<!-- m -->
**Note**: All accounts/posts made on the test forum will not be saved, but all assistance in making sure everything is working will be appreciated!
This maintenance period will include:

* update to phpBB version 3.0.10
* Modification clean up (all mods will be freshly installed with latest versions)

  PeopleSign Captcha
  Prime Birthdate Registration
  User Blog (with Post Model integration)
  Dice Mod
  Post Models
  ReIMG Image Resizer
  Advertisement Management
  Board3 Portal
  Mods Database
  *New* Paypal Donation
  Global Announcements on Index
  Multiple Newsltetters
  *New* Forum SEO
and more
* Chat room will be freshly installed and integrated
* New Mobile style version install

[[View iframe content: https://docs.google.com/spreadsheet/pub?hl=en_US&amp;hl=en_US&amp;key=0AjHYulLjxAGXdHhiamttbDZKMENKc1B2RmNERGNidUE&amp;single=true&amp;gid=4&amp;output=html]](https://docs.google.com/spreadsheet/pub?hl=en_US&amp;hl=en_US&amp;key=0AjHYulLjxAGXdHhiamttbDZKMENKc1B2RmNERGNidUE&amp;single=true&amp;gid=4&amp;output=html "https://docs.google.com/spreadsheet/pub?hl=en_US&amp;hl=en_US&amp;key=0AjHYulLjxAGXdHhiamttbDZKMENKc1B2RmNERGNidUE&amp;single=true&amp;gid=4&amp;output=html")

---

## Re: Site Maintenance - Sunday 5 February

### **jaybee3** (2012-01-27 04:10:03)

Tried registering on the test site and get the following error:
"One of your responses below was not correct."
It doesn't actually flag anything either, so I don't know what my incorrect response was.

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 09:29:08)

I'd been noticing AutoMod wasn't installing things on the style (one of the reasons I rarely use it). I'll make sure that the PeopleSign Captcha was installed onto the themes here shortly.
> **Edit:**
>
> I&#39;ve verified that the PeopleSign and Prime Birthdate mods used during registration are working properly on xabbBlue and on the new Mobile theme.
> Make sure you&#39;re answering the PeopleSign correctly. I might consider switching to reCaptcha if they&#39;ve fixed their hackability

---

## Re: Site Maintenance - Sunday 5 February

### **jaybee3** (2012-01-27 09:58:58)

I think the problem might be...I can't even see the capcha. (email and password redacted)
<details><summary>Spoiler</summary>

[attachment=0]signup.PNG[/attachment]

</details>

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 10:06:36)

Are you trying this from work? Maybe it's being blocked.
> **Edit:**
>
> I think that might be the case as I see the two HR lines where it would go in between.

---

## Re: Site Maintenance - Sunday 5 February

### **jaybee3** (2012-01-27 10:58:38)

Agreed, I've had troubles with certain capchas before.

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 12:08:33)

I installed a different Captcha.. Let me know what you think.

---

## Re: Site Maintenance - Sunday 5 February

### **jaybee3** (2012-01-27 12:46:30)

Apart from making me feel a little motion sick, I like it <!-- s:) -->![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)<!-- s:) --> Since I can access. Feedback posted on test site.

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 12:48:57)

I'm experiencing a WTF moment as I look at the posts in the test forum and no text is appearing <!-- s8/ -->![8/](https://i.ibb.co/kVxpy8vX/icon-eek.gif)<!-- s8/ -->
This is why I do a test board!

---

## Re: Site Maintenance - Sunday 5 February

### **jaybee3** (2012-01-27 12:50:59)

Yeah exactly what I've got, hence me posting with the titles <!-- s:) -->![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)<!-- s:) --> Even when editing the text has completely disappeared.

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 12:52:24)

> **jaybee3 wrote:**
>
> Yeah exactly what I&#39;ve got, hence me posting with the titles &lt;!&ndash; s:) &ndash;&gt;![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)&lt;!&ndash; s:) &ndash;&gt; Even when editing the text has completely disappeared.

Hmm... Going to check the database to see if the post body is being updated into the tables.
Worse case scenario is I go slower.. Restart from the beginning as far as mods go.. again.
> **Edit:**
>
> That&#39;s the problem.. The post body isn&#39;t being inserted into the database. HMMM&#8230;. &lt;!&ndash; s?) &ndash;&gt;![?)](https://i.ibb.co/ynksRzZt/icon-question.gif)&lt;!&ndash; s?) &ndash;&gt;
> 2. There&#39;s 3 or 4 mods that would have interfered with the post process.. Blogs, Post Models, Dice Mod.. Maybe I&#39;ll take a look at them and see if they messed with the submission process at all.
> Then again.. I think I might just start over and say screw it to AutoMod.

---

## Re: Site Maintenance - Sunday 5 February

### **jaybee3** (2012-01-27 12:57:27)

Yeah thought so, previews work, just not the actual. Erm...
SELECT *
INTO thread
FROM post
<!-- s:) -->![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)<!-- s:) -->

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 15:49:45)

Went in and replaced three files dealing with posting... Will manually install the mods for those three files and see what broke it. I have a feeling though it was the new dicemod version.

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 15:57:08)

> **Alicia wrote:**
>
> Went in and replaced three files dealing with posting&#8230; Will manually install the mods for those three files and see what broke it. I have a feeling though it was the new dicemod version.

I hate it when I'm right... Just did the dicemod install and it's broke again...
> **Edit:**
>
> Test forum has been fixed and Post Models are working normally. Dice Roller is not installed

---

## Re: Site Maintenance - Sunday 5 February

### **Alicia** (2012-01-27 20:54:56)

For anyone paying attention to the checklist, my goal is to have up to level 3 priority completed for at least the xabblue and mobile styles before I take it live.

---

## Re: Site Maintenance - Date To Be Determined

### **Alicia** (2012-02-04 16:12:50)

Due to some set backs the date of the maintenance will be announced at a later date. My goal is to have this done before the end of February.

---

## Re: Site Maintenance - Date To Be Determined

### **Alicia** (2012-02-05 14:52:42)

A new version of the Chat room has been installed.
It would be appreciated if you could give it a test run.
Just use the Chat room button located in this site's Nav.

---

## Re: Site Maintenance - Date To Be Determined

### **jaybee3** (2012-02-06 10:04:23)

Chat room looks good, Ali. It's saving the last 10-20 previous messages. Works really well. I like <!-- s:) -->![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)<!-- s:) -->

---

## Re: Site Maintenance - Date To Be Determined

### **Alicia** (2012-02-11 22:10:56)

It might have been noticed Spoiler2 bbcode was not working anymore. As of now all instances have been replaced with the correct spoiler tag and all posts should now be parsing the BBCode correctly.
Please use the report post utility if you see anything amiss.

---

## Re: Site Maintenance - April 30th

### **Alicia** (2012-04-21 20:18:47)

I have decided to do the maintenance April 30th. The site will be down from 12pm EST until the completion. An email notification will be sent out before being taken down and upon being completed. You can also keep an eye on the Facebook page for status updates.
I apologize if this cuts into the posting time of any members.

---

## Re: Site Maintenance - April 30th

### **Alicia** (2012-04-24 12:21:49)

Anyone want to give the new mobile version a try?
Just go to <!-- m -->[http://galacticcampaigns.com/test](http://galacticcampaigns.com/test "http://galacticcampaigns.com/test")<!-- m --> on your mobile device.
Looking for feedback from those who use blackberry and android devices.

---

### **Alicia** (2012-04-30 12:26:09)

Maintenance has been completed.
Please use the guidelines [http://galacticcampaigns.com/forum/viewtopic.php?f=93&amp;t=24975](http://galacticcampaigns.com/forum/viewtopic.php?f=93&amp;t=24975 "http://galacticcampaigns.com/forum/viewtopic.php?f=93&amp;t=24975")to report any issues.



<span style="font-size: 0.5em;">***Last Modified**: 4.0.28 - *2025-06-02 21:35:32 EDT*</span>