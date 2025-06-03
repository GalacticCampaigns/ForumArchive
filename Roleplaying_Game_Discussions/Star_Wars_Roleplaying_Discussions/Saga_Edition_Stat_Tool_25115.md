# Saga Edition Stat Tool

### **Alicia** (2011-11-04 10:41:33)

I've been working on this the last week and wanted to get some input into features. While I don't intend for this to be a generator, I would like to encompass as much material as possible which will effect a character.
The following is a supplement to character creation and should not negate the standard character creation process.
Enjoy!
<span style="font-size: 1.50em;">[Star Wars Saga Edition Stat Tool](http://galacticcampaigns.com/stattool.php "http://galacticcampaigns.com/stattool.php")</span>
<span style="font-size: 1.25em;">Change Log and Future Updates</span>
[[View iframe content: http://swrpgrc.com/statTool/changelog.html]](http://swrpgrc.com/statTool/changelog.html "http://swrpgrc.com/statTool/changelog.html")

---

### **BWS2K** (2011-11-04 13:40:57)

Looks awesome! <!-- s:D -->![:D](https://i.ibb.co/MDcFvFDD/icon-e-biggrin.gif)<!-- s:D -->

---

### **Alicia** (2011-11-10 19:52:28)

I need some assistance from you book worms...
Help me make a list of talents and feats which changes the modifier to attack and damage:
Weapon Finesse = use dex in melee instead of Str with light weapons
Ataru = use dex instead of str in melee for damage when using lightsabers
Noble Fencing Style = use CHA in melee with light weapons
etc etc. Just want to make sure I get them all.
Likewise if there's anything else out there that gives permanent bonuses to attacks or damage include that as well. If it doesn't work then I just won't include it. Reference to Weapon Focus and Specialization is not necessary.

---

### **DarthAnthrax** (2011-11-11 15:34:08)

Hmm, I actually think you got them all. However, since they are in the same vein, and just in case you forgot them, there are four feats that allows you to use another stat for your defenses, all from Galaxy at War:
**Resilient Strength** - Lets you use Str instead of Con for Fortitude Defense
**Predictive Defense** - Lets you use Int instead of Dex for Reflex Defense
**Force of Personality** - Lets you use Cha instead of Wis for Will Defense
**Fight through Pain** - Lets you use Will instead of Fortitude as the base for your Damage Threshold
For more permanent bonuses to attack/damage I can think of a few, but most I know of are situational in some way:
**Melee Smash** - Permanent +1 damage to melee attacks (Soldier talent)
**Primitive Warrior** - Permanent +1 dice of damage with simple melee weapon, only for Gamorreans (Rebellion Guide, feat)

---

### **Alicia** (2011-11-11 18:43:52)

Thanks for the list DA. Looks like I'm going to have to go back and reconsider defenses. Would you think for each defense it's feasible to assume someone would only take one talent/feat to change that respective defense? Thinking I might just incorporate a drop down menu for each defense so the option can be chosen.
<span style="font-size: 0.80em;">***[ Post made via Mobile Device ]***</span>

---

### **BWS2K** (2011-11-11 19:56:55)

If you do a dropdown, do you have to limit it to only one selection? If I was to pick one from a dropdown menu, could it include that one and then underneath it create another empty dropdown field that I could choose another from? Just a thought, and I'm not sure I'm even using the correct terms. <!-- s:red: -->![:red:](https://i.ibb.co/xStHX79F/icon-redface.gif)<!-- s:red: -->

---

### **DarthAnthrax** (2011-11-11 20:11:10)

> **Alicia wrote:**
>
> Thanks for the list DA. Looks like I&#39;m going to have to go back and reconsider defenses. Would you think for each defense it&#39;s feasible to assume someone would only take one talent/feat to change that respective defense? Thinking I might just incorporate a drop down menu for each defense so the option can be chosen.
> <span style="font-size: 0.80em;">***[ Post made via Mobile Device ]***</span>

I remembered that there´s a Noble talent that mimics the effect of Force of Personality, **Idealist** (Force Unleashed). And while I could see most builds using only one of these feats, I think the option to use more than one should be open. Since it´s a pretty limited number of options available, wouldn´t check boxes work quite well?

---

### **jaybee3** (2011-12-20 11:25:57)

Some testing feedback for ya:
**Bug:** If you select a Size greater than Medium from the dropdown and then select something smaller than Medium (i.e. without the CON bonus) it will keep the CON bonus. (Medium seems to reset the fields, from what I see: Fine, Diminutive, Tiny and Small aren't setting their appropriate bonus for CON.)
I don't know if this is deliberate or a bug:
[**Bug 2:** When you click "Start Over" it doesn't reset the Name, Sex, Race and Levels textboxes.]
**Bug 3:** Use Cha? Isn't working for either Fort or Will
**Bugs 4 and 5:** I don't know if the above is related to the below, but I got a couple of errors on the page:
"Object doesn't support this property or method" in defenses.js line 56 char 2 &
"Object doesn't support this property or method" in skills.js line 76 char 2

---

### **Alicia** (2011-12-20 21:48:20)

> **jaybee3 wrote:**
>
> **Bug 3:** Use Cha? Isn&#39;t working for either Fort or Will

Can't be duplicated. The feature is working fine on my end
> **jaybee3 wrote:**
>
> **Bugs 4 and 5:** I don&#39;t know if the above is related to the below, but I got a couple of errors on the page:
> &quot;Object doesn&#39;t support this property or method&quot; in defenses.js line 56 char 2 &amp;
> &quot;Object doesn&#39;t support this property or method&quot; in skills.js line 76 char 2

What browser are you getting these errors on? I'm not getting them on IE or FireFox

---

### **jaybee3** (2011-12-21 05:07:33)

> **Alicia wrote:**
>
> > **&quot;jaybee3&quot; wrote:**
> >
> > **Bug 3:**

Can't be duplicated. The feature is working fine on my end
> **jaybee3 wrote:**
>
> **Bugs 4 and 5:**

What browser are you getting these errors on? I'm not getting them on IE or FireFox
The two/three seem to be related as I get the error messages when I try and change the Cha. I'm running IE 8.0.6001.18702CO.
I've also had trouble staying logged in recently too. Seems to keep booting me off after being idle for 30mins or so. Whereas before I could log off and on and I could still be logged in. I think they may have changed cookie policy at work.

---

### **Alicia** (2011-12-21 11:01:20)

> **jaybee3 wrote:**
>
> Some testing feedback for ya:
> **Bug:** If you select a Size greater than Medium from the dropdown and then select something smaller than Medium (i.e. without the CON bonus) it will keep the CON bonus. (Medium seems to reset the fields, from what I see: Fine, Diminutive, Tiny and Small aren&#39;t setting their appropriate bonus for CON.)
> I don&#39;t know if this is deliberate or a bug:
> [**Bug 2:** When you click &quot;Start Over&quot; it doesn&#39;t reset the Name, Sex, Race and Levels textboxes.]

This will be fixed in my next upload.

---

### **Alicia** (2011-12-21 12:10:59)

> **DarthAnthrax wrote:**
>
> Hmm, I actually think you got them all. However, since they are in the same vein, and just in case you forgot them, there are four feats that allows you to use another stat for your defenses, all from Galaxy at War:
> **Resilient Strength** - Lets you use Str instead of Con for Fortitude Defense
> **Predictive Defense** - Lets you use Int instead of Dex for Reflex Defense
> **Force of Personality** - Lets you use Cha instead of Wis for Will Defense
> **Fight through Pain** - Lets you use Will instead of Fortitude as the base for your Damage Threshold

I think what I've decided to do is use a drop down menu which will let the user choose which ability will be the predominate, this way it's not feat/talent specific and will allow for better customization for homebrewn abilities. I'll likely do the same for attack/damage as well.

---

### **Alicia** (2012-08-20 23:02:44)

Update was a long time coming. BUT I resolved the major issue with the Armor calculating into the Defenses (or at least I think so). Also, basic Attacks and damage have been added making this a functioning addition.
Including stat changes from feats and talents is coming.
For Attacks and Defenses I think I'm just going to use a drop down for each attribute respectively and let you pick which stat to use in the default's place. I think this will function much better in the long run particularly if the GM introduced their own talents/feats.
Keep up the feed back regarding additional features which should be included as part of the standard calculations. Once these are done I'll probably work on introducing species including droids.
I can't believe I put this aside for 8months..... Back to work!



<span style="font-size: 0.5em;">***Last Modified**: 4.0.28 - *2025-06-02 21:35:57 EDT*</span>