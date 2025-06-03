# [Resolved] Known Issue: Apostrophes

### **Alicia** (2012-05-07 16:09:21)

The Dice Roller fix had the unfortunate effect of throwing a SQL when a post with apostrophes is submitted. This is only occurring in forums where forum dice has been enabled. As of right now it appears that posts are being submitted in their entirety and is otherwise just a nuisance. Hopefully this issue will be fixed quickly.
Please let me know if this is not the case.

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-07 16:09:44)

"test"

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-07 16:09:57)

'test'
this may throw the error
Do dice work here? [Invalid dice roll_id: 1d20]

---

## Re: Known Issue: Apostrophes

### **jaybee3** (2012-05-07 16:29:05)

[Invalid dice roll_id: 1d20+12] I don't know if this will work

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-07 16:30:36)

Dice aren't supposed to work here so all's good!

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-07 16:32:49)

hmm. got the apostrophe error.. wierd
'test

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-07 17:25:11)

I reverted back to the old code and enabled dice in all forums till the Mod author can devise a fix for the apostrophe issue..
Just to make sure 'test'

---

## Re: Known Issue: Apostrophes

### **jaybee3** (2012-05-08 03:17:30)

What was in the fix anyway? Seemed that the roller was working fine?

---

## Re: Known Issue: Apostrophes

### **jaybee3** (2012-05-08 03:22:50)

General Error
SQL ERROR [ mysqli ]
You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '{SMILIES_PATH}/icon_smile.gif" alt=":)" title="smile" /> Yay for up' at line 1 [1064]
An SQL error occurred while fetching this page. Please contact the Board Administrator if this problem persists.

---

## Re: Known Issue: Apostrophes

### **jaybee3** (2012-05-08 03:25:12)

Yeah smily parsing seems to flag up errors

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-08 09:01:14)

> **jaybee3 wrote:**
>
> General Error
> SQL ERROR [ mysqli ]
> You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near &#39;{SMILIES_PATH}/icon_smile.gif&quot; alt=&quot;:)&quot; title=&quot;smile&quot; /&gt; Yay for up&#39; at line 1 [1064]
> An SQL error occurred while fetching this page. Please contact the Board Administrator if this problem persists.

Just so you know... I really need the whole thing. There's backtrace which will give me where the SQL error is.. otherwise I have no idea what's causing the error above.
BUT! If you were attempting to put a smiley with a dice roll then this is a known error.
The fix I tried to install was to:

* fix Smileys causing SQL errors and disabling usage of dicecode in posts containing Smileys
* fix error causing submitted posts to result empty posts or sql errors in forum that did not allow dice at all

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-08 09:01:38)

testing <!-- s:r2: -->:<!-- s:r2: -->

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-08 09:02:54)

testing [Invalid dice roll_id: 1d20]
getting this SQL error

```
SQL ERROR [ mysqli ]

You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '{SMILIES_PATH}/r2d2line.gif" alt=":" title=":" />", post_che' at line 1 [1064]

SQL

UPDATE phpbb_posts SET post_text = "testing <!&ndash; s:r2: &ndash;>:<!&ndash; s:r2: &ndash;>", post_checksum = "78d3a6b37f5da0f0daabab980f399278" WHERE post_id = 62587

BACKTRACE

FILE: [ROOT]/includes/db/mysqli.php
LINE: 182
CALL: dbal->sql_error()

FILE: [ROOT]/posting.php
LINE: 1211
CALL: dbal_mysqli->sql_query()
```

If that's what you're getting too, it's caused by the dice mod as that's whats on line 1211 of posting.php

---

## Re: Known Issue: Apostrophes

### **jaybee3** (2012-05-08 09:19:43)

Unfortunately what I posted is the **whole error message** I get. I don't get the **full details**, I would have thought the logs would pick it up.
I posted a dice roll *THEN* a smily...not like within the tags.

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-08 09:39:18)

> **jaybee3 wrote:**
>
> Unfortunately what I posted is the **whole error message** I get. I don&#39;t get the **full details**, I would have thought the logs would pick it up.
> I posted a dice roll *THEN* a smily&#8230;not like within the tags.

Huh.. maybe because I'm an admin I got the full error.
Regardless... The mod author adjusted his fix so I'll be giving that a shot later today.

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-08 13:39:20)

testing '
[Invalid dice roll_id: 1d20]
<!-- s:r2: -->:<!-- s:r2: -->

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-08 14:16:52)

'a final test' <!-- s:r2: -->:<!-- s:r2: -->

---

## Re: Known Issue: Apostrophes

### **Alicia** (2012-05-08 14:17:04)

Issue resolved!



<span style="font-size: 0.5em;">***Last Modified**: 4.0.28 - *2025-06-02 21:37:34 EDT*</span>