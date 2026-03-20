# Ex08 Event Registration Web Application
## Date:

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
home page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="HOME-PAGE">
      <img class="logo" src="img/logo-1.png" />
      <img class="screenshot" src="img/screenshot-2026-03-20-125219-1.png" />
      <img class="img" src="img/screenshot-2026-03-20-131135-1.png" />
      <div class="text-wrapper">SPORTS DAY EVENT</div>
      <div class="rectangle"></div>
      <div class="LOGIN">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LOGIN</div>
      <div class="div"></div>
      <div class="REGISTER">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; REGISTER</div>
    </div>
  </body>
</html>

.HOME-PAGE {
  background-color: #ffffff;
  width: 100%;
  min-width: 609px;
  min-height: 1323px;
  position: relative;
}

.HOME-PAGE .logo {
  position: absolute;
  top: 13px;
  left: 14px;
  width: 595px;
  height: 90px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.HOME-PAGE .screenshot {
  position: absolute;
  top: 103px;
  left: 0;
  width: 609px;
  height: 1208px;
  aspect-ratio: 0.51;
  object-fit: cover;
}

.HOME-PAGE .img {
  position: absolute;
  top: 234px;
  left: 120px;
  width: 370px;
  height: 376px;
  aspect-ratio: 0.98;
  object-fit: cover;
}

.HOME-PAGE .text-wrapper {
  position: absolute;
  top: 619px;
  left: 65px;
  width: 515px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.HOME-PAGE .rectangle {
  position: absolute;
  top: 694px;
  left: 76px;
  width: 453px;
  height: 89px;
  background-color: #f51313;
}

.HOME-PAGE .LOGIN {
  position: absolute;
  top: 713px;
  left: 100px;
  width: 390px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.HOME-PAGE .div {
  position: absolute;
  top: 839px;
  left: 102px;
  width: 427px;
  height: 90px;
  background-color: #f14646;
}

.HOME-PAGE .REGISTER {
  position: absolute;
  top: 879px;
  left: 132px;
  width: 369px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

event page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="EVENT-PAGE">
      <img class="screenshot" src="img/screenshot-2026-03-20-125134-2.png" />
      <p class="sports-day-event">
        <span class="text-wrapper">&nbsp;&nbsp;&nbsp;&nbsp; </span>
        <span class="span"
          >sports&nbsp;&nbsp;day event<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Circket<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.Badminton<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.Volley
          Ball<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.100 MTS<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5.200
          MTS<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6.400MTS<br /><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7.4*100
          Relay</span
        >
      </p>
    </div>
  </body>
</html>

.EVENT-PAGE {
  background-color: #ffffff;
  width: 100%;
  min-width: 581px;
  min-height: 1222px;
  position: relative;
}

.EVENT-PAGE .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 581px;
  height: 1222px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.EVENT-PAGE .sports-day-event {
  position: absolute;
  top: 188px;
  left: 77px;
  width: 355px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-PAGE .text-wrapper {
  font-weight: 500;
}

.EVENT-PAGE .span {
  font-family: "Jaini-Regular", Helvetica;
  font-size: 24px;
}

event registration

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="EVENT-REGISTRATION">
      <img class="screenshot" src="img/screenshot-2026-03-20-125134-3.png" />
      <p class="div">
        <span class="text-wrapper">&nbsp;&nbsp;</span>
        <span class="span">EVENT REGISTRATION FORM<br />FILL THE DETAILS</span>
      </p>
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="rectangle-8"></div>
      <div class="rectangle-9"></div>
      <div class="REGISTER">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; REGISTER</div>
      <div class="text-wrapper-2">Event to register</div>
      <div class="text-wrapper-3">Phone Number</div>
      <div class="text-wrapper-4">Department</div>
      <div class="text-wrapper-5">Register Number</div>
      <div class="text-wrapper-6">Age</div>
      <div class="text-wrapper-7">Gender</div>
      <div class="text-wrapper-8">Full Name</div>
      <div class="text-wrapper-9">Email id</div>
    </div>
  </body>
</html>

.EVENT-REGISTRATION {
  background-color: #ffffff;
  width: 100%;
  min-width: 547px;
  min-height: 1223px;
  position: relative;
}

.EVENT-REGISTRATION .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 547px;
  height: 1197px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.EVENT-REGISTRATION .div {
  position: absolute;
  top: 49px;
  left: 7px;
  width: 531px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-REGISTRATION .text-wrapper {
  font-weight: 500;
}

.EVENT-REGISTRATION .span {
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
}

.EVENT-REGISTRATION .rectangle {
  position: absolute;
  top: 226px;
  left: 30px;
  width: 316px;
  height: 45px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-2 {
  position: absolute;
  top: 305px;
  left: 41px;
  width: 290px;
  height: 41px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-3 {
  position: absolute;
  top: 377px;
  left: 41px;
  width: 305px;
  height: 54px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-4 {
  position: absolute;
  top: 454px;
  left: 49px;
  width: 270px;
  height: 51px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-5 {
  position: absolute;
  top: 533px;
  left: 53px;
  width: 293px;
  height: 53px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-6 {
  position: absolute;
  top: 612px;
  left: 55px;
  width: 309px;
  height: 55px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-7 {
  position: absolute;
  top: 690px;
  left: 59px;
  width: 305px;
  height: 51px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-8 {
  position: absolute;
  top: 763px;
  left: 67px;
  width: 319px;
  height: 57px;
  background-color: #d9d9d9;
}

.EVENT-REGISTRATION .rectangle-9 {
  position: absolute;
  top: 989px;
  left: 132px;
  width: 254px;
  height: 61px;
  background-color: #54eafb;
}

.EVENT-REGISTRATION .REGISTER {
  position: absolute;
  top: 1011px;
  left: 152px;
  width: 212px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-REGISTRATION .text-wrapper-2 {
  position: absolute;
  top: 785px;
  left: 144px;
  width: 187px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.EVENT-REGISTRATION .text-wrapper-3 {
  position: absolute;
  top: 700px;
  left: 68px;
  width: 221px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-REGISTRATION .text-wrapper-4 {
  position: absolute;
  top: 621px;
  left: 61px;
  width: 223px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-REGISTRATION .text-wrapper-5 {
  position: absolute;
  top: 541px;
  left: 58px;
  width: 216px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-REGISTRATION .text-wrapper-6 {
  position: absolute;
  top: 460px;
  left: 56px;
  width: 191px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-REGISTRATION .text-wrapper-7 {
  position: absolute;
  top: 387px;
  left: 51px;
  width: 168px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.EVENT-REGISTRATION .text-wrapper-8 {
  position: absolute;
  top: 314px;
  left: 46px;
  width: 177px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.EVENT-REGISTRATION .text-wrapper-9 {
  position: absolute;
  top: 233px;
  left: 39px;
  width: 226px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

contact page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="CONTACT-PAGE">
      <img class="screenshot" src="img/screenshot-2026-03-20-125154-1.png" />
      <p class="WE-ARE-ALL-EAGERLY">
        WE ARE ALL EAGERLY WAITING <br />
        FOR YOUR PARTICIPATION IN<br />&nbsp;&nbsp; THE SPORTS EVENTS
      </p>
      <img class="logo" src="img/logo-2.png" />
      <div class="THANK-YOU">THANK&nbsp;&nbsp;YOU</div>
      <div class="text-wrapper">CONTACT US</div>
      <div class="div">Saveetha college@gamil.com</div>
      <div class="text-wrapper-2">Contact No: 9896194395</div>
    </div>
  </body>
</html>

.CONTACT-PAGE {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 514.17px;
  min-height: 1170.96px;
  position: relative;
}

.CONTACT-PAGE .screenshot {
  position: absolute;
  top: -1px;
  left: -1px;
  width: 514px;
  height: 1171px;
  transform: rotate(0.14deg);
  aspect-ratio: 0.44;
}

.CONTACT-PAGE .WE-ARE-ALL-EAGERLY {
  position: absolute;
  top: 432px;
  left: 120px;
  transform: rotate(0.14deg);
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.CONTACT-PAGE .logo {
  position: absolute;
  top: -1px;
  left: 0;
  width: 514px;
  height: 81px;
  transform: rotate(0.14deg);
  aspect-ratio: 6.65;
  object-fit: cover;
}

.CONTACT-PAGE .THANK-YOU {
  position: absolute;
  top: 348px;
  left: 155px;
  transform: rotate(0.14deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.CONTACT-PAGE .text-wrapper {
  position: absolute;
  top: 585px;
  left: 120px;
  transform: rotate(0.14deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.CONTACT-PAGE .div {
  position: absolute;
  top: 660px;
  left: 11px;
  width: 501px;
  transform: rotate(0.14deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.CONTACT-PAGE .text-wrapper-2 {
  position: absolute;
  top: 749px;
  left: 22px;
  width: 405px;
  transform: rotate(0.14deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:
![alt text](<Screenshot 2026-03-20 142002.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
