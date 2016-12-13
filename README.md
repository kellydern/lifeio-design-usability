

![alt text](https://github.com/kellydern/Life-features/blob/master/assets/logo.png)


# Life.io Usability Testing Documentation

The repository houses the design files for the Life.io usability tests. We run weekly usability tests to review our assumptions. These tests inform our product development process and help us iterate on designs.

## Current usability design files:
- [x] Cards - Containers
- [x] Points
- [x] Primary - Secondary Actions
- [x] Reports
- [x] Workouts

##Set-Up
To manage design files, first install the <a href="https://github.com/mathieudutour/git-sketch-plugin">Sketch plugin</a> and follow the instructions to set up.

###Tips for managing files/artboards
- Give each artboard a meaningful title
- Create a new branch when you start working on a new feature. From the Plugin, go to Plugins > Git > New branch.
- Save the file
- When you're ready to commit, export the artboards by going to Plugins > Git > Generate files for pretty diffs
- Push your changes to the remote. (Plugins > Git > Push)
- Create a pull request the master branch.

###Tips for naming convention
- Use client name + feature name + date for Sketch file names. For example, Lifeio_RewardsTracking_092616
- Artboard names should be organized chronologically (1.1, 1.2, 1.3 etc.)

###Large file storage
- If the Sketch or other design files are too large to store, follow the <a href="https://git-lfs.github.com/">Git Large File Storage (LFS)</a> instructions to get started.
+ Download and install `git lfs install`
+ You can verify that your files are being tracked by running `git lfs ls-files`
+ Select the file types you'd like Git LFS to manage. We manage Sketch, PSDs and design assets such as images, icons and illustrations. `git lfs track "*.sketch"` or `git lfs track "*.psd"`
+ If you'd like to track a specific file, you can specify a file name to manage: `git lfs track "assets/filename.sketch"`
+ Commit and push 
`git add file.psd`
`git commit -m "Add design file"`
`git push origin master`




