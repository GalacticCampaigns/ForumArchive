# Feature - Dice Rolls

### **Alicia** (2010-01-07 19:03:44)

Dice Rolls can now be applied to forum posts by all registered users. They are inserted via the dice command by entering a <span style="font-size: 1.25em;">*n*d*n*</span> statement such as 3d6 or 1d20. All dice formats are recognized (even some odd ones like 1d2).
Modifiers and calculations can be incuded.

* Supports addition, substraction, multiplication and division of float values.
* Supports only one calculation in one bracket set.
* Supports negative numbers.
* Choose to show the dice 'string', 'total' or both

Here's a list of all dice code commands:

* **Common Roll**

```
[dice]1d20[/dice]
```

***2*** <- [2] 1d20

* **Dice Crafting** (Dice crafting can only be performed by GMs. This would produce a d20 roll of an 18)

```
[dice]d20:18[/dice]
```

***18*** <- [18] 1d20

*Multiple dice*

```
[dice]d6:1,2,3,4[/dice]
```

***10*** <- [1, 2, 3, 4] 4d6

*Multiple dice with modifier*

```
[dice]d6:1,2,3,4+10[/dice]
```

***20*** <- [1, 2, 3, 4] 4d6 + 10

* **Total** (displays only the total of all dice rolled)

```
[dice=total]1d20[/dice] 
```

***5*** <- [5] 1d20

* **String** (displays only the individual dice rolled)

```
[dice=string]1d20[/dice] 
```

***19*** <- [19] 1d20

* **Both String and Total**

```
[dice=string, total]1d20[/dice] 
```

***12*** <- [12] 1d20

Only moderators and administrators can delete or re-roll a user's dice. When a user edits his or her post the roll will appeared parsed as:

```
[dice]0[/dice
```

If a change is attempted, upon submitting a screen will load informing the user to contact a mod or admin to have the roll changed.
Moderators and admins can click the [Make Removable] link next to a particular roll in the post so the user may delete or re-roll.

---

A post model for ease of including a pre-formatted roll system has been added to the drop down.
***** +mod - replace * with skill name and +mod with the skill modifier
dice code - 1d20 is already entered here
**Attack** weapon +mod (special notes) - Replace weapon with item being used to attack, the +mod with attack modifier and in () put any special attack notes, IE. PBS included, autofire, burstfire, Devastating Attack, etc.
dice code - 1d20 is already entered here
***damage*** +mod - Replace +mod with your damage modifier.
dice code - enter your weapon damage into the dice tags
If you don't need all of the code just delete what you don't need. You can always insert the code again or copy and paste parts of the template you do.

---

### **Alicia** (2010-06-01 11:14:26)

Testing update

***2*** <- [2] 1d6

Dice are now only available in the gaming forums. Dice had to be allowed in each forum individually. For now only the game forums will have access to it.
Because permissions are manually set, if yours was excluded please PM me.

---

### **Alicia** (2011-07-25 12:21:29)

Testing update (0.8.1)

***10*** <- [10] 1d20

***29*** <- [19] 1d20 + 10

***30*** <- [6, 2] 2d20 + ()+30

***19*** <- [3] 1d20 + 16

***20*** <- [1, 1, 4, 1, 3] 5d6 + 10

***33*** <- [5, 2, 6] 3d8 + 20

***6*** <- [1] 1d1 + (+12)/2

<span style="font-size: 1.20em;">**Changelog:**</span>:
**0.8.1:**

* Added a math parser.
* Supports addition, substraction, multiplication and division of float values.
* Supports only one calculation in one bracket set.
* Supports negative numbers.
* The dice roll must be in the deepest bracket layer.
* The function is simply written around the standard rolling code
* Using a function automatically displays the total value, no need for the total tag
* Example:

  ***9000*** <- [2, 7, 16] 3d20 + 10/(+3)*-2.5)
* To change the function on an existing roll, do as with the previous example, but surround the roll id with f( )
* Example: [Invalid dice roll_id: 10/f(0)*-2.5)][Invalid dice roll_id: 10/f(8)*-2.5]
* To remove a function from a dice roll, surround the roll id with nomath( )
* Example:
* Changed the way missing or redundant roll ids are handled durin posting:
* Missing dice rolls are added at the bottom of the post
* Redundant dice rolls are removed, only the first code is kept.
* Significant refining changes to old code.

---

### **Alicia** (2012-06-06 19:45:12)

<span style="font-size: 1.20em;">**Changelog:**</span>:
**0.8.8b:**

* added a crucial forgotten line to install instructions that prevented the mod from working at all
* small bugfix to posting.php which caused empty array errors
* fixed dicemod acp module php

**0.8.8:**

* a number of little Bugs found and fixed
* fixed Bug that prevented usage of ' in posts containing dicerolls
* rearranged Code
* made Mathparsing Depth available for configuration in ACP
* created "default dicemode" as a forum option
* replaced the modes total and totalonly with combinable modes string and total
* if only the total is displayed, the bbcode replacement now shows the diceroll as hovertext

Tests:

```
[dice]10d20[/dice]
```

***89*** <- [2, 15, 20, 15, 2, 12, 5, 5, 5, 8] 10d20

---

```
[dice=total]10d20[/dice]
```

***104*** <- [13, 18, 2, 12, 6, 17, 7, 13, 11, 5] 10d20

---

```
[dice=string]10d20[/dice]
```

***105*** <- [2, 9, 3, 9, 13, 20, 2, 17, 14, 16] 10d20

---

```
[dice=string,total]10d20[/dice]
```

***116*** <- [12, 17, 17, 10, 13, 11, 20, 10, 4, 2] 10d20

---

### **Alicia** (2013-02-27 23:50:33)

Updated first post with better explanation of dice commands.

---

### **DarthAnthrax** (2013-03-02 21:57:59)

Maybe I´ve missed something on how to use the latest update of the dice code, but it won´t roll a single die with modifiers for me.
**Test**

***25*** <- [17] 1d20 + 8

**Edit** Interesting...it works here, but not when I tried it in a game forum...



<span style="font-size: 0.5em;">***Last Modified**: 4.0.28 - *2025-06-02 21:35:28 EDT*</span>