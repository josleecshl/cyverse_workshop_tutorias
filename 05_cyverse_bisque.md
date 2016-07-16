# Introduction to BisQue Image Analysis

[BisQue](http://www.cyverse.org/bisque) Bio-Image Semantic Query User Environment allows you to store, visualize, organize and analyze images in the cloud. BisQue was developed for the exchange and exploration of biological images, but can support image data from other domains. 

## How to login to BisQue
Launch [BisQue](http://bisque.iplantcollaborative.org/client_service/). You must be sign into the account when prompted.

>**Tip:** You have to request access to BisQue through the CyVerse User Portal. To request access, login to [CyVerse User Portal] (https://user.cyverse.org/) and check to see if Bisque is listed under ‘My Services.’ If it is not, scroll down and click the “Request Access” button next to BisQue.

### Loading data using Cyberduck

You can upload resources from 40-100 GB via a graphical interface using Cyberduck.

1.	Connect to the data store using Cyberduck.
2.	Click on the 'bisque_data' folder' to open.
3.  Drag your image(s) from your computer into the folder.
4.	Under my recent stuff, select the Images tab to find your image(s).

### Loading data using iCommands

You can upload large resources (tens of GBs) or automatically upload images from your microscope or camera using iCommands.

1.	Connect to the data using iCommands:
```
iinit
```
Youll be prompted to enter your password.

2. Change the directory to your 'bisque_date' folder.
```
icd bisque_data
```

3.  Use iCommands 'iput' to transfer image to the 'bisque_data' folder.
```
iput filename.tiff
```

## Exercise 1 - Share image with another CyVerse user
By default, uploaded items are set to private visibility, which means only you can access or view the file. You can change the permission setting for some or all files in the list.

1. Get the username of another CyVerse user. i.e. jwilliams
2. Select your image. Above the image next to visibility, there is a 'Share icon' to click on.
(insert file share1)
3. A window will pop-up. Begin to type in the CyVerse username.
(insert file share2)
4. You'll be able to set permissions depending if the image is public or private. Private resources are only accessible by the owner and shared users. Published resources are visible to everybody but are only modifiable by owners and shared users.
(insert file share3)

## Exercise 2 - Add metadata (annotations) to images
You can add, delete, and IR import metadata tags (annotations) to datasets or selected files now or later.
[wiki link](https://pods.iplantcollaborative.org/wiki/display/BIS/Uploading+Files%2C+Images%2C+and+Directories+to+BisQue) 

1. To add metadata to a selected file in the dataset, click the file and then click Add.
(insert file add)
2. Double-click in the Name field, and either select a name from the drop-down list or enter a new metadata name.
(insert file add2)
3. Double-click in or tab to the Type field and enter the metadata type.
(insert file add3)
4. Click Update.
