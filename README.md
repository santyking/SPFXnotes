# SPFXnotes
Notes of SPFX 
#installation
#versions required
Spfx 1.18.2
node js 18.19.1
yo 4.3.1
gulp 4.0.2

since node modules are not a part of Upload try running 'npm install' to load dependencies

we need to enable app catalogue wrt SharePoint site collection. for this,
install SharePoint online management shell if not installed.
Connect-SPOService
Add-SPOSiteCollectionAppCatalog -Site "enter site url"

to add multiple webparts under single solution, run yo @microsoft/sharepoint on the same folder once again. yoman automatically identifies that this is something additional on the existing solution and adds it.
