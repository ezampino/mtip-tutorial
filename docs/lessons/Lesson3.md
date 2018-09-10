## Lesson 5: Introduction to GitHub for managers (non-programmers)
##### [Back to Home](../index.md)
### Overview:
- [Getting started](#getting-started)
- [Organization](#organization)
- [Markdown](#markdown)
- [Content types](#content)

### Getting started

GitHub itself isn't much more than a social network like Facebook or Instagram. You build a profile, upload projects to share and connect with other users by "following" their accounts. While many users store programs and code projects, there's nothing preventing you from keeping text documents or other file types in your project folders to share publicly (or privately). It is capable of storing any file type from text, to structured data, to software. And more features are being added by the day. The real power of Git, however, is less about individuals publishing content (many places can do that, including google docs etc). It is more about that content being easily shared, built upon, and credited in a way that is robust to the realities of distributed collaboration. While the power of GitHub is daunting, you don't actually have to be a blackbelt to gain a lot of benefit from using it. You don't even have to know how to code or use the command line.

### Organization

Git supports the following types of primary entities:

- **Individual:** A person who contributes to GitHub (that's you!)
- **Repository:** A collection of versioned files (of any type)
- **Organization:** An entity that may correspond to an actual organization (such as a university) or to a meaningful grouping of repositories. Organizations are like individuals except that they can establish teams.
- **Teams**: A group of individuals assembled by the administrators of an organization. An individual may participate in many teams and organizations, however a team is always bound to a single organization.

The relationships between any combination of these entities is many-to-many, with the nuanced exception of repositories.
For our purposes today we will oversimplify by saying that a repositoy belongs *either* to a single organization or to a single *individual*.

![](../howto/images/github-organizations-teams-repos.png)

### Task - create a new GitHub repository
- [Create your GitHub account](https://github.com/)
- Customize your avatar
	- Click the upper right hand corner
	- Choose settings
	- Upload new picture
- Create a repository 
	- click New next to "Repositories" on the left
	- give your new repository a name, like MTIP-test
	- Give it a description
	- Make it public
	- Click "Initialize this repository with a README"

### Markdown

Content in GitHub is written using Markdown, a text-to-HTML conversion tool for web writers [(ref)](https://kirkstrobeck.github.io/whatismarkdown.com/).

For more help with Markdown, see this [GitHub guide](https://help.github.com/categories/writing-on-github/).

| Raw markup syntax | As rendered |
|-------------|------------|
|`Emphasis, aka italics, with *asterisks* or _underscores_.`|Emphasis, aka italics, with *asterisks* or _underscores_.|
|`Strong emphasis, aka bold, with **asterisks** or __underscores__.`|Strong emphasis, aka bold, with **asterisks** or __underscores__.
|`Combined emphasis with **asterisks and _underscores_**.`|Combined emphasis with **_asterisks and underscores_**.|
|`Strikethrough uses two tildes. ~~Scratch this.~~` | Strikethrough uses two tildes. ~~Scratch this.~~ |

### Task - update the content in your README
- Go back to the repository you just created
- Click the pencil icon in the right corner of your README.md file
- Add some content to your file that includes italics, bold, unscores and strikethrough
- You can preview your changes before committing by clicking 'Preview changes'.
- Commit your changes by clicking the commit button at the bottom of the page.

### Content types

GitHub can store any kind of content, provided it isn't too big. (And now [even this is possible](https://git-lfs.github.com/)).
However, it is more capable for some filetypes than it is for others. Certain filetypes can be viewed 'natively' within the GitHub interface. These are:

- Images: png, jpg, svg
- GEOJSON
- CSV, TSV (note that files named type '.tab' will not render properly in the UI.)
- Markdown
- Software code (eg. including json, HTML, xml etc)
- Any of these can also be set up outside of a repository but within your use

### Task - add content to your repository
- Click on the code button
- Upload a file by dragging and dropping or browse for file
- Trying uploading an Excel file vs a TSV or CSV file. How are these displayed differently?

Note: You can create folders in your GitHub repository, just like on your computer.

### Gitter
Gitter is a chat platform (like Skype, Slack, etc.) that is linked to GitHub accounts.

We created a Gitter room for this tutorial, please join [here](https://gitter.im/tis-lab/MTIP-tutorial?utm_source=share-link&utm_medium=link&utm_campaign=share-link).


### Additional Resources
- [Frequently Asked Questions](FAQ)
- [Git and GitHub for Documentation](http://www.slideshare.net/annegentle/git-and-github-for-documentation)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Git 101: Git and GitHub for Beginners](http://www.slideshare.net/HubSpot/git-101-git-and-github-for-beginners)
- [Mastering Issues (10 min read)](https://guides.github.com/features/issues/)


##### [Click here for Lesson 6](https://data2health.github.io/mtip-tutorial/lessons/Lesson6.html) 
### [Back to Home](../index.md)

