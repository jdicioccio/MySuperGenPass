# SuperGenPass as a Chrome Extension

This is exactly the same version used in http://supergenpass.com/mobile/

And it was adapted to be used as a chrome extension by https://github.com/benol/MySuperGenPass Thanks to <b>benol</b>!

However; there were some improvements for performance that makes it hard to investigate if there is any "funny code". And also, I didn't really like the idea to get automatic updates of the extension without my approval. 

No offense benol. Security is very important, right. So, I changed a little bit to make it more open to be audited. 

I got rid of unused resources and replaced minified zepto with the one I downloaded myself. And also, I compared the supergenpass algorithm with the actual source. Finally, I removed the hooks in manifest.json to make it not updatable. And voila! Yet another SuperGenPass based app.

## Installation

This extension is not intended to be in the chrome store due to auto update. So, you need to install it by yourself. To install, follow these steps:

* First, check by yourself if there is anything "scary" in the code! As far as I know, there is nothing that can track any password or transaction. But, I can be wrong! Check yourself. I take no responsibility. If you find anything, please let me know too. I am using it everyday. :)
* Clone the repository to the specified folder of your own.
* Go to Tools|Extension in Chrome
* Select Developer Mode
* Click on Load unpacked extension...
* And point the folder where you cloned the repository.
* Have fun!