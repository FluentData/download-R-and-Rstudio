
Workstation Preparation Instructions 
Introduction to R and RStudio for Air Quality Data Science
We are reaching out to request your assistance in preparing computers for an upcoming online class on R and RStudio. This class will require participants to have both R and RStudio installed on their computers, along with access to CRAN repositories and GitHub for downloading necessary libraries. Additionally, users will need appropriate permissions to save and install these libraries in their user directories.
1. Install R
R is a free software environment for statistical computing and graphics. Please follow these steps to install R:
Go to the Comprehensive R Archive Network (CRAN) website (https://cran.r-project.org/).
Select a CRAN mirror that is geographically close to you.
Download the latest version of R for Windows, macOS, or Linux, depending on the operating system used.
Follow the installation instructions for the respective operating system.
2. Install RStudio
RStudio is an integrated development environment (IDE) for R. To install RStudio:
Visit the RStudio download page (https://www.rstudio.com/products/rstudio/download/).
Select and download the appropriate installer for RStudio Desktop (Free version) for Windows, macOS, or Linux.
Execute the installer and follow the on-screen instructions to complete the installation.
3. Configuring Access to CRAN and GitHub
It's essential that the computer can connect to CRAN repositories and GitHub.com for downloading required libraries. Please ensure that any firewall or internet security settings allow connections to:
CRAN repositories: Ensure that access to https://cran.r-project.org/ and any selected CRAN mirrors is not blocked.
GitHub: Ensure that access to https://github.com/ is allowed, as some R packages may need to be installed directly from GitHub repositories.
4. Setting Permissions for Library Installation
Users will need to have the necessary permissions to install and save R libraries in their user directories. Please adjust the permissions to ensure that:
Users have write access to their R library path. You can find the default library path by running .libPaths() in an R session.
If the default library path is not writable, consider setting a user-specific library path or adjust the permissions accordingly.
5. Testing the Installation and Configuration
To verify that the setup is correct, please perform the following steps:
Open RStudio.
Install a test package from CRAN by running install.packages("devtools") in the R console.
Install a test package from GitHub by running devtools::install_github("hadley/ggplot2"). (Note: This requires the devtools package, which was installed in the previous step.)
6. Additional Configuration (Optional)
Consider installing commonly used R packages to save time during the class. A basic set of packages includes tidyverse, shiny, rmarkdown, and devtools. These can be installed from CRAN using the install.packages() function.
Support
If you encounter any issues during the installation or configuration process, please consult the official documentation for R and RStudio, or contact Eric Bailey (ebailey@fluentdatallc.com) for further assistance.
Thank you for your cooperation and support in preparing for the Introduction to R and RStudio for Air Quality Data Science. Your efforts will ensure a smooth and productive learning experience for all participants.


