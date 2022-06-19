# Pyscript Textfsm Form using NTC Templates
Using Pyscript create a form where a text file can be uploaded and parsed using TextFSM templates
Form is completely standalone and does not require hosting. 

Must have access to the Internet though to reach the pyscript CDN

To illustrate the completely standalone capability of pyscript, all the python is contained inside the HTML file.
However, preference is to host the python .py files on a webserver since it is easier to troubleshoot and maintain.
Hence I developed this first by hosting the the python code and then moving it inside the HTML file once working.

Just copy or clone the **index.html** and **tabledemo.html** files and open up in your browser. Tested on Chrome but should work with other browsers

**Raw Output Demo**
![pyscript](https://user-images.githubusercontent.com/63735312/174481962-ea2c927d-a3eb-45e1-9d90-421a6a1f7be6.png)



**Table Demo**
![image](https://user-images.githubusercontent.com/63735312/174485798-619155d0-77b8-4ced-b670-1e2c8c64b60e.png)

The tabledemo.html file builds an HTML Table from the data
