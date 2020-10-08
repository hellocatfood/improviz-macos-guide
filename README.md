# improviz-macos-guide

Improviz is a live coding environment built by Guy John aka Rumblesan. It is available as a stand-alone desktop application and as a web app. It is similar in appearance and functionality to LiveCodeLab but the desktop version extends this functionality by giving the user the option to load their own custom textures, animated gifs, shaders, and 3D models.

![improviz_macos_001](images/improviz_macos_001.jpg)

As with a lot of live coding languages, one of the most difficult barriers to using them is setting up the environment and installing them, especially if you're used to just downloading a file and double-clicking it to install and run it.

In this short tutorial I'll show you how to launch Improviz using the terminal, which will be useful when using Improviz but will also put you in a better position for doing programming and using other live coding tools.


For this particular tutorial I’m using a Mac Pro computer, and will be using the default Safari Browser.

Launch your browser and go to https://improviz.rumblesan.com/ . This is the official website for Improviz and should be your first stop for finding out more about the software.

![improviz_macos_002](images/improviz_macos_002.jpg)

Under the Installation section click on where it says pre-built binaries. This will take you to the Github site where you can download a version of the software that is compatible for your operating system.

![improviz_macos_003](images/improviz_macos_003.jpg)

As we're using Mac download the one labelled improviz-osx-0.8.2.tar.gz . The archive file you download may have a different version number if there have been updates since this video was made, but that’s ok. This will start the download of the software. By default this will download it to your Downloads folder.

![improviz_macos_004](images/improviz_macos_004.jpg)

Open the Downloads folder from the dock. If you've set a different location for your downloads you should go there instead. In there you'll see the improviz-osx-0.8.2.tar.gz file (if the .gz isn't shown, don't worry though). This is an archive folder containing the software. To unpack it, double click on it, and OSX should create another folder called improviz-osx with the contents of the archive inside.

In that folder you'll see lots of different files, including one called improviz.

![improviz_macos_005](images/improviz_macos_005.jpg)

You may be thinking that to run Improviz you would double-click on the improviz file. While this is an option, for Improviz we need to open, or launch, the software from the terminal. This approach has multiple benefits, and for Improviz it will allow us to see an error message when we make mistakes.

To open the terminal, open a Finder window, and then go to your Applications folder.

![improviz_macos_006](images/improviz_macos_006.jpg)

From there, find the Utilities folder, open it and then double click on the Terminal app.

![improviz_macos_007](images/improviz_macos_007.jpg)

Using the terminal is like navigating your computer but without your mouse and only using text commands. A full explanation of using the terminal is out of the scope of this introduction video, but a few guides are linked in the description.

![improviz_macos_008](images/improviz_macos_008.jpg)

By default when you open the terminal you are located in your Home folder. If you type ls you can see a list of your files and folders. We need to navigate to the location where you Improviz folder is. The command cd allows you to change directory to one you specify. This is similar to double-clicking on a folder icon with your mouse.

in the terminal type cd Downloads. Now when you type ls you'll see a list of the files in that folder.

![improviz_macos_009](images/improviz_macos_009.jpg)

Again in the terminal type cd improviz-osx and press Enter.

Now that you're located in the right folder in the terminal type ./improviz to launch Improviz. Depending on the version of OSX you have, you may get Improviz immediately, you may get a warning about network connections first, or you may get a warning saying that “improviz” cannot be opened because the developer cannot be verified.
If it’s the latter, then click “cancel”, and then allow the app to run by following these steps.

![improviz_macos_010](images/improviz_macos_010.jpg)

Click the apple icon in the top left of your screen to open up your System Preferences, go to Security & Privacy, and then in there go to the General tab.

![improviz_macos_011](images/improviz_macos_011.jpg)

![improviz_macos_012](images/improviz_macos_012.jpg)

At the bottom there should be a message saying that “Improviz was blocked from use because it is not from an identified developer”. Click the Open Anyway button, and then in the terminal rerun the ./improviz command.

![improviz_macos_013](images/improviz_macos_013.jpg)

You may still get another warning about macOS not being able to verify the developer, but this time you should have the option to click Open.

![improviz_macos_014](images/improviz_macos_014.jpg)

If you get a white screen appearing in the top-left corner of your screen then you're ready to start learning to use Improviz!

If you don't you can report an issue to the developer by going to the address below.

You can also chat visit a forum for livecoding where a community of users may be able to help you.

You're now ready to start using Improviz! There are example files located in the Improviz folder you downloaded which you can learn from, or you can search on the internet to see if there's any upcoming Improviz workshops.
