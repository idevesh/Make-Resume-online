# Resume generator
Web based editor to create Resume in a customizable template with the facility to save the file in .pdf format.  

**If you enjoy this project, please consider <a href="https://www.buymeacoffee.com/idevesh" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
 to continue developing and maintaining it.**



  
###### Live Demo : 

###### Technologies: HTML, CSS, JavaScript


**Note** : Click the "VIEW INSTRUCTIONS" button in the editor to read usage instructions.

#### Features
- Resume content can be edited just like a normal document editor (cut,copy,undo etc).
- Entire sections can be added, reordered, removed just by cut,copy,pasting method.
- Section visibility can be toggled while retaining the content.
- Options provided in the left panel to modify the template and formatting.
- Sub-points can be added with various bullet styles and adjustable indentation.
- Script provided to merge multiple pages and compress the PDF.

#### Using the merge & compress script
- You must be able to run python file on your system for this.
- Save the individual pages in PDF format with name ```1.pdf``` , ```2.pdf```
- Download the ```compress_pdf.py``` file and open it in a text editor.
- Set the following variables :
	- ```dir_path``` : Directory path where you saved the PDFs for individual page
	- ```num_of_pages``` : Number of files to merge (i.e. pages in your Resume)
	- ```out_file``` : Name of output file
- Run this python file.
- Note: As this creates a new PDF file, you may have to see permission settings or run with sudo on terminal.

**Note** : Use Google Chrome

----------------------------------------------------------------------------------------------------------------
To setup the project on your local machine:

1. Click on `Fork`.
2. Go to your fork and `clone` the project to your local machine.
3. `git clone https://github.com/idevesh/Online-Resume-Builder.git`


### Show some ❤️ by starring my repository! ![](https://visitor-badge.glitch.me/badge?page_id=idevesh.Make-Resume-online&style=flat-square&color=0088cc)
