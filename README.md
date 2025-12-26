# Ex08 Event Registration Web Application
## Date:26-12-2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

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
    <div class="iphone-pro-max">
      <div class="rectangle"></div>
      <div class="text-wrapper">DRESTIEN 2025</div>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <img class="logos" src="img/id8rbwvi7l-logos-1.png" />
      <img class="idwahcuod-logos" src="img/idwahcuod7-logos-1.png" />
      <img class="drestein-logo" src="img/drestein-logo-1.png" />
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  top: 363px;
  left: 52px;
  width: 337px;
  height: 62px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 381px;
  left: 104px;
  width: 290px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 30px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  top: 511px;
  left: 105px;
  width: 230px;
  height: 49px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 517px;
  left: 145px;
  width: 231px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 30px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .logos {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 88px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone-pro-max .idwahcuod-logos {
  position: absolute;
  top: 153px;
  left: 148px;
  width: 145px;
  height: 145px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-pro-max .drestein-logo {
  position: absolute;
  top: 593px;
  left: 52px;
  width: 330px;
  height: 329px;
  aspect-ratio: 1;
  object-fit: cover;
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
    <div class="iphone-pro-max">
      <img class="drestein" src="img/drestein25-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">DRESTEIN EVENT HIGHLIGHTS</div>
      <div class="div"></div>
      <div class="text-wrapper-2">PIXEL PLAY</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">INNOVOLT</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">TREASURE HUNT</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">AI ADZAP</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-6">MIND X ML</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .drestein {
  position: absolute;
  top: 51px;
  left: 0;
  width: 440px;
  height: 905px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  top: 0;
  left: 0;
  width: 440px;
  height: 51px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 11px;
  left: 0;
  width: 440px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 29px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  top: 144px;
  left: 27px;
  width: 223px;
  height: 32px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 145px;
  left: 36px;
  width: 329px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  top: 225px;
  left: 30px;
  width: 220px;
  height: 33px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 227px;
  left: 35px;
  width: 161px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  top: 300px;
  left: 30px;
  width: 214px;
  height: 34px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 301px;
  left: 33px;
  width: 220px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-4 {
  top: 381px;
  left: 30px;
  width: 211px;
  height: 32px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 383px;
  left: 35px;
  width: 211px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-5 {
  top: 458px;
  left: 30px;
  width: 207px;
  height: 30px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 460px;
  left: 36px;
  width: 187px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
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
    <div class="iphone-pro-max">
      <img class="element" src="img/36497171-registration-text-concept-on-green-digital-world-map-background-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTRATION FORM</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-2">NAME:</div>
      <div class="text-wrapper-3">REGISTER NO:</div>
      <div class="text-wrapper-4">DEPARTMENT:</div>
      <div class="text-wrapper-5">YEAR OF STUDY:</div>
      <div class="text-wrapper-6">EVENT REGISTERED:</div>
      <div class="text-wrapper-7">PHONE NUMBER:</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .element {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 1.29;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 47px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 10px;
  left: 58px;
  width: 440px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 29px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  top: 120px;
  height: 35px;
  position: absolute;
  left: 0;
  width: 207px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-2 {
  top: 195px;
  height: 38px;
  position: absolute;
  left: 0;
  width: 207px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-3 {
  top: 274px;
  height: 36px;
  position: absolute;
  left: 0;
  width: 207px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-4 {
  top: 349px;
  height: 33px;
  position: absolute;
  left: 0;
  width: 207px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-5 {
  top: 427px;
  height: 35px;
  position: absolute;
  left: 0;
  width: 207px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-6 {
  top: 502px;
  height: 34px;
  position: absolute;
  left: 0;
  width: 207px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 124px;
  left: 2px;
  width: 210px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 201px;
  left: 2px;
  width: 202px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 278px;
  left: 2px;
  width: 201px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 355px;
  left: 0;
  width: 220px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 430px;
  left: 2px;
  width: 207px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 506px;
  left: 2px;
  width: 185px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}


```

## OUTPUT:
![alt text](<Screenshot (76).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
