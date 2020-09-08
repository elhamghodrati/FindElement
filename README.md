# FindElement
Webtesting

Local Extension Installation Guide:
1. Download and save the Chrome Extension LAST VERSION file.
2. Go to chrome: // extensions / and to use the first extension, you must upload it to your extensions.
3 - At the top left of the screen, press the load unpacked button and select your Chrome Extension file folder from the window that opens.
4. In the Google Chrome popup menu, use the Extensions tab to pin the Get element program.
5 - Open the desired website and click on Extension Get element.
6- A blue tab opens on the left side of the screen
7 - By clicking on different elements of the page, the CSS and XPath path of that element can be seen
8- Finally, by clicking on the Export JSON option, it will give you a file with the JSON extension.

Test guide:
You can test the output.
1. Open the JSON file.
2. You will see all the elements you select as an array of objects.
See an element of the Golem site here:
 {
      "cssSelector": "HTML.js BODY.index.golem-flip-std-body DIV.golem-flip-std DIV # grandwrapper.golem-zo-grandwrapper.iq-site-wrapper HEADER # header.iq-site-header DIV.dh1 A IMG ",
      "relxpath": "//***@alt='Golem.de - IT-News für Profis']",
      "ID": "",
      "tagname": "img",
      "classes": "",
      "style": "width: 212px;",
      "alt": "Golem.de - IT-News for Profits",
      "Text": "" ,
      "rect": {"height": 42, "width": 212, "x": 0, "y": 0}
    } ،
3- In this section, you can test whether the production route is correct or not.
Press the F12 key and in the console section, enter the following command to test the CSS selector, and press the Enter key.

 document.querySelector ("HTML.js BODY.index.golem-flip-std-body DIV.golem-flip-std DIV # grandwrapper.golem-zo-grandwrapper.iq-site-wrapper HEADER # header.iq-site-header DIV.dh1 A IMG ")

4- Please change the value inside the quotation according to the updated JSON output file to see the new routes.
5. Use the following command to test XPath.
$ x ("// * [@ alt = 'Golem.de - IT-News für Profis']")
6- Please pay attention to single quotation and double quotation
