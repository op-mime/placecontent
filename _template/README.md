#The 'template' Template#

The *"Place Content"* fixup in callas pdfToolbox uses an HTML file and converts it to PDF. This gives you a lot of liberty in how to structure your HTML, in how you link to other files such as scripts, CSS and fonts and in how to structure the folder you use to hold that template.

In this template folder you find one possible way to do this. You'll find a liberal use of sub folders and CSS and Javascripts that are referred to, rather than included in the HTML file. You're *free to follow this standard* or implement your own. Anything that would work for a normal HTML file, will also work here.

##Folder Structure##
The template uses several different folders and it's important to realise why:

- callas_tmp: you should *not* modify this folder. It's contents are overwritten automatically by pdfToolbox each time the place content fixup is used with this template. The folder will contain interesting files after such an execution, such as the PDF file generated by the template, an execution log file and the JSON file with information about the PDF document that can be used by your HTML template code.

- callas_library: this folder contains the Javascript and CSS files with support files. The purpose of these files is to make your life easier, but you should _not_ modify them for a specific project. These files are separate so that you can easily replace them if necessary with an updated version from the online GitHub.

- scripts: this folder is used to store project specific Javascript files.

- styles: this folder is used to store project specific CSS files.
