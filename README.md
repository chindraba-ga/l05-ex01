# l05-ex01

-  Status: Pending
-  Live page: <https://www.chindraba.work/fewd/l05-ex01.html>

## Contents

-  [Description](#description)
-  [Copyright and License](#copyright-and-license)
   -  [The MIT License](#the-mit-license)

---
## Description

### Lesson 5: Solo Exercise: Make a Grid With Images

Make a 3 column grid out of these - try to get these images to fit their div containers.

The starter code is:

#### HTML

    <!doctype html>
    <html>
    <head>
      <title>Grid and Flexbox</title>
      <link href="https://fonts.googleapis.com/css?family=Open+Sans|Oswald" rel="stylesheet">
    </head>

    <body>
      <header class="intro">
        <p class="heading">Make a 3 column grid out of these - try to get these images to fit their div containers.</p>
      </header>
      <main class="grid-city">
        <div>
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-1.JPG">
        </div>
        <div>
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-2.JPG">
        </div>
        <div>  
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-3.JPG">
        </div>
        <div>
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-4.JPG">
        </div>
        <div>
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-5.JPG">
        </div>
        <div>
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-6.JPG">
        </div>
        <div>
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-7.JPG">
        </div>
        <div>  
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-8.JPG">
        </div>
        <div>  
          <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/2522641/dv-9.JPG">
        </div>
      </main>

      <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
      <script src="js/main.js"></script>
    </body>
    </html>

#### CSS

    body {
      background-repeat: no-repeat;
      color: black;
      margin: 0;
      padding: 35px 70px 200px 70px;
    }

    /* offset page header height by height of the top header*/
    h1 {
      padding-top: 100px;
    }

    h2 {
      padding-top: 80px;
    }

    div {
      padding-bottom: 30px;
    }

    .code {
      font-family: courier;
    }

    .intro {
      color: black;
      margin-top: 25px;
    }

    .heading {
      font-family: 'Oswald', sans-serif;
      font-size: 36px;
    }

    /*
      ##################################
      ######## Container Styles ########
      ##################################

      Note the 3 levels of nesting in the HTML
      <main>
        <div>
          <img src="">
        </div>
      </main>

      CSS Grid controls children but what about the third level images?
      How do you make the images responsive?
      Check the solution to see the result but give this a good effort before doing so if you can.
    */

[TOP](#contents)

---
## Copyright and License

Copyright © 2020  Chindraba (Ronald Lamoreaux)

<[upskill@chindraba.work](mailto:upskill@chindraba.work?subject='l05-ex01')>

— All Rights Reserved

### The MIT License
    
    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the "Software"),
    to deal in the Software without restriction, including without limitation
    the rights to use, copy, modify, merge, publish, distribute, sublicense,
    and/or sell copies of the Software, and to permit persons to whom the
    Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included
    in all copies or substantial portions of the Software

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGE MENT. IN NO EVENT SHALL
    THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
    DEALINGS IN THE SOFTWARE.

[TOP](#contents)
