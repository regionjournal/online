# regionjournal `html components`

The goal of this document is to serve as a workspace and dynamic library of `html components` that can be stored, updated, and reused for future website maintenance.

## Wishlist
* Shop button
* Spotify music button
* Bottom right region button
  * Becoming a member button
    * region assistant button
      * Chat bot
* Blog button

---

## Header Systems

### Example 1

```html
<head>
    <title>Restaurant HAYQ</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="author" content="Aurimas Ransys">
    <meta name="keywords" content="Armenian Food, Food">
    <meta name="description" content="Armenian Food Business">
    <link href="https://fonts.googleapis.com/css?family=Cabin" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Bungee" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Great+Vibes|Permanent+Marker" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Gloria+Hallelujah|Indie+Flower" rel="stylesheet">
</head>
```

## Icons

```html
        <div class="row mx-0 white-txt">
            
            <!-- Brand logo -->
            <div class="col container">
                <div class="footer-font">
                    region
                </div>
            </div>
            
            <!-- Bottom mantra -->
            <div class="col-10 container text-center">
                <div class="text-muted footer-font">
                    for the people that exist between borders with family on both sides
                </div>
            </div>

            <div class="col container">
                <div class="footer-font">
                    <a href="#" class="fa fa-facebook"></a>
                    <a href="#" class="fa fa-facebook"></a>
                    <a href="#" class="fa fa-facebook"></a>
                </div>
            </div>

        </div>
```

```html
<div class="container text-left">
    <a href="#" class="fa fa-facebook"></a>
</div>

<div class="container text-center">
    <span class="text-muted footer-font">for the people that exist between borders with family on both sides</span>
</div>

<div class="container text-right">
    <a href="#" class="fa fa-facebook"></a>
```

## Navbar Systems

### Multiple unordered list_1:

```html
<!-- Navbar -->
<nav class="navbar navbar-light bg-light main-nav" role="navigation" align="center">
    <div class="container">
        
        <!-- Navbar item: brand logo -->
        <ul class="nav navbar-nav">
            <li class="nav-item active">
                <a href="#" class="navbar-brand">
                    region.
                </a>
            </li>
        </ul>

        <!-- Navbar item: brand mantra -->
        <ul class="nav navbar-nav ul_center_nav">
            <li class="nav-item">
                <a class="nav-link" href="#">
                    building better maps
                </a>
            </li>
        </ul>

        <!-- Navbar item: brand information -->
        <ul class="nav navbar-nav">
            <li class="nav-item">
                <a class="nav-link" href="#">
                    about.
                </a>
            </li>
        </ul>
    </div>
</nav>
```

```html
<!-- Navbar -->
<nav class="navbar navbar-expand-md navbar-fixed-top navbar-light bg-light main-nav" role="navigation" align="center">
    <div class="container">
        
        <!-- Navbar item: brand logo -->
        <ul class="nav navbar-nav">
            <li class="nav-item active">
                <a href="#" class="navbar-brand">
                    region.
                </a>
            </li>
        </ul>

        <!-- Navbar item: brand mantra -->
        <ul class="nav navbar-nav mx-auto">
            <li class="nav-item">
                <a class="nav-link" href="#">
                    building better maps...
                </a>
            </li>
        </ul>

        <!-- Navbar item: brand information -->
        <ul class="nav navbar-nav">
            <li class="nav-item">
                <a class="nav-link" href="#">
                    about.
                </a>
            </li>
        </ul>
    </div>
</nav>
```

---

## Button Systems

### The two buttons

```html
<!-- Buttons -->
<div class="div_center"> 
    <ul class="ul_buttons">

        <!-- Button: page 1 -->
        <li class="li_buttons">
            <a href="https://storage.googleapis.com/blessa/region/RegionJournalFinal.pdf" class="button_region">
                <h3>
                    <mark>issue 01.</mark>
                </h3>
            </a>
        </li>
        
        <!-- Button: page 2 -->
        <li class="li_buttons">
            <a href="https://storage.googleapis.com/blessa/region/cube%20map%20png.png" class="button_region">
                <h3>
                    <mark>issue 02.</mark>
                </h3>
            </a>
        </li>
    </ul>
</div>
```

### The two button system with signature

```html
<!-- Buttons -->
<div class="center"> 
    <table class="table_buttons">
        
        <!-- Button: page 1 -->
        <tr>
            <th>
                <a href="https://storage.googleapis.com/blessa/region/RegionJournalFinal.pdf" class="button_region">
                    <h3>
                        <mark>issue 01.</mark>
                    </h3>
                </a>
            </th>
        </tr>

        <!-- Button: page 2 -->
        <tr>
            <th>
                <a href="https://storage.googleapis.com/blessa/region/cube%20map%20png.png" class="button_region">
                    <h3>
                        <mark>issue 02.</mark>
                    </h3>
                </a>
            </th>
        </tr>

        <!-- Signature -->
        <tr>
            <th>
                made by |&nbsp;<a href="https://regionjournal.github.io/online/">regionjournalcrew✨</a>
            </th>
        </tr>
    </table>
</div>
```

### The four buttons

```html
<!-- Button 1 -->
<div class="center">
    <table>
        <tr>
            <th>
                <!-- A single button to rule the world -->
                <a href="https://light-systems.github.io/REGION-DIGITAL/" class="button_region">
                    <h3>
                        <mark>notes.</mark>
                    </h3>
                </a>
            </th>
        </tr>
    </table>
</div>

<!-- Touch break -->
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<!-- Button 2 -->
<div class="center">
    <table>
        <tr>
            <th>
                <!-- A single button to rule the world -->
                <a href="https://storage.googleapis.com/blessa/region/RegionJournalFinal.pdf" class="button_region">
                    <h3>
                        <mark>issue 01.</mark>
                    </h3>
                </a>
            </th>
        </tr>
    </table>
</div>

<!-- Touch break -->
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<!-- Button 3 -->
<div class="center">
    <table>
        <tr>
            <th>
                <a href="https://storage.googleapis.com/blessa/region/cube%20map%20png.png" class="button_region">
                    <h3>
                        <mark>issue 02.</mark>
                    </h3>
                </a>
            </th>
        </tr>
    </table>
</div>

<!-- Touch break -->
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<!-- Button 4 -->
<div class="center">
    <table>
        <tr>
            <th>
                <!-- A single button to rule the world -->
                <a href="https://classroom.google.com/c/NDQ0OTgzMDEyOTFa" class="button_region">
                    <h3><mark>classroom.</mark></h3>
                </a>
            </th>
        </tr>
    </table>
</div>
```

## Signature Systems

```html
<!-- Signature -->
made by | <a href="https://regionjournal.github.io/online/">regionjournalcrew✨</a>
```

## Footer Systems

```html
<!-- Footer -->
<nav class="navbar navbar-expand-md navbar-fixed-top navbar-dark bg-dark main-nav" role="navigation" align="center">
    <div class="container">
        <ul class="nav navbar-nav">
            <li class="nav-item active">
                <a href="#" class="navbar-brand">region.</a>
            </li>
        </ul>
        <ul class="nav navbar-nav mx-auto">
            <li class="nav-item"><a class="nav-link" href="#">for the people that exist between borders with family on both sides. </a></li>
        </ul>
        <ul class="nav navbar-nav">
            <li class="nav-item">
                <div class="container">
                    <a href="https://www.facebook.com/regionjournal"><i id="social-em" class="fa fa-facebook-square fa-2x social"></i></a>
                    <a href="https://www.instagram.com/regionjournal/"><i id="social-em" class="fa fa-instagram fa-2x social"></i></a>
                </div>
            </li>
        </ul>
    </div>
</nav>
```
