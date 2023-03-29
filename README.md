# GithubDownloadGuide
This is a resource for the [HailPack](https://github.com/BodenMcHale/HailPack/blob/trunk/README.md) installation guide.

## On-site download
 1. Go to the Github repository that contains the file you want to download.
 2. Navigate to the folder that contains the file.
 3. Click on the file you want to download.
 4. On the next screen, click the "_Download_" button.
 5. The file will be downloaded to your local computer.

## Command-line download
Alternatively, you can use the Git command-line tool to download a file from a Github repository.
 1. Install Git on your computer if you haven't already.

 > **Tip:** [Click here to learn how to install Git]([https://github.com/BodenMcHale/DownloadFileInstructions/blob/trunk/README.md](https://github.com/git-guides/install-git)).
 
 2. Open a command prompt or terminal window.
 
 3. Navigate to the directory where you want to download the file.
 
 4. Run the following command: ```git clone <repository_url>```

> **Note:** Replace <_repository_url_> with the URL of the Github repository you want to clone.
 
 5. Navigate to the directory containing the file you want to download.
 
 6. Copy the file to your local directory by running the following command: ```git checkout <branch_name> -- <file_path>```
 
 > **Note:** Replace <_branch_name_> with the name of the branch containing the file you want to download and <_file_path_> with the path to the file relative to the repository root.
