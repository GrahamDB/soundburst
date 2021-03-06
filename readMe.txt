# Install Instructions

### Windows

1. First download and install R if you don't already have it installed. It is always better to download the latest version of R, however if you are having any issues with the SoundBurst App, please download the version of R with which it was developed with. The application was created and tested using R 3.3.1 which can be downloaded from [here](https://cran.r-project.org/bin/windows/base/old/3.3.1/R-3.3.1-win.exe). If you prefer to use the latest version, you can obtain the install from [here](https://cran.r-project.org/bin/). _Please note that you might need to run the installer as administrator on Windows._

2. The next step is to download and install RStudio if you don't already have it installed. You can download the latest version of RStudio from [here](https://www.rstudio.com/products/rstudio/download/) or download the version of RStudio with which SoundBurst App was developed with from [here](https://download1.rstudio.org/RStudio-0.99.903.exe)

3. Since you will be running the SoundBurst App on Windows, it is necessary to also install RTools. Please download the latest version from [here](https://cran.r-project.org/bin/windows/Rtools/) or [version 3.4](https://cran.r-project.org/bin/windows/Rtools/Rtools34.exe) which was used to during the app's development. **Make sure that you select "Edit System Path" during the installation of Rtools so that it can be located and used by RStudio. See image below**
![Rtools Edit System Path](http://blueraster-users.s3.amazonaws.com/cphang/edit-path-rtools)

4. Once you have everything installed, you will need to download our source code from our [github page](https://github.com/blueraster/emammal-soundBurst). If you are a developer, please clone the master branch. Otherwise you can just click [here](https://github.com/blueraster/emammal-soundBurst/archive/master.zip) to download the latest version of the Soundburst app.

5. Once the code is downloaded, unzip the file.

6. **NOTE:** if you are running Windows 10, you may encounter the following unexpected error (see image below). If you experience this error, please select "Do this for all current items" and click Skip. ![windows10-SoundBurst-App](http://blueraster-users.s3.amazonaws.com/cphang/windows10-SoundBurst)

7. Once the file is unzipped, double click on soundBurst-site.Rproj. This will open RStudio. Click on installPackagesWin.r from the bottom right pane. In the top left pane, highlight all text and click the button "Run." This installs the necessary packages for the app to run.
> Note that you might need to "Install additional tools". Just click "yes" if asked.

8. Next, open server.R file from the bottom right pane. Click "Run App" in the top left pane to launch the application.

> If after you clicked on Run App you see an error similar to "Error: There is no package called: ..", please try bullet point #6 and #7 once more and it should fix the problem. If the problem persists, please
> create a github issue and we will help you out.


### Mac

1. First download and install R if you don't already have it installed. It is always better to download the latest version of R, however if you are having any issues with the SoundBurst App, please download the version of R with which it was developed with. The application was created and tested using R 3.3.1 which can be downloaded from [here](https://cran.r-project.org/bin/macosx/old/R-3.3.1.pkg). If you prefer to use the latest version, you can obtain the install from [here](https://cran.r-project.org/bin/).

2. The next step is to download and install RStudio if you don't already have it installed. You can download the latest version of RStudio from [here](https://www.rstudio.com/products/rstudio/download) or download the version of RStudio with which SoundBurst App was developed with from [here](https://download1.rstudio.org/RStudio-0.99.903.dmg)

3. You will need to also download libxml. The easiest way to do that is to use [Homebrew](http://brew.sh/). If you do not have it installed on your Mac, please follow the instruction on their website. Once you have homebrew installed, just run the following commands: "$ brew install libxml2 libxslt" and "$ brew link libxml2 libxslt"

4. Once you have everything installed, you will need to download the SoundBurst App from our [github page](https://github.com/blueraster/emammal-soundBurst/archive/master.zip). If you are a developer, please clone the master branch from [here](https://github.com/blueraster/emammal-soundBurst).

5. Once the code is downloaded, unzip the file.

6. Once the file is unzipped, double click on soundBurst-site.Rproj. This will open RStudio. Click on installPackagesMac-Linux.r from the bottom right pane. In the top left pane, highlight all text and click the button "Run." This installs the necessary packages for the app to run.
> Note if you receive a question about updating packages, simply select "No".

7. Next, open server.R file from the bottom right pane. Click "Run App" in the top left pane to launch the application.

> If after you clicked on Run App you see an error similar to "Error: There is no package called: ..", please try bullet point #6 and #7 once more and it should fix the problem. If the problem persists, please
> create a github issue and we will help you out.

### Linux (Desktop)

1. First download and install R if you don't already have it installed. It is always better to download the latest version of R, however if you are having any issues with the SoundBurst App, please download the version of R with which it was developed with. Please go [here](https://cran.r-project.org/bin/linux/), choose your Linux distribution and download the latest version of R **OR** download the version of R with which the SoundBurst App was developed **R 3.3.1**.


2. The next step is to download and install RStudio if you don't already have it installed. Please go [here](https://www.rstudio.com/products/rstudio/download/) and choose your Linux distribution to download the latest version of RStudio. If you want to download a previous version of RStudio (0.99.903 is not packaged for any Linux distribution), please go [here](https://download1.rstudio.org/)

3. Once you have everything installed, you will need to download the SoundBurst App from our [github page](https://github.com/blueraster/emammal-soundBurst/archive/master.zip). If you are a developer, please clone the master branch from [here](https://github.com/blueraster/emammal-soundBurst).

4. Once the code is downloaded, unzip the file.

5. Once the file is unzipped, double click on soundBurst-site.Rproj. This will open RStudio. Click on installPackagesMac-Linux.r from the bottom right pane. In the top left pane, click the button "Run." This installs the necessary packages for the app to run. Note that you might need to "Install additional tools". Just click "yes" if asked.

6. Next, open server.R file from the bottom right pane. Click "Run App" in the top left pane to launch the application.

> If after you clicked on Run App you see an error similar to "Error: There is no package called: ..", please try bullet point #5 and #6 once more and it should fix the problem. If the problem persists, please
> create a github issue and we will help you out.wichga -Agc -m "Readme update"gp origin maer
