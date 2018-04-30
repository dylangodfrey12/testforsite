Joseph is the only person that should be looking at this

STEPS TO CONFIGURE SITE LOCALLY

1) DOWNLOAD THE REPOSITORY AS A ZIP

2)USING VISUAL STUDIO CODE OPEN THE UNZIPPED FILE 
=> https://code.visualstudio.com/download 

3) IN VISUAL STUDIO CODE CLICK VIEW/INTEGRATED_TERMINAL (This is in control panel i.e File,Edit,Selection,VIEW).

4) IN THE TERMINAL AT THE BOTTOM RUN: npm install --only=dev
(THIS WILL INSTALL ALL THE DEPENDENCIES YOU NEED MAY TAKE 5MINS ALSO MAKE SURE YOU ARE IN CONSTRUCTION SITE DIRECTORY)

5) RUN IN TERMINAL: node main.js
(this will start local server)

6)Navigate in your browser to localhost:5000 to view site

FYI

HTML FILES ARE IN THE VIEWS DIRECTORY NOT THE DIST.
STYLESHEETS ARE IN PUBLIC DIRECTORY NOT DIST!

TO PUSH TO GIT:

1) In source control on the left handside click the symbol that looks like a node branching to two nodes.

2) select the check mark at the top after adding a descriptive message below that checkmark.

3) in your terminal run: git push


contact me if anything fails!