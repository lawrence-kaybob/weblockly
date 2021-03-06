# Weblockly

### What is "Weblockly"?
"Weblockly" is a [Blockly](https://developers.google.com/blockly) Modification project, which helps noobs to make component of web site, using HTML, CSS and blocks, so that they can run and deploy their component with Weblockly.
We're planning to implement deployment feature, enalbing their project to be deployed and embeded in own web site.

### How does this project works?
Blockly is an open source project(under Apache License v2.0). By taking advantage of [Blockly](https://github.com/google/blockly) project, we were able to make Blockly App to Static Web Site Version.

### How can I use this project?
1. Make sure you have installed [git](https://git-scm.com/downloads), [node.js](https://nodejs.org), and [npm](https://www.npmjs.com/) 
2. Clone this project with git on desired directory
```
git clone git@github.com:lawrence-kaybob/weblockly.git
```
3. Move to cloned directory
```
cd weblockly
```
4. Install dependencies using npm
```
npm install
```
5. Start node.js server instance
```
npm start
```
6.  Open you browser at http://localhost:3000

### Demo
You can also try out our project at [here](http://weblockly.lkaybob.pe.kr)!

### Coming Features  
* sign in and save & load workspace 
* provides project examples 
* improved UX&UI 
* support various and powerful blocks 

### License
Weblockly is released under GNU General Public License v3.0. See [LINCESE](https://github.com/lawrence-kaybob/weblockly/blob/master/LICENSE) for more information.

### Dependencies
Weblockly uses following open source software. Each usage can be found in [LICENSE](https://github.com/lawrence-kaybob/weblockly/blob/master/LICENSE#L676)
* npm : https://www.npmjs.org
* Material Design Lite : https://getmdl.io/
* Blockly : https://developers.google.com/blockly/
* CodeMirror : https://codemirror.net
* JSZip : https://stuk.github.io/jszip/

### Probable Issue
Since Blockly depends on [closure-library](https://github.com/google/closure-library), you might get a warning like below, when you try out Weblockly.
![image](https://raw.githubusercontent.com/lawrence-kaybob/weblockly/master/public/images/closure-alert.png)

If it does, check out the solution [here](https://developers.google.com/blockly/guides/modify/web/closure)
### Other References
* SlideShare (Korean): https://goo.gl/8IDPVN
* YouTube Video : https://youtu.be/BydwQcDlhu4
