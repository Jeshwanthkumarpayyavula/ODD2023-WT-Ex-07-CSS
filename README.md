# Ex-07-CSS
# Name: Jeshwanth kumar
# Ref.no:23002519
# Aim:
Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme: Background color: Light gray (#f4f4f4) Text color: Dark gray (#333) Link color: Blue (#007bff) Small Screen Adaptation (Max-width: 600px):

Change the background color to dark gray (#333) Change the text color to light gray (#f4f4f4) Change the link color to light green (#28a745)

Dark Mode Preference:

If the user has set their device to dark mode, override the above styles with the following: Background color: Black (#000) Text color: White (#fff) Link color: Cyan (#17a2b8)
# Steps:

## Step1:
Meet the requirements for the default mode or light mode
## Step2:
Choose a device which is smaller in size of mobilephone of 600px and meet the prefered requirements
## Step3:
Meet the requirements for the prefered darker mode

# Code:
media.html:
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="pj.css">
</head>
<body>
    <a href="https://github.com/Jeshwanthkumarpayyavula/ODD2023-WT-Ex-07-CSS.git"></a>
    <p>
      <legend align="center"><big><b>This is My Web Page</b></big>
    </p>
     
  <p align="center">Hi This Is Jeshwanth Kumar from the dept of Aiml</p>
</fieldset>
</body>
<hr>
<footer>~Created By @P.Jeshwanth Kumar</footer>
</html>
```
pj.css:
```
p {
    font-size: 100px;
    color: #333;
    background-color: #f4f4f4;
    a {
        color: #007bff;
    }
}
@media (max-width: 600px) {
    p {
        font-size: 100px;
        background-color: #333;
        color: #f4f4f4;
        a {
            color: #28a745;
        }
        
    }
}
@media (prefers-color-scheme: dark) 
{ 
p { 
    font-size: 100px;
    background: #333; 
    color: white; 
    a {
        color: #17a2b8;
    }


} }
footer {
    font-size: x-large;
}
```




# Output:
light mode:

![image](https://github.com/Jeshwanthkumarpayyavula/ODD2023-WT-Ex-07-CSS/assets/145742402/acb65074-b6f5-4761-84af-c1e9069af9e9)


Dark mode:

![image](https://github.com/Jeshwanthkumarpayyavula/ODD2023-WT-Ex-07-CSS/assets/145742402/228f998a-9c01-49a1-9dd8-07a584378391)

Smaller screen:

![WhatsApp Image 2023-12-01 at 20 35 37_c492c632](https://github.com/Jeshwanthkumarpayyavula/ODD2023-WT-Ex-07-CSS/assets/145742402/7dada9ac-1b43-4e71-b705-977f9948dcd9)

