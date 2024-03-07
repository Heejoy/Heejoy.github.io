# Hosting a Resume on GitHub Pages with Jekyll

## Purpose

Learn how to craft a resume template using Markdown and style it with Jekyll. This guide provides step-by-step instructions for hosting your resume on GitHub Pages using Jekyll and composing your resume in Markdown with Visual Studio Code.

## Prerequisites

- GitHub Account
- Visual Studio Code installed
- Your resume formatted in Markdown

## Instructions

After you've finished the setup steps listed in the prerequisites section, you are now ready to start making your resume with Markdown. Let's get started on making a resume using the easy to follow Markdown.

## Create Markdown Resume

### 1. **Open your installed Visual Studio Code**
* Select `File` from the top left of the Visual Studio Code  

* In the drop-down menu, select `New File` to create a new file

* Click on `File` again, then `Save As`

* A dialog box will ask where to save it and what to name it

* Make sure to end the file name with `.md` to show it's a Markdown file

* For example, name it `<Your Name>Resume.md`

### 2. **Write your resume in Markdown** 
* With your new Markdown file open, you can now begin typing your resume based on your own resume in the file you created

* Markdown allows you to format your document with headings, bullet points, links, and more, using simple symbols

* For help writing in Markdown, refer to [Markdown Tutorial](https://www.markdowntutorial.com/) by [gjtorikian](https://github.com/gjtorikian)

* You can preview your Markdown in Visual Studio Code

* To use it, right-click in your Markdown Document and select `Open Preview` or use `Ctrl+Shift+V`(`Cmd+Shift+V` on Mac)

* This will open a side-by-side preview of your document as it will appear when formatted, which is helpful for checking your work as you go 

### 3. **Save your Markdown resume**
* After you've finished writing your resume, save your work by clicking on `File` -> `Save` or by pressing `Ctrl + S` (`Cmd + S` on Mac)

* Choose where on your computer you want to save it


## Host Resume on GitHub Pages

### 1. **Log in to your GitHub account.**

### 2. **Create a new repository** 

Create a new repository by following the prompts on GitHub to initialize and set up your repository for GitHub Pages.  

![Create Repo](https://github.com/Heejoy/Heejoy.github.io/blob/main/Gifs/create_repo.gif?raw=true) 


* Go to the main page of your account

* Click on the `New Repository` button

* Name your repository `<username>.github.io`, where `<username>` is your GitHub username

* Choose to make the repository public

* Initialize the repository with a README, if desired

* Click on the `Create Repository` button to finish the creation process.  

_This step follows Etter’s emphasis on using distributed version control_

### 3. **Upload your Markdown resume to your new repository**
<div style="margin-left: 20px;">
    <img src="https://github.com/Heejoy/Heejoy.github.io/blob/main/Gifs/Add_new_files.gif?raw=true" width="550" height="auto" alt="Add New File">
</div>

* Inside your repository, click on the `Add file` button and select `Upload files`

* Drag and drop your Markdown file or use the file explorer to select and upload your resume.

* Make sure your Markdown resume file is named as `index.md`

* Commit the file to the repository by entering a commit message and clicking on the `Commit changes` button.

<div style="margin-left:20px;">
    <img src="https://github.com/Heejoy/Heejoy.github.io/blob/main/Gifs/Commit.gif?raw=true" width="550" height="auto" alt="Add New File">
</div>

_Uploading your resume on GitHub reflects Eater’s emphasis on documentation and communication_

### 4. **Set up Jekyll for your GitHub Pages site.**
    
* In your GitHub repository, you need to create a new file named `_config.yml` for Jekyll configuration  

* Click on the `Add file` button in your repository and select `Create new file` and name the file `_config.yml`

<div style="margin-left: 20px;">
    <img src="https://github.com/Heejoy/Heejoy.github.io/blob/main/Gifs/Config.gif?raw=true" width="550" height="auto" alt="Add New File">
</div>

_This step perfectly encompasses Etter’s bias towards static websites_


#### **Specify a theme**

* You might start with basic settings like the theme. GitHub Pages support several [Jekyll themes](https://pages.github.com/themes/) that you can specify directly in `_config.yml`

* To apply a theme, enter the command `theme: jekyll-theme-THEME-NAME`, substituting `THEME-NAME` with the actual name of the theme in the `_config.yml` file

* For example, the resume in this project uses "minimal". You would add the following line to your `_config.yml`
       ```javascript
        "theme: jekyll-theme-minimal"
       ```
<div style="margin-left: 20px;">
    <img src="https://github.com/Heejoy/Heejoy.github.io/blob/main/Gifs/theme.gif?raw=true" width="550" height="auto" alt="Add New File">
</div>

#### **Add site details**

* You can customize your site further by adding additional fields to `_config.yml`

* Common fields include 
    * `title`- used to set the overall title of your website
    * `description`: provides a brief overview of your site
    * `author`: specifies the name of the site's author
    * Here's an example 
        ```javascript
        "title: <Name>'s Resume"
        "description: Resume for <Name>"
        "author: <Name>"
        ```  
* Now, commit `_config.yml` to your repository by clicking the `Commit Changes` button on the right top corner.
<div style="margin-left: 20px;">
    <img src="https://github.com/Heejoy/Heejoy.github.io/blob/main/Gifs/config_commit.gif?raw=true" width="550" height="auto" alt="Add New File">
</div>

### 5. **Visit your GitHub Pages site.**

* Your GitHub Pages site should now be live at `https://<username>.github.io`, displaying your Markdown-styled resume  

* It may take a few minutes for GitHub Pages to build and publish your site after you push your changes.

* Here is a live demo of the GitHub Pages site for this resume repository

    ![GitHub Pages](https://github.com/Heejoy/Heejoy.github.io/blob/main/Gifs/my_resume.gif?raw=true)

**_Congratulations! You have now hosted your resume on GitHub Pages using Jekyll and Markdown._**

### More Resources  
Create your own [GitHub](https://github.com/) account  
Download [Visual Studio Code](https://code.visualstudio.com/)  
[Check](https://code.visualstudio.com/docs/languages/markdown) more details about editing Markdown with Visual Studio Code    
Find more variables you can use with [Jekyll](https://jekyllrb.com/docs/variables/)  
Learn more about [GitHub Pages](https://docs.github.com/en/pages)

## FAQs

### Why is Markdown better than a word processor?

Markdown uses straightforward syntax to format text, making document creation faster and focusing the writer on content over design.  

Markdown files are simple text files. This makes them easy to use on different devices, share, and turn into other formats like HTML and PDF.   

Unlike traditional word processors, it saves time by eliminating the need to use your mouse to choose different formatting options; everything can be done directly with simple text commands.

### Why is my resume not showing up?

If your resume isn't showing, check the upload format and ensure it meets the site's requirements.   

Make sure your profile is fully filled out because missing information might hide your resume.  

If you change your webpage's look, like picking a new theme, it may take a little while to update. Just wait a bit and refresh the page.

### Authors and Acknowledgments
[Heejeong Kim](https://github.com/Heejoy): Author of Resume and  README file  
[Kevin Tsang](https://github.com/tsangkevin99): Peer editor and Group 7 member  
[Jonathan Placatka](https://github.com/jonathanplacatka): Peer editor and Group 7 member
