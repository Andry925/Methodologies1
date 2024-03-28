# Markdown to HTML convertor

This is a tool for converting Markdown I have developed as the first laboratory. My program converts most common 
Markdown such as  bold text (**), monospaced text (`),italic text (_) paragraphs and backticks.My program also handles both
**Cyrillic** and **Latin** letters.
In addition to converting Markdown to HTML, 
the program is designed to output the converted HTML both to a file and to stdout
I also implemented error handling which detects various issues, like not closed tags, invalid combination of tags. 
As an enhancement to main functionality, my program also converts some valid nested tags into html.

# How to install

1. First you must make sure that you have Python installed
(3.10 version is preferable, but it must run on almost all versions, because I did not use any external packages).
2. After that, you have to clone this repository and enter the working folder :
```bash
$ git clone https://github.com/Andry925/Methodologies1.git
$ cd Methodologies1/
```
3. In order to start type the following command  :
```bash
$ python3 -m main.convertor [file path to a markdown file] (--out [file path to an html file])optional
```

# Usage 
I also decided to add the markdown_files package, which holds some Markdown files with examples to show how my program 
handles different types of tags and catches errors.
1. The application outputs the generated HTML markup to the standard output or to the HTML file(if specified).
   ![Screenshot from 2024-03-28 15-54-07](https://github.com/Andry925/Methodologies1/assets/114020399/787b888f-87e9-4e5b-80d0-7a46eedc82e2)

   Or you can also specify the path to a file to store generated html(if the file with this name does not exist it will 
   be created)
   
   ![Screenshot from 2024-03-28 16-00-54](https://github.com/Andry925/Methodologies1/assets/114020399/655a4831-c473-469f-8b86-71916fcbd265)
   
    Also do not forget to add <meta charset="utf-8"> to the 
    html to correctly display Cyrillic letters.

# Link to revert commit

[Here you will find revert commit](https://github.com/Andry925/Methodologies1/commit/3b6a3e5ba5f09c37cfcc954f8a60d81ae7183de3)
