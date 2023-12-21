# Ex-06-Book-Cover-Design

# AIM : 
To Design a Book cover page using HTML and CSS.

# Requirements :
Code editors like visual studio code or notepad to run the html and css code.

# Step 1:
## Create a New HTML File:

Open your favorite text editor or an integrated development environment (IDE).

Create a new file and save it with a .html extension, for example, index.html.
# Step 2:
## HTML Structure:
Set up the basic HTML structure.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Book cover page</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
</head>
<body>
    <!-- Content goes here -->
</body>
</html>

```
# Step 3:
## Add CSS Styling:

Create a new CSS file, for example, styles.css.
Link the CSS file to your HTML.
# Step 4:
## CSS Styling:

Copy and paste the CSS styles you've provided into your styles.css file.
Adjust styles as needed.
# Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Book cover page</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
        <style>
            body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    margin:auto;
    position: relative;
    background-image: url(https://img.freepik.com/free-photo/ai-nuclear-energy-background-future-innovation-disruptive-technology_53876-129783.jpg?size=626&ext=jpg);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: bottom 0px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: xx-large;
    font-weight:bold;
    color: #f47027;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 10px;
    border-top:2px solid #f47027;
    padding-top:0px;
    width:726px;
    font-family:Georgia, 'Times New Roman', Times, serif;
}
.photo{
            position: relative;
            top: 190px;
            left: 550px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition</h3>  
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>A.Hari Veera Prasad</span>
                    <span id="end"><u>AIML></u></span>
                </div>
            </footer>
            <div class="photo">
                <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\ABA3B6FD5D186D28E06FF97135CADE7F\WhatsApp Image 2023-12-21 at 20.59.15_f7fe1d67.jpg" width="130" height="150"alt="">
            </div>  
    </section>
    </body>
</html>
```
# Step 5:
Run the html and css code in any code editor.
# Output:
![image](https://github.com/Hariveeraprasad-2006/Ex-06-Book-Cover-Design/assets/145049988/d0113c44-573f-4177-8821-2e948232ece1)

# Result :
Therefore, successfully created a Book Cover Page Design using HTML and CSS.
## Developed By : Arikatla Hari Veera Prasad
## Register Number : 212223240014
