# OBS overlay - Stats
*Custom overlay created for Battle of the Braves standalone section*

![Cover](https://raw.githubusercontent.com/cssmfc/obs/master/obs_overlays/obs_overlay_bars/how%20to%20use/assets/cover_obs_overlay_bar.jpg)


### Index

:bar_chart: Fast navigation

* [about](README.md#about)
* [content](README.md#content)
* [author note](README.md#author-note)
* [support and contact](README.md#contact)
* [social network](README.md#links)

## :inbox_tray: [Download Source and full documentation](https://github.com/cssmfc/obs/releases/tag/v1.0.Bar)

### About
This OBS overlay shows animated content (using CSS3 keyframes).
Please note that after the overlay has been enabled, it has a 1.4s before starting the CSS animation in order to display the full content
* Red Knights
  * revealed with a delay of 1.4s after the overlay has been activated
  * top banner image
  * animated flag in the left side
  * team header title using editable plain text (Metamorphous font)
  * 6 Premium Usernames displaied in cascade transition with 8s delay animation starting with the first one
    * each Premium Username has the team's icon in front
  * token value animated micro banner set as background image and editable token value using plain text
* Blue Lords
  * revealed with a delay of 3.4s after the overlay has been activated
  * top banner image
  * animated flag in the left side
  * team header title using editable plain text (Metamorphous font)
  * 6 Premium Usernames displaied in cascade transition with 8s delay animation starting with the first one
    * each Premium Username has the team's icon in front
  * token value animated micro banner set as background image and editable token value using plain text
 

**OBS overlay type:** browser
**Source:** local
**Coded:** HTML, CSS
**Resources:** MicroFLF font, Metamorphous font, static and animated images


:wrench: General install of OBS overlays downloaded form our platform:
1. Download and extract the content from zip file
2. Open OBS, click the + button/icon from Sources manager window
3. Select the Browser option from the available options panel
4. Select Local file checkbox , browse button and select the html file provided
5. Set up the width and height of the overlay (it depends on what the overlay is showing)
6. Select the Refresh checkbox
7. Tweak the position of the installed overlay by dragging the red lines or corners
8. To trigger overlay visibility use the eye icon to show or hide

### Install instructions
**How to use this overlay and how to edit it?**

In order to edit the content of the ShowStatus.html you must edit the source markup of the web page. Notepad++ (Windows users), TextWrangler (MAC users) will do the job or you can use the compiled [Source Editor](https://github.com/cssmfc/obs/tree/master/source_editor_tool) already provided inside the downloaded folder
To use this overlay on your stream follow the install steps suggested below

1. Open **OBS** [download OBS if necessary](https://obsproject.com/)
2. From **Sources** zone click the :heavy_plus_sign: sign/icon

![New Source](https://raw.githubusercontent.com/cssmfc/obs/master/obs_overlays/obs_overlay_bars/how%20to%20use/assets/obs-add-new-source.jpg)

3. Next step is to select **Browser** from available options 
![Select Browser](https://raw.githubusercontent.com/cssmfc/obs/master/obs_overlays/obs_overlay_bars/how%20to%20use/assets/obs-select-source.jpg)

4. **Create New** will show up, give it a name, easy to spot 
![Rename](https://raw.githubusercontent.com/cssmfc/obs/master/obs_overlays/obs_overlay_bars/how%20to%20use/assets/obs-rename-browser-source.jpg)

5. **Local File** - Browse. **Browse** for the file Bars.html. Make sure you select **Local File** option 
![Select Local File](https://github.com/cssmfc/obs/blob/master/obs_overlays/obs_overlay_bars/how%20to%20use/assets/obs-local-file.jpg)
 Settings visible in screenshot
 

7. Drag the red corners to fit your main screen source for better position
![Position](https://raw.githubusercontent.com/cssmfc/obs/master/obs_overlays/obs_overlay_bars/how%20to%20use/assets/obs-position-overlay.jpg)

8. Optional, you can play with Transition and Fade Transition options when triggering this overlay, it is up to you.



### Content

:open_file_folder: This github repository is holding markup codes and detailed documentation used for this OBS overlay along with graphics and install instructions


### Author Note

:memo: **Please read**
* the overlay is not interactive, it is not triggered by tips.
* all editing process is made via source code
* all resources run locally from your device (desktop/laptop)
* the overlay is triggered manually by the model
* overlay developed for Chaturbate webcam performers.
* javascript is used to display the current date

```javascript
<script>
var d = new Date();
document.getElementById("date").innerHTML = d.toDateString();
</script>
```

The editable markup HTML code used for Premium Username, Twitter and Amazon sections

```html
<div class="cl-12 icons no">

    <div id="toptipper" class="cl-4 no toptipper tright">
       <p>Premium Username</p> <!--- add premium username --->
    </div>
    
    
    <div id="twitter" class="cl-4 twitter no">
       <p>@TwitterUsername</p> <!--- add twitter username --->
    </div>
    
    <div id="amazon" class="cl-4 amazon no">
       <p>my-email@address.com</p> <!--- add your email address --->
    </div>
    
    
    
</div>
```
The layout of this overlay is using responsive values defined by `cl-` class
HTML, CSS and Javascript are commented


**Install instructions and full documentation along with all necessary resources provided inside the downloaded file**


### Contact

:mailbox_with_no_mail: For questions, feedback, suggestions, feel free to contact the [support staff](https://camgirl.cloud/contact/) 


### Links 

:link: CGC is active on social networks and other platforms:

[Twitter](https://www.twitter.com/CSSMFC) | [Facebook Group](https://www.facebook.com/groups/xniteproductions/) | [YouTube](https://www.youtube.com/channel/UCbJQMNUNpK1Pt-uGyOq7iQw) | [Website](https://camgirl.cloud/) | [Reddit](https://www.reddit.com/r/CamgirlLiveEditor/) | :underage: [on Chaturbate](https://chaturbate.com/redglove/)
