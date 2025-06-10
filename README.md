# DigitalTreasureHunt_NA

# DigitalTreasureHunt with No Arduino. Adapted for use with no Arduino kit. 
Overview
The Cyber Treasure Map project is an interactive web application designed to engage users in solving a series of puzzles and clues to find the hidden treasure. The map incorporates various elements and icons that users can click on to receive hints and guidance.

The project consists of an HTML files that includes embedded CSS for styling and JavaScript for interactive functionalities. The project uses external libraries such as Bootstrap and SweetAlert for better UI/UX.

Files and Directories
index.html: The main HTML file containing the structure and content of the web application (The treasure map). The link to the first webpage is located here.
web_page1/: Directory containing the code, images, and other resources for the first webpage. 
webPage2/: Directory containing the code, images, and other resources for the second webpage.
treasure.html: The third and final webpage. Contains the treasure chest.
icons/: Directory containing icon images used in the treasure map.
treasureMap2.png: The background image of the treasure map.'
files/: Directory containing the activity files and student guide. 
files.html: The first webpage. All the other webpages will be accessed using this webpage. 
math.html: The second webpage. Contains the math problem that needs to be solved. 

External Libraries:
Bootstrap CSS and JS
SweetAlert for alert dialogs
jQuery for DOM manipulation

Dependencies
The project relies on several external libraries, which are included via CDN links:

Bootstrap (v5.3.0-alpha1 and v4.5.2)
SweetAlert2 (v11)
jQuery (v3.6.0 and v3.5.1)

Usage
Running the Application
Open index.html in a web browser.
The treasure map will be displayed with various clickable icons.

Interacting with the Map
Icons: Click on the icons scattered across the map to receive hints and clues.

Icons and Their Hints
Balloons: Hint related to the elements and their symbols.
Kite: Hint about a historical figure associated with electricity.
Globe: Grants access to the first webpage.
Cipher: Provides a Caesar Cipher hint.
Keypad1: Requires the year the Declaration of Independence was signed.
Light: Hint about the inventor of the incandescent electric light bulb.
Calcium: Hint related to the element found in milk and bones.
Tesla: Hint about the inventor and the automobile company named after him.
Radio: Hint about the password related to the invention of the radio.
JC: Hint about Julius Caesar and the Caesar Cipher.
Bifocals: Hint about the inventor of bifocals and the only non-president on American currency.
Keypad2: Requires a code from solving a math problem.
Declaration: Another hint about the Declaration of Independence.
File: Instructions about opening files to find the treasure.

Files and Their Usage
Calcium.pdf: Contains the caesar cipher diagram.
BenjaminFranklin.pdf: Contains the instructions on how to use the Caesar cipher. 
NikolaTesla.txt: Link to the second webpage (login2.html/math.html).
Helium.pdf: Link to the third webpage (treasure.html/lastCode.html).
All other files are set to 'self destruct' using a sweet alert once they are clicked.

Customization
To customize the treasure map, you can modify the index.html file:

Update the background image by changing the background property in the CSS section for #map.
Add or remove icons by updating the <img> tags within the #map div.
Modify hints and messages in the JavaScript section where Swal.fire is used.

Credits
Author: Alexis Ouellette, Kyle Nguyen
ChatGPT was used to create all icons and background images.
Libraries: Bootstrap, SweetAlert2, jQuery
