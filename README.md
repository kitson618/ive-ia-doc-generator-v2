# ive-ia-doc-generator-v2
<b>IA-Generator</b>

This project is used to auto fill in industrial attachment document of Hong Kong Institute of Vocational Education(IVE) 
Successor of ive-ia-doc-generator-legacy 
All credit goes to: Mark Lai (IT114115/2B 2017-2018)

inherit from version one by marklai1998 

origin: https://github.com/marklai1998/ive-ia-doc-generator-legacy/tree/master/web

-------------------------------------------------------

In case this is your first time using Github

Press the green "Clone or download" on the top right hand corner

Then press "Download ZIP"

To download the generator

-------------------------------------------------------

<b>How to use</b>

open run.bat with admin right

LOL if chrome.exe not found (Install chrome and try again)

---------------------------------------------------------
<b>Change Academic Supervisor Signature</b>

page of the signature in template: p16, p26

1. Make sure you have the png file in ./sign folder
2. In index.html find out part of signature and change those options for you want.
   Be careful, the value of those options must be same as the png files.
   For example, if your png file was named example.png, the value of option should be example.
3. If you want to change the size of signature, ./javascript/main.js the function getSize can help you.