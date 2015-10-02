# AppVeyorCI-Test

To get the build working with a nuget package i had to add:

in settings -> build -> before script -semect CMD and added:

nuget restore DemoApp-CI\DemoApp-CI.sln

and also i made sur that no packages where uploaded to github.

http://i.imgur.com/pruxo6O.png
