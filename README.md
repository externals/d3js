# d3/ d3js
Packages repo of d3js (https://d3js.org)


This is a repo to hold different versions of d3 you may need
and also to make them available for your project as default

# d3 ready to run files
Downloaded from github or d3js.org set to the "packages" branch so you can use
the version you prefer as default.

Checkout the version you need or create a new branch including the version you want

if you need it system wide? then merge it to the "packages" branch

example:
# packages branch
./v1.2.3/d3.js
./v1.2.3/README

If a new version exists and you need it globaly:
don't drop other versions! Add your version to it using a new branch, then
merge to "packages":

Eg: You need verion 2.0.1 system wide:
checkout the master branch and create a new branch: "v2-0-1" (branches needs - NOT dots!)
create a folder: mkdir v2.0.1/
Download the d3.js to v2.0.1/
commit & push the new version branch

Then checkout the "packages" branch and merge your version into it. result:
# branchs available:
./v1.2.3/d3.js
./v1.2.3/README.txt
./v2.0.1/d3.js
./v2.0.1/README.txt
./README.md (this README file)
