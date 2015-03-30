# Erik's Sublime Configuration

![Screenshot](http://i.imgur.com/hhBihmD.png)

This is entire contents of my [Sublime Text 3](http://www.sublimetext.com) User directory, containing my Sublime Text 3 settings as well as my user settings for the different packages I have installed.

This is an accumulation of probably 2-3 years of configuring Sublime Text just how I like it. The result is, in my opinion, the most beautiful and productive editor that I can possibly imagine.

A list of packages that I use (all installed through Package Control) is available in the `Package Control.sublime-settings` file.

## How to Use
To replicate the configuration I have here, first [install the Package Control plugin](https://packagecontrol.io/installation) and close Sublime Text.

Then copy the contents of this repository into your Sublime Text User directory:

<pre>
git clone https://github.com/ErikSwan/sublime-config.git &amp;&amp; \
cp sublime-config/* <strong>{path to user directory}</strong> &amp;&amp; rm -rf sublime-config
</pre>

The path to your User directory is different depending on what operating system you are using:

* OS X: `~/Library/Application Support/Sublime Text 3/Packages/User`
* Windows: `%APPDATA%\Sublime Text 3\Packages\User` (usually `C:\Users\{user}\AppData\Roaming\Sublime Text 3\Packages\User`)
* Linux: `~/.Sublime Text 3/Packages/User`

Modify the list of packages that you want by editing `Package Control.sublime-settings`. Then re-open Sublime Text. You should see a flurry of activity as Package Control installs the missing packages. 

To enable the theme I'm using, go to *Sublime Text → Preferences → Color Scheme → User → Monokai Soda*. 

You're all set!

## More Resources
You won't be getting the maximum out of Sublime Text until you truly learn and master its bag of tricks. Jeffrey Way has an excellent video series, [Perfect Workflow in Sublime Text 2](https://code.tutsplus.com/courses/perfect-workflow-in-sublime-text-2), that I highly recommend to get up to speed with Sublime Text quickly.
