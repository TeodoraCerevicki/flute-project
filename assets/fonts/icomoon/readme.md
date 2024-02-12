
# How to add new icon

1. go to <https://fontawesome.com/icons>, find the icon you need, download svg file for the icon
2. rename svg file to something simple (without icon prefix), e.g. "close.svg"
3. go to <https://icomoon.io/app/>
4. go to menu -> manage projects
5. import project, choose file selection.json (src\assets\fonts\icomoon\selection.json), and click load
6. go to set menu (on the right) and unselect all icons
7. go to set menu (on the right) and choose import to set, choose to upload svg (ensure that the file is named in a simple way (step 2), icomoon will add prefix "icon-")
8. in the menu at the top of the page find an option Move, choose the newly added icon and drag it all the way to the end
9. go to set menu (on the right) and select all icons
10. click generate font at the bottom of the page and then download
11. unpack zip icomoon folder somewhere on your PC
12. go to assets/fonts/icomoon folder and replace all icomoon files, style.css, selection.json and demo.html with newly downloaded version
13. in downloaded version open style file, you will get the list of icons
14. select the ones you've added
15. open src\styles\partials\vendors\libraries\icomoon\fonts.scss and paste icons on the bottom of the file
