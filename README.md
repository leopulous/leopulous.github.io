# Writing a resume in Markdown and host it on GitHub Pages

Either you are writing a resume from scratch or forking a template resume and edit it in Markdown, this guide is your one stop for everything you need to know about resume writing in Markdown. This will not be a sole guide on writing a resume or a Markdown tutorial. However, we will include some of their references in our documentation.

---
## Table of content
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Download and Installing Atom](#download-and-installing-atom)
    - [Working with Atom](#working-with-atom)
  - [Markdown and Resume](#markdown-and-resume)
    - [Getting familiar with Markdown](#getting-familiar-with-markdown)
    - [Writing an effective resume](#writing-an-effective-resume)
    - [Writing resume in Markdown](#writing-resume-in-markdown)
  - [Hosting your resume and README on GitHub Pages](#hosting-your-resume-and-readme-on-github-pages)
    - [Creating a GitHub account](#creating-a-github-account)
    - [Create a repository and host your website](#create-a-repository-and-host-your-website)
  - [Formatting your resume with a Jekyll theme](#formatting-your-resume-with-a-jekyll-theme)
    - [Forking a Jekyll theme](#forking-a-jekyll-theme)
    - [Format your resume with Jekyll template](#format-your-resume-with-jekyll-template)
  - [Tools and References](#tools-and-references)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  - [FAQs](#faqs)

---
## Getting Started

These guide will provide a step-by-step instruction on installing Atom text editor for you to write your resume and preview it on Markdown form. You will learn to write a resume and some useful Markdown syntax, then we will sign up for a GitHub account and host our resume.

### Prerequisites

The set of instruction is for beginners with no experience in using Atom, Markdown and GitHub or even Jekyll.  

We will write and edit our resume on Atom. What you need to install Atom:

> Any convenient web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge).

### Download and Installing Atom
  1. Visit Atom's [website](https://atom.io).
  2. Press on the yellow download button on Atom's front page.  
  ![Atom page](https://ibb.co/MGxvRt8 "Atom front page")   
  3. After directing the folder you want to save the file on, click save to downloaded file onto your computer.
  4. Launch the Atom's setup file from the download directory, Atom will install itself without taking the user through many configuration steps.
  5. When Atom finishes installing, it will launch into the program. You should see this Atom's window:  
  ![Atom UI](https://ibb.co/3vQkgB5 "Atom UI")

### Working with Atom

Now that we have Atom installed, we can go ahead and create our markdown file:  
  - From the top left menu, click on **File** and choose **New File** from the drop down menu or use the keyboard shortcut `Ctrl + N`.
  - This opens an untitled tab on your Atom's application.
    - To have more space you should close other opened tab that we don't need by pressing on the X button on the tab.  

Before we start writing the resume, it's a good practice to save our files first:  
  - Save the file into a directory by either using the short cut `Ctrl + Shift + S` or choose *Save as* from the **File** drop down menu.  
  - Enter our file name `index.md`. Now we can write our resume on this file and save it regularly in Atom using `Ctrl + S`.
  - To view our Markdown live as we write the resume, on the upper toolbar, click on **Packages** and hover over **Markdown Preview** on the drop down menu.
  - While `Toggle Preview` shows you a normal preview on Atom, `Toggle GitHub Style` provides a preview of your Markdown file should you ever wish to host your resume on GitHub, which we will cover later. You can choose either, depending on your preference.

## Markdown and Resume

### Getting familiar with Markdown

To learn extensively about Markdown, there are many resources. I would recommend [Mardownguide](https://www.markdownguide.org) for cheat sheets and references.

For the sake of writing a resume, we will only need some relevant Markdown syntax:

> Headers, Emphasis, Lists, Blockquotes and Line Breaks.  

With these in mind, we can get to writing our resume.

### Writing an effective resume

Ordering the information in your resume is critical technique to utilize the Markdown applied:
- Since employers usually spend a short period of time reading the resume, put the most important information first (e.g. technical skills, projects, qualifications that matches the job descriptions)
- Choose the right style of resume to leverage of your abilities. This following table is included in ***University of Manitoba***'s **Career Services**' [documentation](https://umanitoba.ca/student/careerservices/media/Resume.pdf) on resume types:

| Resume Type   | Overview      | Advantages  |
| ------------- |:-------------:| -----------:|
| Chronological | Highlights job experience with most recent experience first. | Good for strong, consistent, relevant work history.|
| Combination   | Allows you to showcase your most relevant skills while offering reverse chronological detail.|   Can help people with limited related work experience highlight their skills first by allowing for school, volunteer, work, and extracurricular activities to be easily integrated.  |

- Make use of Demonstration Statements with Action Verbs to show you are capable of performing specific tasks and responsibilities in an appealing way to the employers.

### Writing resume in Markdown

Markdown comes in handy for convenient highlighting of important information in our resume. It is also easy to read even in the non-preview window.  
Here are tips and pointers to make the most out of Markdown in our resume:  
> 1. Different Markdown headers can help highlight headers quick and easily with different fonts.
> 2. Highlight keywords and phrases with emphasis syntax or make them stand out with blockquotes.
> 3. Outline your experiences and skills using ordered and unordered list.
> 4. Separate different sections with horizontal rules.
> 5. Line break is to separate unconnected paragraphs and provide space to the resume's look.  

---
## Hosting your resume and README on GitHub Pages

Once you have written your resume and README in Markdown, they are ready to be hosted on GitHub on your own website. These easy-to-follow instructions will advise you on getting familiar with GitHub Pages and display your resume for future employers.

### Creating a GitHub account
GitHub Pages provides each GitHub account with a public site. In order to host your website, we need a GitHub account:
> 1. Visit [GitHub](https://github.com) and enter your information on `Username`, `Email` and `Password` textbox.  
> ![GitHub home page](https://ibb.co/NY4Yjs9 "GitHub home page")
> 2. After you finished, press on `Sign up for GitHub` and we have created a GitHub account. You will need to choose a Personal Plan to use public or private repositories depending on your preferences.

### Create a repository and host your website

Our website needs a folder to hold the data. We will apply the following order of procedure to host our website:
> 1. Create a new repository using the green `New` button on the leftmost `Repository` tab.
> 2. You will be taken to a new site with a **Create a new repository** header:  
> ![New repository](https://ibb.co/kQ69w0t "Create a new repository")
> 3. In `Repository name` textbox, enter _username_.github.io, where *username* is your username on GitHub. Change other settings as desired.
> 4. Since we have a written ```README.md```, we can skip past the `Initialize this repository with a README` and upload our own later.
> 5. After pressing on `Create Repository`, GitHub takes you to a `Quick Setup` page, where you can choose from a variety of choices on how to fetch data into your repository.  
> ![Quick Setup](https://ibb.co/1mL3p1G "Quick Setup")
> 6. Since we are uploading our local files, click on the `uploading an existing file` hyperlink. Then an upload dialog box will open where you will navigate to the folder path where your Markdown formatted resume is.
> 7. Once the file has finished uploading, scroll down to the bottom of the webpage and enter descriptions, then click on commit changes to the branch.
> 8. While your `README.md` is displayed under the list of files in the repository, to view your website where your Markdown Resume is, go to this `Settings` tab.
> 9. Scroll down the Settings page until you see the `GitHub Pages` headings. Your site needs a `Source` so choose the `master` branch.  
> ![GitHub Pages](https://ibb.co/KXwtLvJ "GitHub Pages")

The URL hyperlink should take you to a new page where your resume is hosted.

---
## Formatting your resume with a Jekyll theme

Our work is not completed until we apply a Jekyll theme to our resume. This is required by GitHub for any page that you want to host on. The following steps will perform forking a Jekyll template and use it to format our resume.

### Forking a Jekyll theme
These following steps will demonstrate how to fork a Jekyll theme on GitHub repository:
> 1. To find any Jekyll theme supported by GitHub, go on [Google](https://www.google.com/?gws_rd=ssl) and type `Jekyll theme resume`, you will see many Jekyll templates hosted on GitHub for public use.  
  >- For this example we will use Sproogen's [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)  
> 2. On the same line with the repository's name, to the right is the `Fork` button. To fork is to make a copy of a repository, which means you can freely experiment it without affecting the original files.
> 3. After pressing on `Fork`, the first thing we do is to rename the reposity to match our site. This is because GitHub needs to host repository with the correct format ```_username_.github.io```.  
  > - To edit repository's name, go the `Settings` tab and insert the new name into the textbox.  
   ![Settings tab](https://ibb.co/9GMNFMP "Settings tab")  
> 4.  Remove any file named `CNAME`. Jekyll template designers usually leave a `CNAME` file with the link to their custom domain as an alternative link for ```_username_.github.io```. Not removing the `CNAME` will cause problem when GitHub Pages tries to host your website.

### Format your resume with Jekyll template
Formatting does not require you to have prior knowledge of Jekyll. Unless you want to directly alter the layouts of the template, you have to learn about Jekyll template's structure. I would recommend Mike Dane's [tutorial](https://www.mikedane.com/static-site-generators/jekyll/).

As for our current Jekyll template, our main files are of `.yml` extension, which is the YAML file format, a recursive acronym for ***YAML Ain't Markup Language***. This means that we should only copy our information into `.yml` without Markdown to avoid mixing them with YAML's syntax.  
Note that YAML is a data-serialization language so our main goal is translating data into a format that can be stored. A forewarn is that after you make adjustment to `.yml` files in your repository, there is a span of one minute for GitHub Pages to show the updated changes onto the page.

It's best to read over the template's README.md to have a good view of where to store our information.   
The first file we visit is `_config.yml`.
   - The `_config.yml` file should include our name and contact information.  
   ![_cofig.yml](https://ibb.co/LPs53Rk "_cofig.yml")
   - You can edit the titles of headings according to your resume headers.
   - Comment out any unnecessary values and headers with `#` or just delete them.
   - Follow the notes in the file that the author noted on what we can make changes to.
   - A `|`  symbol after a key and before a value will allow new lines for paragraphs, while a `>` symbol will turn new lines into spaces.

For other parts such as Education, Experience, Projects etc., the `_data` folder usually provide these information in terms of separate `.yml` files.
- Overall, data within a `.yml` is usually stored as a key - value pair. For the files already available in the folder you can change the value information with your own and create new key - value pair should you wish. 
- The editing style is similar to how we did for `_config.yml`, only without headers and we have to divide information across several files.  
  ![_data folder](https://ibb.co/z4tNQ9g "_data folder")

## Tools and References

* [Atom](https://atom.io) - Editor
* [Mardownguide](https://www.markdownguide.org) - Tutorial for Markdown
* [GitHub](https://github.com) - Website hosting through repositories
* [GitHub Pages](https://pages.github.com) - Guides on hosting your website on GitHub from different methods.
* [Jekyll Tutorial by Mike Dane](https://www.mikedane.com/static-site-generators/jekyll/)
* [Sproogen's modern-resume-theme](https://github.com/sproogen/modern-resume-theme)  

---
## Authors

  ***Nguyen Thu Lam*** - follow me on [LinkedIn](www.linkedin.com/in/liamnguyenn98) or visit my [Github](https://github.com/leopulous).  

---
## License

This project is licensed under the GitHub License.

---
## Acknowledgments

My wonderful teammates who took time to listen and help me solve obstacles that I encountered during the process of writing this `README.md`.  
The talented developer James Grant who created the `modern-resume-theme` Jekyll template.

---
## FAQs

---
**Question**: The `.yml` files in `_data` folder doesn't cover enough sections of my resume. What should I do?  

**Answer**: You can, in fact, create another `.yml` file for other additional sections like Soft Skills, Events Participated, Awards but you have to learn Jekyll and HTML / CSS syntax to edit the layout files in `_layouts` folder to include new files.  

---
**Question**: What is Atom and why do we need it to write our resume in Markdown?  

**Answer**: To work with Markdown you will need a text editor. Atom is the most suitable editor for this task. Atom is a free and open source code editor which is executable on many popular operating system such as Windows, macOS and Linux. It also integrates with GitHub so we can edit our file on Atom and push it on to GitHub repository. Visit [here](https://github.atom.io) for more information.
