### SuperGenPass as a Chrome Extension

This is exactly the same version used in http://supergenpass.com/mobile/
And it was adapted to be used as a chrome extension by https://github.com/benol/MySuperGenPass Thanks to benol!
However; there were some improvements for performance that makes it hard to investigate if there is any "funny code". And also, I didn't really like the idea to get automatic updates of the extension without my approval. So, I removed the hooks in manifest.json as well. 

No offense benol. Security is very important, right. So, I changed a little bit to make it more secure. 

I got rid of unused resources and replaced minified zepto with the one I downloaded myself. And also, I compared the supergenpass algorithm with the actual source. Finally, I updated the manifest.json to make it not updatable. And voila! Yet another SuperGenPass based app.

## Installation

As I said, this extension is not intended to be in the chrome store. So, you need to install by yourself. To install, follow these steps:

* First, check by yourself if there is anything "scary" in the code! As far as I know, there is nothing that can track any password or transaction. But, I can be wrong! Check yourself. I take no responsibility.
* Clone the repository to the specified folder of your own.
	git clone https://github.com/osaatcioglu/MySuperGenPass.git
* Go to Tools|Extension in Chrome
* Select Developer Mode
* Click on Load unpacked extension...
* And point the folder where you cloned the repository.
* Have fun!