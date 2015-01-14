#### What this is

<img src="http://scripting.com/2015/01/14/peterPanAndWendy.png" width="125" height="193" border="0" style="float: right; padding-left: 25px; padding-bottom: 10px; padding-top: 10px; padding-right: 15px;" alt="A picture named peterPanAndWendy.png">A new version of the software used in the <a href="http://listicle.io/cluetrain/">Cluetrain listicle</a>, generalized so that it is fully specified in a JSON file. It can be used for lots of listicles, including ones that you write. 

<a href="http://scripting.com/2015/01/13/listicleOListicle.html">Dave Winer</a>

#### How it works

There's a <a href="https://github.com/scripting/listicle/blob/master/list.json">JSON file</a> that configures the app. It must be in the same folder as the index.html file and it must be named list.json.

When the page loads, it reads the JSON file, and shows you the first item in the list. If you click the right arrow, you go to the next item, click the left arrow you go to the previous one. The Home icon takes you to the first item. 

If you click on the label you get a permalink for the item. If you click the twitter icon at the top of the page you get a dialog that sets up a tweet with the content of the item you're looking at. 

Click on the Info icon to see the About box.

#### Updates

v0.52 -- 1/14/15 by DW -- Made a change to how prefs are stored in localStorage, so you can have more than one listicle on a domain without having their prefs collide.

v0.51 -- 1/13/15 by DW -- you can now include Emojis in listicle items using the <a href="http://www.emoji-cheat-sheet.com/">Emoji cheat sheet</a> codes. <a href="http://listicle.io/demo/?clue=10">Example</a>.

#### Demo

Here's the <a href="http://listicle.io/demo/">demo listicle</a>. 

