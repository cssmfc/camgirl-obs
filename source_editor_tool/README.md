# Source Editor 
*Basic offline Source viewer and Editor*

![Cover](https://raw.githubusercontent.com/cssmfc/obs/master/source_editor_tool/cgc_cover_source_editor.jpg)


### Index

:bar_chart: Fast navigation

* [about](README.md#about)
* [content](README.md#content)
* [author note](README.md#author-note)
* [support and contact](README.md#contact)
* [social network](README.md#links)

## :inbox_tray: [Download Source](https://github.com/cssmfc/obs/releases/tag/v1.0.Editor)

### About
This is a simple to use compiled web page allowing you to view, modify and render the edited source code of a local web page or code segment.
It uses Javascript, HTML and CSS all packed in a single web page.

> From time to time I offer markup codes, templates and resources for webcam performers as free downloads but some of them have  difficulties in editing and customizing their template by altering the Source code.

Well, this offline Source Editor is helping you view, edit and save markup codes.

It works offline, no additional resources. All in one file - javascript, CSS, HTML and it works in your Browser. Nothing to install and secure.

Your browser must support HTML5 FileRender. If you see error message, please upgrade your browser or at least use a better one like Firefox or Chrome; 
(I didn't tested this with Safari)
 

**File format:** .html
**Source:** local
**Coded:** HTML, CSS, Javascript
**Resources:** no external resources


:wrench: Functions and Options:
- Copy/paste code segments in Source Editor in order to edit it
- Option to upload a local file directly into Source Editor
- Option to render and preview the edited markup code
- Option to save the edited markup code 
- Reset option (basically refresh page function) - will loose all edited markup
- Supported files .html, .php,.txt
- Supported markup codes and programming language - all supported by your browser
- Option to resize the Render window's width for testing responsiveness  

**:ok_hand: Pro:**
- no install necessary
- no external libraries or files
- runs offline with local files and folders


**:neutral_face: Con:**
- does not auto correct the markup
- this file must be placed in the same folder as the one which will be edited in order for the additional resources and full paths of your resources to render correctly (show images, additional/external style-sheet... so on)
- it does not use the language detection for rendering different markup types with different visual styles
- it does not render php with server-side dependencies (you can only view its source)
- it does not add document type headers (if missing)

### Install instructions
**How to Install and use this Source Editor?**
**Just download and save the file in your laptop/pc, no install necessary**

Editing source code of a full web page offline
- move this file inside the same folder as the file you want to edit

Editing source code of a full markup code (a Chaturbate bio design for example, because all HTML, CSS and images are in the same place)
- simply copy your code and paste it in the Source Editor's box
- save the code as .html file locally on your pc/laptop 



### Content

:open_file_folder: This github repository is holding the file you need to download on your laptop/pc


### Author Note

:memo: **Please read**
* I've developed this simple script in order to allow my collaborators to edit their Chaturbate bio design locally in their browser
* I can not be responsible for how this file is used. If no editing skills, you might brake a functional web page or code snippet.
* To test your code for smaller screen, there's a piece of javascript which makes the Render window narrow - button available 

```javascript
function my500() {
    var x = document.getElementById("m500");
	if (x.style.width === "100%") {
        x.style.width = "50%";
    } else {
        x.style.width = "100%";
    }
}
```

If you want to change the Source Editor's background color and color of the font... You'll need to edit it's css markup code. Look for this class

```css
.fcode{border:none;padding:5px;width:100%;height:400px;scroll:auto;
background:#212121;
color:#f1f1f1;
font-family:Courier, serif;border-radius:3px;-moz-border-radius:3px;-webkit-border-radius:3px;}
```
Enjoy


### Contact

:mailbox_with_no_mail: For questions, feedback, suggestions, feel free to contact the [support staff](https://camgirl.cloud/contact/) 


### Links 

:link: CGC is active on social networks and other platforms:

[Twitter](https://www.twitter.com/CSSMFC) | [Facebook Group](https://www.facebook.com/groups/xniteproductions/) | [YouTube](https://www.youtube.com/channel/UCbJQMNUNpK1Pt-uGyOq7iQw) | [Website](https://camgirl.cloud/) | [Reddit](https://www.reddit.com/r/CamgirlLiveEditor/) | :underage: [on Chaturbate](https://chaturbate.com/redglove/)
