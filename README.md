# today-i-learned

.md stands for markdown

that was a test text for course.

but it appears in #header somehow

#### To create paragraph use a blank line.

For more info use **[this Basic](https://www.markdownguide.org/basic-syntax/)**.

***[Markdown Editor](https://dillinger.io/)***

hidden folders after git init. ls -a - shows list with hidden files and folders (-a for *all*).

cd - перехід в директорію, cd for one level up or cd ~ and go to

ls - список

touch - створити файл (touch test.txt creates the new text file with the name test). *! about speed of the action, does it worth it?*

mkdir - creates directory (mkdir new folder)

cp - copy

mv - move

cat - opens (reads) the file (cat test.txt)

=============================================

**always use git status before git commit**

git add - adds files from choosed directory to the staging area (commands git to look for those files) (git add test.txt)

git add . - all files in a directory will be added to the staging area

check with git status

*all git commands use in git directory that was added to the git previously with git init (to check use git status or ls -a)*

*also with git status you can check the spelling of the files in the selected directory/*

to save or create a shot of changes (and move the file from the staging area to the git) use git commit (git commit -m "first commit"). Git will create a record of those files (record changes in those files that has been added to the staging area (green ones))

commit - здійснити, вчинити.

"- m" after git commit is "message" - description of changes.

git restore --staged <file> - to remove a file from the staging area (git restore --staged test.txt) does not worked in my module-git
  
git clone link - copies project to the local machine.
  
[Git HOWTO](https://githowto.com/uk)
  
git remote -v - shows all remote repos.

html - structure, css - colors, sizes.
  
[can I use](https://caniuse.com/)

[Bootstrap](https://getbootstrap.com/)

[test](https://codepen.io/pen/)
  
**[Довідник HTML](https://developer.mozilla.org/en-US/)**
  
**[Code Pan - online редактор для HTML/CSS/JavaScript](https://codepen.io/)**
  
div.TAB
  
CTRL+~ - opens terminal in VSCode
  
< !-- enter (or CTRL/)- comment line

*h1* shold be only one!

Shift+TAB moves selected rows in VSCode.

CSS <style> puts in html head

colours in CSS starts with # or rgb.

id should be only one(do not use it!). For more united elements use class.

.(dot) and # - selectors for class

CSS vlastyvosti ne chipliaty na ID - nikoly! Do not use id for werstka.

ne yusay style na elementakh

link only in head
  
  парсер іде згори донизу, тому видно буде ті стилі, що в останньому лінку.
  
  css 2 1:16
  
  on page Network all can see haw it reads
  
  margin - outline stroke
  
  pedding - inline stroke
  
  Ctrl+Shift+R renew and clears cache.
  
**USE dash - dash in styles and classes names!**
  
  div - block
  
  span - just for the content size inline
  
  16px - defolt font size in Chrome.
  
  vw and vh - scales element size when you change window size by heigh and with.
  
  div.wrapper+enter - adds all symbols to div and creates class with name from text after the dot "wrapper".
  
  you can't change size of the inline object. Inline object is always according to content size.
  
  4 - 35:48
  
  **flexbox** is enough
  
  browser coordinates starts with 0 zero
  
  right (flex-direction: row) - **X**
  
  down (flex-direction: column) - **Y**
  
  flexbox builds container
  
  *var* - variable, will change all variables used in file.
  
  *:root* - will be available in all style file
  
  *justify-content: space-between* - вирівнює рівномірно (дві колонки рівно по площі)
  
  *justify-content: center* - в центрі
  
  *flex-wrap* - переносить блоки по розміру екрана
  
  *flex-grow: 2;* - рости на число більше(швидше) від інших
  
  *flex-shrink* - зменшуватись.
  
  *flex-basis: 25%;* - початковий розмір елемента % від всього контейнера.
  
  *flex: 1 1 auto;* - де 1 - ґроу, 1 - шрінк, auto - бейзіс.
  
  html-css-module-5 1-20-50
  
  <a href="#" - not open any link
     
 **page grid has 12 columns**
     
 [вага стилів](https://specifishity.com/)
     
 media queries - запускає стилі на різних розмірах екрану.
     
@media (min-width: 200px) and (max-width: 600px) у межах між
 
 with - для конкретного значення.
 
create grid (12, 10, 24 ....) html-css7 1:16:30
     
create mediaquery - html-css7 1:28

 js1 48 - home task
     
**do not duplicate the code**
