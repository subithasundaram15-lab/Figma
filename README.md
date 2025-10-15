# Ex09 Event Registration Web Application
## Date:15.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="logo" src="img/logo-1.png" />
      <img class="download" src="img/download-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER</div>
    </div>
  </body>
</html>

.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 307px;
  min-height: 588px;
  position: relative;
}

.frame .logo {
  position: absolute;
  top: 43px;
  left: 14px;
  width: 270px;
  height: 71px;
  aspect-ratio: 3.79;
  object-fit: cover;
}

.frame .download {
  position: absolute;
  top: 139px;
  left: 68px;
  width: 173px;
  height: 173px;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .rectangle {
  position: absolute;
  top: 459px;
  left: 70px;
  width: 179px;
  height: 52px;
  background-color: #24f4e9;
}

.frame .text-wrapper {
  position: absolute;
  top: 473px;
  left: 101px;
  width: 129px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="diwali" src="img/diwali-1.png" />
      <p class="GET-READY-FOR-THE">GET READY FOR <br />THE CELEBRATION</p>
      <div class="DIWALI-MODE-ON">DIWALI <br />MODE ON</div>
      <div class="date-time">date:10.10.2025<br />time:4.00pm<br />venue: sec entrance</div>
    </div>
  </body>
</html>

.frame {
  background-color: #3253f9;
  width: 100%;
  min-width: 318px;
  min-height: 588px;
  position: relative;
}

.frame .diwali {
  position: absolute;
  top: 0;
  left: 0;
  width: 318px;
  height: 588px;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .GET-READY-FOR-THE {
  position: absolute;
  top: 162px;
  left: 17px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #35add5;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .DIWALI-MODE-ON {
  position: absolute;
  top: 286px;
  left: 62px;
  width: 217px;
  font-family: "Inter-MediumItalic", Helvetica;
  font-weight: 500;
  font-style: italic;
  color: #f3f727;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .date-time {
  position: absolute;
  top: 447px;
  left: 62px;
  width: 233px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #7edcdc;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="text-wrapper">THANK YOU</div>
      <p class="fun-is-waiting-wish">
        Fun is waiting!<br /><br /><br /><br /><br />Wish you all HAPPY AND SAFE&nbsp;&nbsp;DIWALI
      </p>
    </div>
  </body>
</html>

.frame {
  background-color: #24f4e9;
  width: 100%;
  min-width: 328px;
  min-height: 569px;
  display: flex;
  flex-direction: column;
  gap: 47px;
}

.frame .text-wrapper {
  margin-left: 89px;
  width: 212px;
  height: 75px;
  margin-top: 53px;
  font-family: "Inter-MediumItalic", Helvetica;
  font-weight: 500;
  font-style: italic;
  color: #e8de24;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .fun-is-waiting-wish {
  margin-left: 37px;
  width: 264px;
  height: 101px;
  font-family: "Inter-MediumItalic", Helvetica;
  font-weight: 500;
  font-style: italic;
  color: #d02222;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
```

## OUTPUT
![alt text](<Screenshot (23).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
