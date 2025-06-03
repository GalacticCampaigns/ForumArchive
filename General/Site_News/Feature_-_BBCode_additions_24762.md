# Feature - BBCode additions

### **Alicia** (2010-07-25 20:17:07)

I will post here when new BBCode additions have been included, which would not be included normally.
A detailed list of BBCode and explanations can be found on the BBCode FAQ <!-- s=> -->![=&amp;gt;](https://i.ibb.co/ZRp1c1RL/icon-arrow.gif)<!-- s=> --> <!-- l -->[faq.php?mode=bbcode](http://galacticcampaigns.com/forum/faq.php?mode=bbcode "http://galacticcampaigns.com/forum/faq.php?mode=bbcode")<!-- l -->
<span style="font-size: 1.50em;">Currently Installed</span>:

* **Alignment** - aligns text center, right or justify

  ```
  [align=center]Content[/align]
  ```
* **Dice roller** - see thread for more info <!– s=> –>![=&amp;gt;](https://i.ibb.co/ZRp1c1RL/icon-arrow.gif)<!– s=> –> <!– l –>[viewtopic.php?f=1&amp;t=24538](http://galacticcampaigns.com/forum/viewtopic.php?f=1&t=24538 "http://galacticcampaigns.com/forum/viewtopic.php?f=1&t=24538")<!– l –>.

  ```
  [dice]1d20[/dice]
  ```
[Invalid dice roll_id: d20:18] (Dice crafting can only be performed by GMs. This would produce a d20 roll of an 18)
[Invalid dice roll_id: 1d20] Total (displays only the total of all dice rolled)
[Invalid dice roll_id: 1d20] String (displays only the individual dice rolled)
[Invalid dice roll_id: 1d20] Both String and Total By default any dice rolled will be displayed as if it had the 'total' tag.* **Edit** -

  ```
  [edit] [/edit]
  ```

  > **Edit:**
  >
  > You can put additional responses here when you edit or use this to keep track of edits on Character Sheets
* **Horizontal line** - places a horizontal ruler through the post. You set the color and the height of the line

  ```
  [hrc=black][/hrc]
  ```
* **iFrame** - Inline Frame is an HTML document embedded inside another, in this case the post.

```
[iframe={height}]URL[/iframe]
```

Replace {height} with the desired height of the iframe. Recommend no larger than 600 and smaller than 200.
[[View iframe content: http://galacticcampaigns.com]](http://galacticcampaigns.com "http://galacticcampaigns.com")* **Image Alignment** - will wrap text around an image. Set align for right or left.

  ```
  [imgal=right]http://[/imgal]
  ```
* **Spoiler** - will hide text within a spoiler window

  ```
  <details><summary>Spoiler</summary>

  Content

  </details>

  ```
<details><summary>This is the title</summary>

The text is contained within the spoiler as normal.

</details>

```
<details><summary>This is the title</summary>

The text is contained within the spoiler as normal.

</details>

```

(Title Spoilers will not appear in most mobile apps, however Spoilers themselves are supported by Tapatalk)* **Steam ID** - show off your Steam profile by linking to an image in your signature or in a post.
To find out your Steam ID, log into your [Steam account](http://steampowered.com "http://steampowered.com"). In the account drop down in the top right, click "View Profile". Your ID will be following <!– m –>[http://steamcommunity.com/id/](http://steamcommunity.com/id/ "http://steamcommunity.com/id/")<!– m –> *It will not be what your name is Displaying as.*

```
[steam]SteamID[/steam]
```

[![Steam Signature for aliciag](http://steamsigmaker.de/komedy/aliciag.png)](http://steamcommunity.com/id/aliciag "http://steamcommunity.com/id/aliciag")* **Tables** - Tables can be used when you wish to put data in a grid-like form. This is an advanced feature and it's recommended you [familiarize yourself in how HTML tables](http://www.webdesignfromscratch.com/html-css/html-tables/ "http://www.webdesignfromscratch.com/html-css/html-tables/") work before attempting.

These are the table codes currently available.
table
td={colspan}
thead
tr={rowspan}

| Column 1 Column 2
|  |
| Example of a simple table The table has 2 columns, each one with a column header.
| The first 2 rows each have 2 cells One cell in each column.

```
[table][thead][tr=0][td=0]Column 1[/td]
      [td=0]Column 2[/td][/tr][/thead]
  [tr=0][td=0]Example of a simple table[/td]
    [td=0]The table has 2 columns, each one with a column header.[/td][/tr]
  [tr=0][td=0]The first 2 rows each have 2 cells[/td]
    [td=0]One cell in each column.[/td][/tr][/table]
```

* **Youtube videos** - Embed a youtube video. Include the code found in the video URL (<!– m –>[http://www.youtube.com/watch?v=XXXXXXXXXXX](http://www.youtube.com/watch?v=XXXXXXXXXXX "http://www.youtube.com/watch?v=XXXXXXXXXXX")<!– m –>, only include the XXXXXX portion)

  ```
  [youtube]XXXXXXXXXXX[/youtube]
  ```

---

### **Alicia** (2010-07-25 20:17:37)

Enabled bbcode for YouTube videos.

---

### **Alicia** (2012-02-08 09:46:55)

Spoiler2 bbcode has been removed and replaced by using "spoiler". All threads using spoiler2 have been changed automatically to spoiler. Please use the report function on any posts with currputed BBcode.
Additionally you may also include a title to the spoiler by using "spoiler=".
<details><summary>This is the title</summary>

The text is contained within the spoiler as normal.

</details>

```
<details><summary>This is the title</summary>

The text is contained within the spoiler as normal.

</details>

```

---

### **Alicia** (2012-06-08 12:42:08)

Updated with current custom BBCode
iFrames
Tables
Dice

---

### **Alicia** (2013-02-27 23:05:01)

Updated with code description for iFrames.

---

### **Alicia** (2013-03-20 12:14:08)

First post updated to include SteamID bbcode description!



<span style="font-size: 0.5em;">***Last Modified**: 4.0.28 - *2025-06-02 21:35:29 EDT*</span>