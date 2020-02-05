# Startpage Firefox SearchProvider
Set Startpage.com as your default Firefox search provider without installing their extension 

## Steps
1) Go to [https://www.startpage.com/search/settings?lang=en](https://www.startpage.com/search/settings?lang=en) and set your search preferences
2) Copy the `prfe` config string at the bottom of the page
![prfe](https://github.com/jankais3r/Startpage-Firefox-SearchProvider/blob/master/prfe.png)
3) Replace the `prfe` string within `startpage.xml` with the one you copied in the previous step
4) Upload the contents of `startpage.xml` to [pastebin.com](https://pastebin.com/) (paste expiration 10 minutes)
5) Open the developer console and paste the following javascript code, replacing the pastebin link with the one you just created
`window.external.AddSearchProvider('https://pastebin.com/raw/bVGUaPSm');`

![prfe](https://github.com/jankais3r/Startpage-Firefox-SearchProvider/blob/master/add.png)


Congratulations, you can now search privately without the need to install any extensions.
