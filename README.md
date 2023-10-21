# Pathology-AutoHotKey
This is a set of templates and instructions for pathologists who intend to use AutoHotKey. The guide is written for Windows users and may not be useful on Mac/Linux/other operating systems.

# Instructions
### Download and install AutoHotKey
If you do not have the ability to install files on your computer, such as corporate controlled computers, you can download the zipped file: "Program/AutoHotKey.zip" and extract that into a folder you can modify, such as your user folder or the Desktop. Even if you can install files on your computer, you may prefer this method. You do you. Otherwise, you can download and install AutoHotKey from the website: "https://www.autohotkey.com/". Downloading from the website will better ensure an updated version of the program.

### Run a template
.ahk files are scripts that AutoHotKey interprets. You can create your own templates or download my templates in the "Files/" folder. They will look like "Files/[template-name].ahk". These can be saved anywhere on your computer. To run the template, in Explorer, right click on the filename, then select "Open with..." Scroll down to the bottom and select "Choose another app". Select AutoHotKey.exe. Now your the template is running. To test it, open Notepad and type in a few of the template calls. If you're using my AP or AP/CP template, try "masd&#92;". It should write "microscopic analysis substantiates the final diagnosis."

### Customize templates
<ol>
  <li>Right click the template: "[filename].ahk". Scroll down to "open with...", and select "Notepad++" from the dropdown menu. If you don't have Notepad++, get it here: "https://notepad-plus-plus.org/"</li>
  <li>This is the script that contains the templates. Any changes you make here will change the templates</li>
  <li>To add a new template just follow the format that's already there, namely:<br>
    ":*:[shortcut]::[template]"<br>
    &#8245;r = new line<br>
    &#8245;t = tab/indent<br></li>
  <li>Save the file and then double click it (feel free to rename it). This will make sure the new script you've saved is running rather than the old one.</li>
  <li>If you want to do anything fancy, there are more powerful things you can do with Autohotkey, and tutorials are available at https://www.autohotkey.com/.</li>
</ol>

