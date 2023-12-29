# TIMEOUT

## Noticement

1. Playlist **MUST** contain teaser list and it's content, otherwise,  teaser function can not works properly.
1. The codec of teaser clip  **MUST** using `Apple ProRes 4444` and contain alpha channel, otherwise teaser function can not be apply or unpredictable result.

   ![Codec](Timeout-teaserCodec.jpg)
   
 `TEASER` list must contain 2 clips, the player use the first clip as home team teaser and the second clip is guest team teaser content.
   
   ![Teaser](Timeout-TeaserPlaylist.jpg)
   
   ![TeaserHome](Timeout-homeTeaserDemo.jpg)
   ![TeaserHome2](Timeout-TeaserHome.jpg)
   
   ![TeaserGuest](Timeout-guestTeaserDemo.jpg)
   ![TeaserGuest2](Timeout-TeaserGuest.jpg)

1. Playlist **MUST** contain timeout list and it's content, 
   otherwise only teaser content overlay in normal playlist content.
   
   ![Teaser](Timeout-TeaserPlaylist.jpg)




   **Sample of timeout list** 

![Timeout](Timeout-Playlist.jpg)



## Preview
![Overview](timeout-Preview.png)


## Demostration
![Step1](Timeout-Preview2.jpg)

**Home team request timeout**
press home team button. 
![Step2](Timeout-PressHome.jpg)


home team teaser content is overlay in clip until countdown run to zero.
![Step3](Timeout-TeaserHome.jpg)

**Guest team request timeout**

Guest Home team button 
![Step2](Timeout-PressGuest.jpg)


Guest teaser content is overlay on normal clip until countdown run to zero.

![Step3](Timeout-TeaserGuest.jpg)

**Switch timeout clip**

Simply tap other thumbnail, when countdown run to zero, timeout will stop, you can not change it anymore.


**Cancel timeout by manually**

Just long press `TIMEOUT` button until blinking stop then teaser content and timeout content will disappear.

![Step3](Timeout-cancel.jpg)
