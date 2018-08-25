# OBS overlay - Fixed Bar

![Cover](https://raw.githubusercontent.com/cssmfc/obs/master/obs_overlays/obs_overlay_bars/how%20to%20use/assets/cover_obs_overlay_bar.jpg)


### Index

:bar_chart: Fast navigation

* [about](README.md#about)
* [content](README.md#content)
* [author note](README.md#author-note)
* [support and contact](README.md#contact)
* [social network](README.md#links)



### About
This OBS overlay shows animated content (using CSS3 keyframes) to power up the sticky bar.
* Model's image - animated with CSS3 keyframes - must be a sqare image (i.e. 400x400, 550x550, 700x700)
* Model's name - editable plain text - editing is made via source markup code
* Scrooling text - `marquee` html tag is used - editable plain text
* Current date - powered by javascript 
* Premium Username - visible animation with delay. It uses plain text and crown icon
* Twitter Username - visible animation with delay. It uses plain text and twitter icon 
* Email Address - visible animation with delay. It uses plain text and Amazon icon 
- email visible for premiums who want to send Amazon Gift Cards. Because it is not rendered directly into browser, scrap bots can not grab the email address
 

**OBS overlay type:** browser
**Source:** local
**Coded:** HTML, CSS, Javascript
**Resources:** font used MicroFLF, images


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

In order to edit the content of the Bars.html you must edit the source markup of the web page. Notepad++ (Windows users) or TextWrangler (MAC users) will do the job.
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
