# OpenRPG/Traipse Tips

### **Alicia** (2012-02-11 12:47:26)

**<span style="font-size: 1.50em;">Traipse Install</span>**
A few very important points, there is an issue with python uninstall that may help you install traipse.
This worked for at least one user. they installed traipse and had problems until they:

1. erased everything
2. ran CCleaner
3. Than ran this [3rd party cleaner](http://www.revouninstaller.com/revo_uninstaller_free_download.html "http://www.revouninstaller.com/revo_uninstaller_free_download.html")
4. Then reinstall python, wxpython and [ornery orc](http://www.knowledgearcana.com/download-traipse "http://www.knowledgearcana.com/download-traipse")

You can get the latest Ornery Orc at: <!-- m -->[http://www.knowledgearcana.com/download-traipse](http://www.knowledgearcana.com/download-traipse "http://www.knowledgearcana.com/download-traipse")<!-- m -->
The idea is that old python files are maybe not getting cleaned with a regular uninstall. The 3rd party cleaner is the main thing getting rid of the conflicting files and the install goes off without a hitch. It also important to note that both ccleaner and the 3rd party cleaner are both free. Hope this helps everyone.
**<span style="font-size: 1.50em;">OpenRPG Domain Issue</span>**
Also the domain <!-- m -->[http://www.openrpg.com](http://www.openrpg.com "http://www.openrpg.com")<!-- m --> is down though someone bought it. This makes the old OpenRPG boards harder to get to so here is the address: <!-- m -->[http://www.rpgobjects.com/forum/viewforum.php?f=5](http://www.rpgobjects.com/forum/viewforum.php?f=5 "http://www.rpgobjects.com/forum/viewforum.php?f=5")<!-- m -->

---

### **Alicia** (2012-03-13 10:26:25)

If you have been experiencing issues on your Vista and Windows 7 machines, don't worry, you're not alone.
This solution solved many of my problems which featured an issue with the map timer (even when maps weren't in use) and caused frequent lock ups and issues with map usage.
For some reason Python doesn't like Vista and Windows 7 when running OpenRPG, but there's good news. It works well on Windows XP set ups.
Don't worry you won't have to dual boot or find an extra copy of the old OS.
If you haven't already you will need to have the 32 bit version of Python and WxPython installed. Don't worry about uninstalling it, it will overwrite or uninstall it for you correctly through the set up files. As I'm using Traipse I used the installs from here:
[Traipse Downloads](http://www.knowledgearcana.com/download-traipse "http://www.knowledgearcana.com/download-traipse")
Here's the direct links to save time:
Python: [Download (2.6.5) Win32](http://www.knowledgearcana.com/files/traipse-openrpg/resources/win-32/python-2.6.5.zip "http://www.knowledgearcana.com/files/traipse-openrpg/resources/win-32/python-2.6.5.zip")
wx.Python: [Download (2.10.1) Win32](http://www.knowledgearcana.com/files/traipse-openrpg/resources/win-32/wxPython2.8-win32-unicode-2.8.10.1-py26.exe "http://www.knowledgearcana.com/files/traipse-openrpg/resources/win-32/wxPython2.8-win32-unicode-2.8.10.1-py26.exe")
Once everything has been installed:
**Note** you may need to be on an administrative account to perfom.

1. Go into the python folder (by default it's in C:/ drive)
2. Go into the properties for python and pythonw
3. In the compatibility tab, click "change settings for all users"
4. Change the drop down to work in compatibility mod for Windows XP Service Pack 3 ( if you're using the 64b version of Python you won't see this.. Go back and install the 32b)

* I set mine to always run as administrator

5. Click "OK"

That should do it!
[Here&#39;s a guide on how Compatibility mode works.](http://www.howtogeek.com/howto/windows-vista/using-windows-vista-compatibility-mode/ "http://www.howtogeek.com/howto/windows-vista/using-windows-vista-compatibility-mode/")



<span style="font-size: 0.5em;">***Last Modified**: 4.0.28 - *2025-06-02 21:36:11 EDT*</span>