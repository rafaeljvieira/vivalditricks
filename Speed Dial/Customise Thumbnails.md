**Basic Understanding and Info**

So, to begin with, the thumbs are stored inside the 'Top Sites' file inside your user profile, which is an SQL Database file. You can check where your profile is by opening the About page.

The image files may be any image type Vivaldi can handle, so you may even use an animated gif (yes it works, it's animated). The default size is 440x360px, this size will fit perfectly leaving no blank spaces. Default SD images are indexed colours, and I suggest for you to do so as this will make loading faster.

**How to Open the DB**

Now, you need to open the file with an SQL file editor/browser. I'll be using [DB Browser for SQLite](http://sqlitebrowser.org/) that's available for all OSes Vivaldi is compatible. Remember that Vivaldi has to be closed to edit the file.

When you open the file open the second tab (Browse Data), and in the dropdown labelled Table choose thumbnails.

**Finally Changing the Thumbs**

Now open your Bookmarks file in your user directory with a text editor and look for your SD folder, the file is a pretty easy to read JSON. Look for the SD entries you want custom thumbs and check their id numbers, if you look a few line below you'll see a Thumbnail entry whose value starts with *chrome://thumb/http://bookmark_thumbnail/* and ends with the id number. If that's not the value of Thumbnail, you better close everything and go back to the step to re-create the thumbs from Vivaldi.

Now back to your SQL Browser search for the entry with the URL starting with *http://bookmark_thumbnail/* and ending with the id you got in the Bookmarks file. Double click the thumbnail entry of that line, which probably says BLOB or NULL, and a new window will open. Click the Import button and choose your thumb, and then click OK.

Repeat for each SD entry you want to edit and once you changed all of them just save the Top Sites file and enjoy.

***Author:*** [An_dz](https://vivaldi.net/en-US/easysocial-dashboard/profile/15939)

***Source:*** https://vivaldi.net/en-US/forum/all/2777-adding-custom-thumbs-in-speed-dial
