# Medical Augmented Reality <img src="/augmented-reality.png" width="60" vertical-align="bottom">
> This project as been developped as part of the Medical augmented reality (IN2293) class at TUM (Technische Universität München). The goal of the project was to introduce an xray image within a given set of images of a surgeon's hand. All the images had been taken with a Microsoft kinect, thus the depth of each image was known. Overlay and blending were used to include the xray between the surgeon's hand and the fake patient body represented by a box. The results and the steps are presented below.

### Mean Depth Calculation From Multiple Images
>#### Input Images Examples:
><img src="/Repo_Images/video102.png" width="150" vertical-align="bottom">
><img src="/Repo_Images/video103.png" width="150" vertical-align="bottom">

>#### Calculated Scaled Mean Depth:
><img src="/Repo_Images/mean_depth.PNG" width="150" vertical-align="bottom">

### Foreground Object Segmentation (surgeon's hands)
>#### Input Images Examples:
><img src="/Repo_Images/video252.png" width="150" vertical-align="bottom">
><img src="/Repo_Images/video253.png" width="150" vertical-align="bottom">
><img src="/Repo_Images/video254.png" width="150" vertical-align="bottom">

>#### Segmented Outputs Examples:
><img src="/Repo_Images/mask150.png" width="150" vertical-align="bottom">
><img src="/Repo_Images/mask151.png" width="151" vertical-align="bottom">
><img src="/Repo_Images/mask152.png" width="152" vertical-align="bottom">

### XRay Overlay Creation
>#### XRay Image Input:
><img src="/Repo_Images/Xray.png" width="150" vertical-align="bottom">

>#### Video Images Input Examples:
><img src="/Repo_Images/video211.png" width="150" vertical-align="bottom">
><img src="/Repo_Images/video217.png" width="150" vertical-align="bottom">

>#### Video Images Output With Overlay Examples:
><img src="/Repo_Images/overlay109.png" width="150" vertical-align="bottom">
><img src="/Repo_Images/overlay115.png" width="150" vertical-align="bottom">

#### How to contribute ?
- [X] Create a branch by feature and/or bug fix
- [X] Get the code
- [X] Commit and push
- [X] Create a pull request

#### Branch naming

##### Feature branch
> feature/ [Short feature description] [Issue number]

##### Bug branch
> fix/ [Short fix description] [Issue number]

#### Commits syntax:

##### Adding code:
> \+ Added [Short Description] [Issue Number]

##### Deleting code:
> \- Deleted [Short Description] [Issue Number]

##### Modifying code:
> \* Changed [Short Description] [Issue Number]


Icons made by <a href="http://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="http://www.flaticon.com" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
