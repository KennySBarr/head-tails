<p align="center">
 
![R](https://github.com/user-attachments/assets/598285a7-2faa-4be9-bca6-8fa666252511)

</p>

<h1> Searching and Previewing Files using Head, Tail, More, and Less</h1>
You are continuing in your role as a security analyst at Candy Corp, investigating the employees potentially selling secret recipes to Sugar Corp.
Your manager at Candy Corp has identified two possible insiders who may be working with Sugar Corp: Henry and Ruth.
Your manager pulled some files from Henry and Ruth's computers without their knowledge.
Some of the files contain gibberish, but some may have useful data.
Your manager has asked you to preview the files to see whether they have readable text data that can be analyzed later.
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Linux Command Line

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2> Naviating Linux

<p>

 ![Screenshot 2024-11-24 203002](https://github.com/user-attachments/assets/839ae08e-040f-4d80-b66e-470a1b88218b)


>
</p>
<p>
STEP 1: There are two folders inside the /03-student/day1/oh_henry/ folder:
  
  One for files captured from Henry and one for files captured from Ruth.
  
Use the preview commands to determine which of the files contain readable text data.

  
  - Use the "less"  tool to preview a file in Linux to see what's inside of a file

</p>
<br />

<p>
  
![Screenshot 2024-11-24 203310](https://github.com/user-attachments/assets/3f407977-217c-4a7c-9a4f-11cdf50e963f)



>
</p>
<p>
STEP 2: Using the "Less" tool followed by the file name, see if there are read-able or non-readable text in the file

- I used the "Less" command where I was able to see the contents of do.txt, allowing me to see it does contain read-able content
  
</p>
<br />

<p>
  
![Screenshot 2024-11-24 204240](https://github.com/user-attachments/assets/78b533eb-27fc-458d-93bb-7d798c2bff07)




>
</p>
<p>
STEP 3: Using the "Less" tool I found that files: spt.txt, do.txt and wp.txt had read-able content

-  - Use "rm" tool followed by the files that contained non-readable text data
  
</p>
<br />



