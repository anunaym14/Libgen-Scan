# Libgen Scan
This is currently a proof-of-concept based off dm77/barcodescanner, providing a thin activity which sends scanned ISBN codes to a Libgen search. Point your phone at a book, the book magically appears on your phone, amazing.
See [HandleResult()](https://github.com/nfd9001/Libgen-Scan/blob/master/app/src/main/java/com/nfd/libgenscan/MainActivity.java#L86);

No affiliation with the fine Library Genesis projects or their families or neighbors or mirrors; but they're mighty neighborly folks indeed, and they could use your money or books or whatever. 
No warranties, what you do with this project is solely your business and I don't take responsibility for your actions, lorem ipsum, sit dolor emet, I'm on vacation and I have nothing better to do than write stupid .md files, I've written more lame jokes here than I've written actual code, give me all your money I'm a student who doesn't want to shell out thousands for CS textbooks I'm not even gonna use, help I'm trapped in a .md factory, etc. etc., and this project inherits the Apache 2.0 license.

# Download
[Debug-signed builds are available in Releases.](https://github.com/nfd9001/Libgen-Scan/releases) This app is not currently listed on any app store; though it may soon be found on F-Droid.

## Todo
* Integrate with services that might be able to resolve a UPC to an ISBN, because some books use UPCs instead, how rude!
* The current intent synergises well with Firefox, which can open links in batches; perhaps add a queue or history so that there may be better cooperation with other browsers
