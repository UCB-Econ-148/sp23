## ECON 148 Spring 2023 website

This [video](https://www.youtube.com/watch?v=azPPK5aOcV0) walks you through how to make changes to the website in general, though it was for a different class.

### Getting Started for Staffs
1. How to edit the calendar schedule  
Go to `_modules` and edit the markdown file for the corresponding week. For a list of label styles, see [here](./_sass/custom/module.scss). 
2. How to edit course staff profiles  
Go to `_staffers` and edit the markdown file for the corresponding staff. You can also update their profile pictures in `resources/assets/staff_pics/`. Make sure the file names match. 
3. Syllabus and Resources can be edited in the correponding markdown files.   

Note to staff: **Always** pull changes before making any edits. 

<br>

---

The following text is taken from the standard GitHub Pages README.

<br>

You can use the [editor on GitHub](https://github.com/pmarsceill/test-jtd/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pmarsceill/test-jtd/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Running Locally

This website is written using Jekyll Bootstrap with some modifications to
improve support for github pages.

Install `rvm`: https://rvm.io/

Install Ruby 2.2.0:

    rvm install 2.2.0

Clone this repo:

    git clone https://github.com/DS-100/DS-100.github.io

In the repo directory, run:

    gem install bundler
    bundle install

Finally, serve the project locally with:

    jekyll serve

This will start the local Jekyll server at http://localhost:4000.
