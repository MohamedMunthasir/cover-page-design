# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:

## Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .bookpage {
            width: 400px;
            height: 650px;
            background-image: url("romeo.jpeg");
            background-repeat: no-repeat;
            background-size: cover;
            color: white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }
        .fade-overlay {
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
        }

        .toptext {
            color: white;
        }

        .tophr {
            width: 140px;
            color: rgb(233, 223, 223);
        }

        .author {
            color: rgb(203, 23, 23);
            display: inline;
            position: relative;
            top: 150px;
            font-family: Helvetica, Arial, sans-serif;
            font-size: medium;
        }

        .booktitle {
            font-family: Helvetica, Arial, sans-serif;
            font-size: 20px;
            text-align: center;
            position: relative;
            top: 20px;
        }

        .id {
            width: 400px;
            position: relative;
            top: 190px;
        }

        .publisher {
            font-size: medium;
            position: relative;
            top: 120px;
            left: 330px;
        }

        .edition {
            color: rgb(242, 234, 234);
            font-size: 15px;
            font-family: Verdana;
            position: relative;
            text-align: left;

            top: 25px;
        }

        .subtitle {
            color: hsl(240, 47%, 97%);
            font-family: 'Montserrat',sans-serif;
            font-size: 20px;
            font-weight: bold;
            text-align: center;
            margin-top: 110px;
        }

        .photo {
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }

    </style>
    <title>Book Cover Page</title>
</head>
<body>
    <div class="bookpage">
        <div class="fade-overlay"></div>
        <div class="toptext">
            EXPERT INSIGHT
        </div>
        <div class="tophr">
            <hr style="color: red;">
        </div>
        <div class="booktitle">
            <h1>RESPONSIVE WEB DESIGN WITH HTML5 AND CSS</h1>
        </div>
        <div class="subtitle">
            DEVELOP FUTURE-PROOF RESPONSIVE WEBSITES USING THE LATEST HTML5 AND CSS TECHNIQUES
        </div>
        <div class="photo">
            <img src="WhatsApp Image 2023-05-19 at 9.58.54 PM.jpeg" width="100" height="100" alt="Author Photo">
        </div>
        
        <div class="author">
            <p><b>THIRD EDITION</b></p>
        </div>
        <div class="publisher">
            PACKT>
        </div>
        <div class="edition">
            <b>MOHAMED MUNTHEASIR Y</b>
        </div>
    </div>
</body>
</html>
```
## Output:
![image](https://github.com/MohamedMunthasir/cover-page-design/assets/121957086/c35bc215-14b3-4cc9-bf15-e5701f052083)

![image](https://github.com/MohamedMunthasir/cover-page-design/assets/121957086/54b5ddd5-e158-4399-b8b1-320e2ef9041e)

## Result:
The program for designing book front cover page using HTML and CSS is completed successfully.
