# Web Archive Repository for MSTSBin mstsbin.uktrainsim.com

This repository contains the web archive version of the original MSTSBin website, which was previously hosted at [mstsbin.uktrainsim.com](http://mstsbin.uktrainsim.com), along with all it's downloadable files and resources as part of a preservation effort.

### Visit live at: [https://thenekobot.github.io](https://thenekobot.github.io/)!

## About this preservation project
With the announcement of UKTrainsim's closure back on the 31st of August, 2023, it was inevitable that the original MSTSBin website would eventually go down as well as it was also being hosted on the same server as UKTrainsim.

As such, being a data hoarder and preservationist myself, I've decided to capture the entire website and all of it's downloadable contents on the 27th of August, 2023, just a few days before the expected closure of UKTrainsim.com, using a tool called [Cyotek WebCopy](https://www.cyotek.com/cyotek-webcopy) which had allowed me to download the entire website and all of it's contents which made it possible to view the website offline.

And with the files in hand, I've decided to implement some of the necessary fixes and improvements to the website to make it more visually accessible and user friendly, and have it hosted on GitHub Pages as a web archive, so that it can be preserved and accessed by anyone who may need it in the future. 

Additionally, it also serves as a way for me to learn how to use GitHub Pages as part of my studies.

## Why host a web archive here when the Wayback Machine already exists?

To summarize, here are a few reasons why I've decided to host a web archive of the MSTSBin website, even though the original website is already archived on the Wayback Machine snapshots:

1. **Speed**: While trying to access the original website snapshot on the Wayback Machine, I've personally found it to be quite slow, and at times even unresponsive, especially when trying to download larger files such as the MSTSBin installer. As such, having another web archive of the same website hosted on GitHub Pages would allow for faster access to the website and it's downloadable files.

2. **Quality of life improvements**: While the Wayback Machine does capture snapshots of the original website **as it was**, this also means that any flaws and visual bugs that were originally present on the website were captured as well. With access to the original website files, this means that I was able to dive into the html files and apply some of the necessary fixes to make the website more visually accessible and user friendly.

3. **Redundancy**: Having multiple copies of the same website hosted on different platforms would ensure that the website would be preserved even if one of the platforms were to go down. And with the recent news of the internet archive in hot legal waters with book publishers, the future of the Wayback Machine remains uncertain and bleak.

4. **Continuous updates**: As this version of the web archive is not a static snapshot, I would be able to continuously update the website with support for new languages, fixes, and other improvements as needed, which would not be possible with the Wayback Machine snapshots.

5. **Giving back to the community**: As a long time user of MSTSBin and a member of the Train Simulator community (Albeit a lurker), having the ability to not only preserve and host the original MSTSBin website itself and all of it's contents, but also to improve upon it has given me much joy and satisfaction, and I hope that this web archive would be of use to the community as well.

6. **I just wanted to**: It's that simple.

## So what are the differences between this and the original website / snapshots?

Here are some of the side-by-side comparisons with the original snapshot on the left and this version on the right:

### 1. Fixed hard-coded frame height which limited the viewable area of the website on modern displays.
In the original website, the height of the frames were hard-coded to a fixed value of 500 pixels, presumably due to the website being designed for the displays at the time. This has bugged me for a long time as it meant that the viewable area was serverly limited on modern displays. This was fixed in the web archive version by replacing the hard-coded height value with `height: 100%` to allow the frames to take up the full height of the display, allowing for a better viewing experience on modern displays.<br> <br>
![Frame height fix](/git_docs/frameheightfix.png)

### 2. Replaced the broken guestbook section with a user-friendly message. 
For sometime now, the guestbook section of the original website had been broken and was not functioning properly. This was never fixed by the original website owner, and in it's place, had always displayed an error message of "File not found". In the web archive version, the broken guestbook section was replaced with a user-friendly message to inform users that the guestbook section was no longer available, and to direct them to use some of the other forums and communities for support instead.
<br><br> ![Guestbook fix](/git_docs/guestbookfix.png)


### 3. Updated the links section to include actual useful links, while retaining old ones

The links section of the original website contained a list of links to various websites and resources related to Train Simulator and MSTSBin. However, many of the links were outdated and no longer functioning, and some of the links were not very useful. As such, in this web archive version, the links section was updated to include active links to various websites and forum resources related to Train Simulator and MSTSBin, while retaining some of the old links for historical purposes.
<br><br> ![Links fix](/git_docs/linksfix.png)

### 4. Image preservation for some of the czech documentation pages.
The original website contained some documentation images in Czech version of the website which were not properly preserved in the Wayback Machine snapshots. In this web archive version, the Czech documentation pages were properly preserved and are now accessible to users who may need them.
<br><br> ![Czech docs fix](/git_docs/czechdocsfix.png)

## Future plans from here on out
As of now, the primary goal of this web archive which was to preserve the original MSTSBin website and all of it's contents has been achieved, and I plan to mostly leave the website as it is, with only minor updates and fixes as needed along the ways.

There are however, a few other things that I would like to implement in the future, such as bringing over the hidden czech documentation pages to be accessible from the english version of the website, and possibly adding support for more languages in the future. (Specifically to cater to the Indian Train Simulator community, as I've noticed that there are quite a few users from India who are deeply interested and passionate in MSTS).

However, as I am currently a student and have other commitments, I may not be able to work on this project as much as I would like to, but I will try my best to keep the website updated and maintained as needed during my free time.

If you have any suggestions, feedback, or if you've found any bugs or issues with the website, please feel free to open an issue on this repository, and I will try my best to address them as soon as possible.

On a side note I'm also currently looking for a way to host steam4me.net on GitHub Pages as well, as I've managed to archive that entire site too before it went down. However, due to the entire site (4GB in total including downloadable files) exceeding the 2GB limit of your typical GitHub repository, I'm currently looking into how feasible it would be to host the HTML files on GitHub Pages while having the downloadable files else where on a separate server, presumably a cloud storage provider with file download availability being the primary concern.
