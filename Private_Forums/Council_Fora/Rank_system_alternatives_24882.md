# Rank system alternatives

### **Alicia** (2010-11-11 11:20:39)

**Proposal Summary:** Alternatives for the Rank system
**Proposal Declaration:** Following the board wide discussion on the topic I, with the help of Simply and other Staff, have been looking into alternatives on how to treat the Rank system.
Here's a couple of the more favorable concepts.

1. Theme based ranks - Users would be able to pick from various rank themes, which would be viewable no matter which style a user was currently viewing with. This has the advantage of each user being able to pick which rank title is seen, but might possible be more work in the wrong to make sure we have varied themes that are unique and interesting in their equality. Maybe have a D&D/Pathfinder theme, our current Star Wars theme, M&M, etc.
2. Make ranks style dependant - Rank images would change depending on which style a user was viewing. This has the advantage of making the image themes uniform as each style would have their own rank images. The current rank images would be for Star Wars based themes for example: Jedi Knight and another Star Wars theme I have plans to release in the future.

**Potential Benefits/Consequences:** Either would be more work, but I believe could be adequate compromises. The option to still remove all but two or even remove completely is still open.
**Reference:** [Multi Race Rank Themes](http://www.phpbb.com/customise/db/mod/mulitrace_rank_themes "http://www.phpbb.com/customise/db/mod/mulitrace_rank_themes")
'Demo' Board: <!-- m -->[http://forums.hiveworldterra.co.uk/](http://forums.hiveworldterra.co.uk/ "http://forums.hiveworldterra.co.uk/")<!-- m -->
Demo Username: ModTester
Demo Password: modtester
I don't have a reference for the 2nd option as it would be just a couple code fixes to change the image path to become style dependent rather than just one set of rank images.
I'm still open to other suggestions, but my goal is to make the main images more system generic rather than our current Star Wars themed ranks.

---

### **simplyscribed** (2010-11-11 14:52:01)

I've been browsing MODs just now, trying to find one for something entirely tangential to this (I was rather hoping I'd be able to find one that would let you see whether or not a post has been read, and ideally by whom - this would help me and other GMs know when players have actually ready posts and are just not replying)... couldn't find one though. :
BUT, I did find a MOD that I think is of some relevance to this topic: Top Poster of the Month. You see, with this, even if posting ranks were removed, there would still be an incentive/"reward" for high levels of posting, which might help alleviate some of the complaints.
<!-- m -->[http://startrekguide.com/mods/index.php &#8230; ail&amp;id=352](http://startrekguide.com/mods/index.php?i=main&mode=detail&id=352 "http://startrekguide.com/mods/index.php?i=main&mode=detail&id=352")<!-- m -->

---

### **Vash** (2010-11-11 20:19:48)

Well that would have ups and downs. Yes there would be a reward but then you would get the people who would just post random things to get that rank. I will stand by my vote to just get rid of them. However people would miss their ranks so to keep the masses happy I would say going with just the two ranks would be best.

---

### **Magical2099** (2010-11-12 03:08:21)

Quick question: if the rankings are hurting the site, then won't adding multiple rank systems and tying them into the theme system put even more strain on the site? I like this idea alot, but if the site is struggling and sacrifices have to be made then cut the ranks.

---

### **DarthAnthrax** (2010-11-12 06:29:57)

I don´t really like this. I think if we should have a rank system, it should be the same for everyone, whether that be SW themed or something more neutral.
I´m not really sure about what criteria are possible to use for determining rank, and how much work is involved (I only know **very** basic web programming), but would it be possible to make the ranks something like "achievements"?
As an example, perhaps you gain the rank "Jedi Scholar" if you have more than 3000 posts in the archives threads, and the one with the most posts in the archives gain the title "Jedi Archivist".
I have no idea what anyone else thinks of this, if it is possible to do, how hard it is to do, or anything really. It was just an idea that floated into my mind.

---

### **Magical2099** (2010-11-12 07:28:29)

gotta admit this is idea is kinda interesting and could be very easy to do. all the processing could be server side and only show/load on the profile page. view the users profile and see what trophies/achievements they have. Would be fairly simple in that it could be set up to run the query against the database once every 24 hours and update the profiles at that time with post totals, achievements, and awards. by having them only be viewable on the profile page it would cut major slack on the sites usages.

---

### **Alicia** (2010-11-12 08:33:58)

I would have no clue how to do this. LOL
Edit: To add to this after thinking it over, As far as I'm aware, there's no way for phpbb3 to determine how many posts an individual has made in a particular forum/topic. The counts which are already stored in a database are for total counts for the thread, forum and even personal counts. Adding individual counts for each thread and forum per individual the way I'm thinking would possibly add so much database overhead we could be slowing the boards down considerably.

---

### **Alicia** (2010-11-12 10:43:17)

> **Magical2099 wrote:**
>
> Quick question: if the rankings are hurting the site, then won&#39;t adding multiple rank systems and tying them into the theme system put even more strain on the site? I like this idea alot, but if the site is struggling and sacrifices have to be made then cut the ranks.

Right now we're using a hosting provider which uses CPU throttling. This means that our problems before with using up our CPU usage isn't as much as a concern.
<!-- m -->[http://helpdesk.bluehost.com/index.php/ &#8230; cle/000564](http://helpdesk.bluehost.com/index.php/kb/article/000564 "http://helpdesk.bluehost.com/index.php/kb/article/000564")<!-- m -->
Right now on any given high performance day we throttle for about 200 seconds, well under their max of 500.
As of right now, it is not as much an issue as it was when we were using the service provider Rowen was using.
The ranking system isn't hurting the site resource wise. As most browsers these days cache images (storing the image on your computer), it's only that initial loading that causes a strain on the website when it comes to them. Honestly though the strain is most likely negligible in comparison to the loading of text from posts and the chat room (chat room is the most likely culprit to hogging our resources).

---

### **Yogi** (2010-11-12 10:44:51)

Personally I liked the ranks when they used to change for me. So I can understand where some are coming from but since the ranks don't affect me anymore now I don't think about it.
As far as people making posts to ramp up their count, I have never really seen that here. If it was happening it would be easy to spot due to our rather small community of posters.
The idea of theme based ranks based on the board style sounds good to me. This way those that want the Star Wars feel can still have that. If they want a supers feel they can have that and so on....
With the two titles that DA mentioned "Jedi Scholar and Archivist" Add them to the ranks that are already available. with two new ones it would divi up the total post requirements down for the titles. (would require a little reworking but not too much I think)

---

### **simplyscribed** (2010-11-12 11:01:35)

> **DarthAnthrax wrote:**
>
> I don´t really like this. I think if we should have a rank system, it should be the same for everyone, whether that be SW themed or something more neutral.
> I´m not really sure about what criteria are possible to use for determining rank, and how much work is involved (I only know **very** basic web programming), but would it be possible to make the ranks something like &quot;achievements&quot;?
> As an example, perhaps you gain the rank &quot;Jedi Scholar&quot; if you have more than 3000 posts in the archives threads, and the one with the most posts in the archives gain the title &quot;Jedi Archivist&quot;.
> I have no idea what anyone else thinks of this, if it is possible to do, how hard it is to do, or anything really. It was just an idea that floated into my mind.

To be honest, this is how I saw the idea from the beginning, except without the right coding the Mod team would have to do it manually (and to make our lives easier, members could probably apply once they knew they qualified). Title/achievements could have any prerequisites we wanted to set, meaning by using them we could encourage members to start actively participating in ways they currently avoid.
Another side-effect of using this way is that we might be able to award title/achievements for playing in games. There might be a few generic ones you could earn from any game for being an excellent player, and perhaps GMs could apply to have a unique title set up for meeting some qualification unique to their own game. Not only would these titles be badges of honour but they would also serve as a record of a player's past participation.
Alicia, do you know if there are mods to a) allow more than one title to be displayed (then a player could pick their top 3, say, complete with logo and description) and/or b) a way to turn the title images into a link to a page where all of their achievements are displayed?

---

### **Alicia** (2010-11-12 11:04:31)

> **simplyscribed wrote:**
>
> Alicia, do you know if there are mods to a) allow more than one title to be displayed (then a player could pick their top 3, say, complete with logo and description) and/or b) a way to turn the title images into a link to a page where all of their achievements are displayed?

This is the first one to come to mind: <!-- m -->[http://www.phpbb.com/community/viewtopi &#8230; 0&amp;t=967635](http://www.phpbb.com/community/viewtopic.php?f=70&t=967635 "http://www.phpbb.com/community/viewtopic.php?f=70&t=967635")<!-- m -->
I saw it in my hunt for alternatives, but as far as I can see its set through the ACP and not UCP.
I'll keep looking.
This one is probably being better supported: <!-- m -->[http://www.startrekguide.com/community/ &#8230; =84&amp;t=2072](http://www.startrekguide.com/community/viewtopic.php?f=84&t=2072 "http://www.startrekguide.com/community/viewtopic.php?f=84&t=2072")<!-- m -->
So far neither of which support usergroups or allow users to adjust it through the UCP, but I have already made the suggestion on the latter's thread so I will see what sort of response is given.

---

### **simplyscribed** (2010-11-12 12:43:12)

> **Alicia wrote:**
>
> > **&quot;simplyscribed&quot; wrote:**
> >
> > Alicia, do you know if there are mods to a) allow more than one title to be displayed (then a player could pick their top 3, say, complete with logo and description) and/or b) a way to turn the title images into a link to a page where all of their achievements are displayed?

This is the first one to come to mind: <!-- m -->[http://www.phpbb.com/community/viewtopi &#8230; 0&amp;t=967635](http://www.phpbb.com/community/viewtopic.php?f=70&t=967635 "http://www.phpbb.com/community/viewtopic.php?f=70&t=967635")<!-- m -->
I saw it in my hunt for alternatives, but as far as I can see its set through the ACP and not UCP.
I'll keep looking.
This one is probably being better supported: <!-- m -->[http://www.startrekguide.com/community/ &#8230; =84&amp;t=2072](http://www.startrekguide.com/community/viewtopic.php?f=84&t=2072 "http://www.startrekguide.com/community/viewtopic.php?f=84&t=2072")<!-- m -->
So far neither of which support usergroups or allow users to adjust it through the UCP, but I have already made the suggestion on the latter's thread so I will see what sort of response is given.
Well hopefully you get response to that! But even if one of us had to change it for them, it would be an easy matter of them sending a request PM and us spending a minute out of our lives to do it. I spend enough time hanging around the community with nothing to do anyway this doesn't seem like a huge burden. The fact that this is an option is cool. What about my second suggestion, where the rank images would be clickable links to an achievement page. Possible?
Not ideal, but I suppose a workaround would be for users who want their achievements publically on record to make a list in their blog and link to it in their siggy.

---

### **Sketchpad** (2010-11-12 13:02:09)

How about instead of ranks use custom titles? As far as forum count and such, is there a way to have Reputation added to the boards? They use it over at the Hero Games Forum and it's pretty nice ... someone likes a post, they give reputation ... They also use the custom title, which works well (and mods gain special titles)

---

### **Alicia** (2010-11-12 13:04:43)

> **Sketchpad wrote:**
>
> How about instead of ranks use custom titles? As far as forum count and such, is there a way to have Reputation added to the boards? They use it over at the Hero Games Forum and it&#39;s pretty nice &#8230; someone likes a post, they give reputation &#8230; They also use the custom title, which works well (and mods gain special titles)

Like Karma? <!-- m -->[http://www.phpbb.com/community/viewtopic.php?t=1861325](http://www.phpbb.com/community/viewtopic.php?t=1861325 "http://www.phpbb.com/community/viewtopic.php?t=1861325")<!-- m -->
And what do you mean by custom titles?

---

### **Sketchpad** (2010-11-12 13:12:30)

> **Alicia wrote:**
>
> > **&quot;Sketchpad&quot; wrote:**
> >
> > How about instead of ranks use custom titles? As far as forum count and such, is there a way to have Reputation added to the boards? They use it over at the Hero Games Forum and it&amp;#39;s pretty nice &amp;#8230; someone likes a post, they give reputation &amp;#8230; They also use the custom title, which works well (and mods gain special titles)

Like Karma? <!-- m -->[http://www.phpbb.com/community/viewtopic.php?t=1861325](http://www.phpbb.com/community/viewtopic.php?t=1861325 "http://www.phpbb.com/community/viewtopic.php?t=1861325")<!-- m -->
And what do you mean by custom titles?
I'm presuming it's about the same ...
Check out the users on here ... I use the same SN ... <!-- m -->[http://www.herogames.com/forums/forum.php](http://www.herogames.com/forums/forum.php "http://www.herogames.com/forums/forum.php")<!-- m -->

---

### **Alicia** (2010-11-12 13:19:52)

> **Sketchpad wrote:**
>
> > **&quot;Alicia&quot; wrote:**
> >
> > > **&amp;quot;Sketchpad&amp;quot; wrote:**
> > >
> > > How about instead of ranks use custom titles? As far as forum count and such, is there a way to have Reputation added to the boards? They use it over at the Hero Games Forum and it&amp;amp;#39;s pretty nice &amp;amp;#8230; someone likes a post, they give reputation &amp;amp;#8230; They also use the custom title, which works well (and mods gain special titles)

Like Karma? <!-- m -->[http://www.phpbb.com/community/viewtopic.php?t=1861325](http://www.phpbb.com/community/viewtopic.php?t=1861325 "http://www.phpbb.com/community/viewtopic.php?t=1861325")<!-- m -->
And what do you mean by custom titles?
I'm presuming it's about the same ...
Check out the users on here ... I use the same SN ... <!-- m -->[http://www.herogames.com/forums/forum.php](http://www.herogames.com/forums/forum.php "http://www.herogames.com/forums/forum.php")<!-- m -->
Looking at this <!-- m -->[http://www.vbulletin.com/docs/html/reputation](http://www.vbulletin.com/docs/html/reputation "http://www.vbulletin.com/docs/html/reputation")<!-- m --> it looks to be the same concept as what the mod is trying to do. Just have to keep in mind this seems to be a built in feature of vBulletin while the pbpbb3 equivalent is the post count system.
EDIT: As I just told Sketch in chat, the Karma mod doesn't look to have been updated in some time and at this time doesn't appear to be a stable release. If this is an option others would like considered, I will look into other releases.
EDIT 2: Found this. Seems to be more inline to what vBulletin does <!-- m -->[http://www.phpbb.com/community/viewtopi &#8230; 0&amp;t=780735](http://www.phpbb.com/community/viewtopic.php?f=70&t=780735 "http://www.phpbb.com/community/viewtopic.php?f=70&t=780735")<!-- m -->

---

### **DarthAnthrax** (2010-11-12 13:23:44)

If we´re going to implement some kind of karma/reputation system, I feel like I have to insist on that we find something where you can only give positive karma, or only give karma to specific posts themselves, and not to members. We had a system that went both ways a long time ago, and I seem to recall a person getting his karma run totally in the bottom just because some argument in an ooc section.
I just don´t feel it makes for very good mood on the board.

---

### **Alicia** (2010-11-12 13:47:11)

Both mods do just that (its on a post basis and not member, the member gets a cumulative grade as it were based on the feedback from the posts) and provide a comment box for members to comment on the post.
Make sure to take a look at the features on the mods themselves.

---

### **Alicia** (2010-11-13 08:21:55)

Here's what's on the table for alternatives at this time:
These would probably be a one or the other choice:

**Multi-themed ranks:** This would allow for users to pick their rank theme which would be visible no matter the style skin in use
**Style based ranks:** The user's style will determine with rank images are shown
**Reputation/Karma:** There are a couple mods which mimic vBulletin's reputation very closely. This basically allows members to give positive or negative points to another member by rating a post. Both mods also allow for the rater to provide a comment to the post, which could provide feedback if the reputation was negative. Check this out for how vBulletin work. <!– m –>[http://www.vbulletin.com/docs/html/reputation](http://www.vbulletin.com/docs/html/reputation "http://www.vbulletin.com/docs/html/reputation")<!– m –>
The following could be done regardless of what ranking alternative we decide with the possible exception of Reputation:

**Multi-Rank:** Staff can go into the ACP and choose up to three ranks to be visible. (so far though this is not determined by usergroups). This would actually be a nice addition should we do Award Titles.

To finally answer your question about links Simply, it would probably be possible to have the rank name be turned into a link, but not the image itself as far as I've been able to discern. If I discover likewise I'll let you know.
**Award Title / Achievements:** At present I haven't found a released mod to aid in this, it would have to be done manually by the Staff/volunteers, but would allow for special ranks to be awarded to members based on a set standard of achievements. This is something we can do regardless of whatever ranking alternative we decide to go with.
Thoughts so far?

---

### **master_Tru** (2010-11-13 09:43:33)

Multi-themed ranks sounds good the more options a member has the more they will customize. The more a member can customize the more the feel that the site is there thus keeping their interest longer.
Style based ranks interesting, this would be a good idea for those few who are less into star wars then the other games on the site. That is if there is such a member. I am sure there must be a few.
Reputation/Karma we had tried this in the past. It did not really take off and was never added back in one of the sites many moves. Though there is nothing stopping us from trying it again.
Multi-Rank if I understand this one correctly we would manually choice the rank for the members. A little more work but worth it if we the members prefer the ranks available to them. We could even have a site vote o the name of one or more of the ranks thus encouraging site participation.

---

### **simplyscribed** (2010-11-13 11:58:34)

> **Alicia wrote:**
>
> **Multi-themed ranks:** This would allow for users to pick their rank theme which would be visible no matter the style skin in use
> **Style based ranks:** The user&#39;s style will determine with rank images are shown

If I understand these descriptions, this works like so:
With **multi-themed ranks**, a user can pick their Force Adept rank title and their decision affects everyone. On my general xabbblue style, I will see their Star Wars rank title. So would someone using a fantasy-themed style, and so on.
With **style-based ranks**, we all see exactly what *we* want to see. The user in the above example, along with anyone else using a Star Wars-theme style, will see their Force Adept rank title. But I'll see the equivalent title for the generic boards ("Exceptional Poster", or whatever), and the fantasy-style guy would see a fantasy title (let's say "Warlord").
My personal preference out of these two is style-based ranks. Everyone will see exactly what rank a member is, but the actual title they see will be consistent with their own preferred style, making for a more cohesive user experience for them. With the other option, another user's decision is forced upon me. I get that they're proud of their rank and want to show it off, but really nobody other than me and the site administration should be allowed to decide what I see when I log onto Galactic Campaigns.
> **Alicia wrote:**
>
> **Reputation/Karma:** There are a couple mods which mimic vBulletin&#39;s reputation very closely. This basically allows members to give positive or negative points to another member by rating a post. Both mods also allow for the rater to provide a comment to the post, which could provide feedback if the reputation was negative. Check this out for how vBulletin work. &lt;!&ndash; m &ndash;&gt;[http://www.vbulletin.com/docs/html/reputation](http://www.vbulletin.com/docs/html/reputation "http://www.vbulletin.com/docs/html/reputation")&lt;!&ndash; m &ndash;&gt;

I like this idea in theory, but I can see a case where it would become exactly what we don't want it to be. We originally talked about getting rid of post ranks so the amount of posts a member generates is less important than *what they're posting*, but if any and every post you make can receive reputation, then it would be easy for reputation to become a "post rank by any other name".
> **Alicia wrote:**
>
> The following could be done regardless of what ranking alternative we decide with the possible exception of Reputation:
>
> **Multi-Rank:** Staff can go into the ACP and choose up to three ranks to be visible. (so far though this is not determined by usergroups). This would actually be a nice addition should we do Award Titles.
>
> To finally answer your question about links Simply, it would probably be possible to have the rank name be turned into a link, but not the image itself as far as I&#39;ve been able to discern. If I discover likewise I&#39;ll let you know.
> **Award Title / Achievements:** At present I haven&#39;t found a released mod to aid in this, it would have to be done manually by the Staff/volunteers, but would allow for special ranks to be awarded to members based on a set standard of achievements. This is something we can do regardless of whatever ranking alternative we decide to go with.

As you already know, I'm in favour of both these ideas in combination to create an Achievements system. If the choice had to be this OR reputation then I would definitely pick this, especially given my noted concern for the reputation system's potential for abuse.
Linking from the text would be fine as well Alicia, just so long as there is some method where another user can easily access the achievements page and see exactly what a member has earned. <!-- s:) -->![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)<!-- s:) -->

---

### **Alicia** (2010-11-13 12:08:52)

Your assessments of my descriptions is practically dead on, Ross.
> **simplyscribed wrote:**
>
> Linking from the text would be fine as well Alicia, just so long as there is some method where another user can easily access the achievements page and see exactly what a member has earned.

This could probably be done using the FAQ system. Just make a new FAQ page and then link to the specific achievement. I have a mod already in place which allows for easy editing via the acp.
<span style="font-size: 0.80em;">***[ Post made via Mobile Device ]***</span>

---

### **simplyscribed** (2010-11-13 16:04:37)

I was messing about in Illustrator earlier and came up with a couple of achievement designs, sort of as proof of concept. Below are examples of how they might look and the sort of thing they might be awarded for:
"1 Year Anniversary": GM or play in a game that reaches its first anniversary.
[attachment=0]<!-- ia0 -->1yr.png<!-- ia0 -->[/attachment]
"Crowning Achievement": As a GM, successfully bring a campaign that has lasted at least a year to its conclusion.
[attachment=2]<!-- ia2 -->crwn.png<!-- ia2 -->[/attachment]
"Cash'n'Carry": Become a GC Supporter.
[attachment=3]<!-- ia3 -->spprt.png<!-- ia3 -->[/attachment]
"Wakka Wakka": Invite 5 new members to the community who do more than just lurk.
[attachment=1]<!-- ia1 -->wakka.png<!-- ia1 -->[/attachment]

---

### **DarthAnthrax** (2010-11-13 16:16:29)

Just a note on time-based achievements. I´ve been thinking about that, but I don´t think it would be a very good thing, since many of us had our joining dates completely messed up during all the site moves we did.

---

### **simplyscribed** (2010-11-13 16:27:10)

> **DarthAnthrax wrote:**
>
> Just a note on time-based achievements. I´ve been thinking about that, but I don´t think it would be a very good thing, since many of us had our joining dates completely messed up during all the site moves we did.

Doesn't matter, as long as we have no achievements for being a member a certain amount of time.

---

### **DarthAnthrax** (2010-11-13 18:43:15)

> **simplyscribed wrote:**
>
> > **&quot;DarthAnthrax&quot; wrote:**
> >
> > Just a note on time-based achievements. I´ve been thinking about that, but I don´t think it would be a very good thing, since many of us had our joining dates completely messed up during all the site moves we did.

Doesn't matter, as long as we have no achievements for being a member a certain amount of time.
Yeah, that´s what I thought you meant with that top picture, that you had been a member for a year. Did you add the text for that one recently, or did I just miss it the first time?

---

### **simplyscribed** (2010-11-13 18:46:54)

> **DarthAnthrax wrote:**
>
> > **&quot;simplyscribed&quot; wrote:**
> >
> > > **&amp;quot;DarthAnthrax&amp;quot; wrote:**
> > >
> > > Just a note on time-based achievements. I´ve been thinking about that, but I don´t think it would be a very good thing, since many of us had our joining dates completely messed up during all the site moves we did.

Doesn't matter, as long as we have no achievements for being a member a certain amount of time.
Yeah, that´s what I thought you meant with that top picture, that you had been a member for a year. Did you add the text for that one recently, or did I just miss it the first time?
Heh, I'm afraid you missed it. That was always there. <!-- s:) -->![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)<!-- s:) -->

---

### **Alicia** (2010-11-13 19:58:54)

> **simplyscribed wrote:**
>
> > **&quot;DarthAnthrax&quot; wrote:**
> >
> > > **&amp;quot;simplyscribed&amp;quot; wrote:**
> > >
> > > > **&amp;amp;quot;DarthAnthrax&amp;amp;quot; wrote:**
> > > >
> > > > Just a note on time-based achievements. I´ve been thinking about that, but I don´t think it would be a very good thing, since many of us had our joining dates completely messed up during all the site moves we did.

Doesn't matter, as long as we have no achievements for being a member a certain amount of time.
Yeah, that´s what I thought you meant with that top picture, that you had been a member for a year. Did you add the text for that one recently, or did I just miss it the first time?
Heh, I'm afraid you missed it. That was always there. <!-- s:) -->![:)](https://i.ibb.co/8LPNcWCM/icon-e-smile.gif)<!-- s:) -->
When I first saw it I thought member anniversary too.... LMAO

---

### **simplyscribed** (2010-11-13 20:01:41)

Hehe, just a few more. This is fun. I volunteer to be in charge of achievement design if we go ahead with it! <!-- s:D -->![:D](https://i.ibb.co/MDcFvFDD/icon-e-biggrin.gif)<!-- s:D -->
"Life? Don't Talk To Me About Life": Five of your characters must die.
[attachment=3]<!-- ia3 -->rise.png<!-- ia3 -->[/attachment]
"The Great Innovator": Solve a problem with an idea *no one* was expecting.
[attachment=2]<!-- ia2 -->idea.png<!-- ia2 -->[/attachment]
"Many Masks": Have 3 or more active characters at one time.
[attachment=1]<!-- ia1 -->masks.png<!-- ia1 -->[/attachment]
"Coffee Mug of Victory": Win the Game of the Year award*.
[attachment=0]<!-- ia0 -->bstgm.png<!-- ia0 -->[/attachment]
*An example of how an achievement might be earned as an award.

---

### **Alicia** (2010-11-13 20:24:10)

Heh, want to make the images for the default board? If we keep with the 20 level rank system we have currently have, well we're going to need 20 ranks. <!-- s;) -->![;)](https://i.ibb.co/GfkGswQC/icon-e-wink.gif)<!-- s;) -->

---

### **simplyscribed** (2010-11-13 20:41:08)

> **Alicia wrote:**
>
> Heh, want to make the images for the default board? If we keep with the 20 level rank system we have currently have, well we&#39;re going to need 20 ranks. &lt;!&ndash; s;) &ndash;&gt;![;)](https://i.ibb.co/GfkGswQC/icon-e-wink.gif)&lt;!&ndash; s;) &ndash;&gt;

Some ideas...
0. Recruit/Lurker
1. Newbie
2. Green
3. Encouraging
4. Promising
5. Member
6. Talented
7. Skilled
8. Experienced
9. Pro
10. Veteran
11. -
12. -
13. -
14. -
15. Amazing
16. -
17. -
18. -
19. -
20. Legend

---

### **Alicia** (2010-11-13 20:57:04)

Maybe 10 levels with an additional for our Lurker rank:
**Level | post count**
**Lurker** | 0
**Level 1** | 1
**Level 2** | 50
**Level 3** | 200
**Level 4** | 500
**Level 5** | 1000
**Level 6** | 2000
**Level 7** | 3000
**Level 8** | 4000
**Level 9** | 6000
**Level 10** | 8000
I'm still recommending keeping the level wording as the images themselves are going to be different if we go with the style based images. It probably won't matter from what I've seen with the Multi-Rank mod.
Edit: WE have the following Special Ranks
Supporter
Game Master
Moderator
Global Moderator
Administrator

---

### **simplyscribed** (2010-11-13 21:17:47)

> **Alicia wrote:**
>
> Maybe 10 levels with an additional for our Lurker rank:.

Well in that case, I think I can manage to come up with 10... also with a bit more flavour.
**Level | generic title**
**Lurker** | Recruit
**Level 1** | Newbie
**Level 2** | Apprentice
**Level 3** | Trainee
**Level 4** | Graduate
**Level 5** | Talent
**Level 6** | Pro
**Level 7** | Veteran
**Level 8** | Master
**Level 9** | Hero
**Level 10** | Legend

---

### **simplyscribed** (2010-11-13 22:12:25)

Okay, just two more... (edit: *ahem* three more *ahem*) Figured if I made one for Supporters I needed to make them for Mods and Council Members. Couldn't resist.
"Mad Mod": Become a member of the Moderation team.
[attachment=1]<!-- ia1 -->mod.png<!-- ia1 -->[/attachment]
"Ring of Power": Become a member of the Galactic Campaigns council, and take part in at least one discussion affecting the site.
[attachment=2]<!-- ia2 -->ring.png<!-- ia2 -->[/attachment]
"Red's Award": In recognition of liberated droids who have thrown off the shackles of organic oppression! Red's Award is granted to players who entertain us with particularly memorable droid or robotic characters (any setting).
[attachment=0]<!-- ia0 -->red.png<!-- ia0 -->[/attachment]

---

### **Alicia** (2010-11-13 23:05:21)

> **simplyscribed wrote:**
>
> > **&quot;Alicia&quot; wrote:**
> >
> > Maybe 10 levels with an additional for our Lurker rank:.

Well in that case, I think I can manage to come up with 10... also with a bit more flavour.
**Level | generic title**
**Lurker** | Recruit
**Level 1** | Newbie
**Level 2** | Apprentice
**Level 3** | Trainee
**Level 4** | Graduate
**Level 5** | Talent
**Level 6** | Pro
**Level 7** | Veteran
**Level 8** | Master
**Level 9** | Hero
**Level 10** | Legend
I choose the longest one for this, what do you think?
[attachment=1]<!-- ia1 -->level-02.png<!-- ia1 -->[/attachment]
[attachment=0]<!-- ia0 -->level-02 v2.png<!-- ia0 -->[/attachment]

---

### **Alicia** (2010-11-14 09:42:15)

Oh, We can't forget Admin, Glob Mod, Mod, Game Master, and Supporter. Though I suppose we could just be boring and use the actual names for those or use the achievement images you've made Simply.
Remember too Simply, that if we're doing multi ranks, the images are going to have to be smaller (at least height wise). 200x50 I would think at most, but we can certainly play with the heights.

---

### **simplyscribed** (2010-11-14 10:16:57)

> **Alicia wrote:**
>
> I choose the longest one for this, what do you think?
> [attachment=1]&lt;!&ndash; ia1 &ndash;&gt;level-02.png&lt;!&ndash; ia1 &ndash;&gt;[/attachment]
> [attachment=0]&lt;!&ndash; ia0 &ndash;&gt;level-02 v2.png&lt;!&ndash; ia0 &ndash;&gt;[/attachment]

Not a bad job of it.
> **Alicia wrote:**
>
> Oh, We can&#39;t forget Admin, Glob Mod, Mod, Game Master, and Supporter. Though I suppose we could just be boring and use the actual names for those or use the achievement images you&#39;ve made Simply.
> Remember too Simply, that if we&#39;re doing multi ranks, the images are going to have to be smaller (at least height wise). 200x50 I would think at most, but we can certainly play with the heights.

Yeah, whether we use achievements or ranks *and* achievements, earning a new status would definitely be supported by the achievement system. So that's one way of keeping the actual post rank scheme simpler.
As for the image size, all of these are actually 50x50 in Adobe Illustrator, as I intended for them to be the perfect size for a member to be able to set their favourite of those earned as their profile pic. I have no idea why they're displaying as 200x200.

---

### **Alicia** (2010-11-16 10:24:15)

I've been playing around on a test forum and I can confidently say I know how to make ranks user style based.
For now, do you want to do the style based ranks rather than implementing reputation (which I haven't tested yet)?
What do you all think of the new ranks Simply and I have proposed?

---

### **Alicia** (2010-11-18 18:21:23)

**Level | Star Wars title**
**Lurker** | Non Heroic
**Level 1** | Fringer
**Level 2** | Scoundrel
**Level 3** | Noble
**Level 4** | Jedi
**Level 5** | Ace Pilot
**Level 6** | Officer
**Level 7** | Jedi Knight
**Level 8** | Force Disciple
**Level 9** | Crime Lord
**Level 10** | Jedi Master

---

### **simplyscribed** (2010-11-18 18:48:49)

> **Alicia wrote:**
>
> **Level | Star Wars title**
> **Lurker** | Non Heroic
> **Level 1** | Fringer
> **Level 2** | Scoundrel
> **Level 3** | Noble
> **Level 4** | Jedi
> **Level 5** | Ace Pilot
> **Level 6** | Officer
> **Level 7** | Jedi Knight
> **Level 8** | Force Disciple
> **Level 9** | Crime Lord
> **Level 10** | Jedi Master

Personally I would suggest replacing Non Heroic with Fringer, it's more evocative and implies lurking on the edge. Better to not have Fringer as an actual level too, really - it was always the odd one out, not being the name of a class.
I would probaby move every class from Jedi down up to the preceding level and slot in Gunslinger at the gap, myself.

---

### **Alicia** (2010-11-18 19:53:33)

Style based rank images has been integrated into the boards.



<span style="font-size: 0.5em;">***Last Modified**: 4.0.28 - *2025-06-02 21:39:13 EDT*</span>