# Candy grid system

## Quick start

* [Download the latest release](https://github.com/andreamariotti83/candy-grid-system/archive/v1.3.0.zip).
* Clone the repo: `git clone https://github.com/andreamariotti83/candy-grid-system.git`.
* Install with [Composer](https://getcomposer.org): `composer require candygs/candy-grid-system`.

### HTML:

To use the Grid, you need to include the file with Grid number **12**, **16** or **24** that you want to use in the section `<head>` of the page.

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/1.3.0/12-candygs.min.css">
```
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/1.3.0/16-candygs.min.css">
```
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/candy-grid-system/1.3.0/24-candygs.min.css">
```

Add the class to set up your default layout, whether fixed or responsive. You can choose the layout among **17 different options** and  setting up any up to 8 classes.

* **candygs** : this is necessary to set up the values of your layout and Grid, in order to use the Candy Grid System.

```html
<body class="candygs">
	<div class="..."></div>
</body>
```

First, decide whether the layout will be set to, **small** to high, or **medium** to high, responsive **mobile** mode;
* **mobile** : sets up a responsive layout of 0 to 100%.
* **small** : sets up a responsive layout  of 720px to 100% `min-width: 720px`
* **medium** : sets up a responsive layout of 960px to 100% `min-width: 960px`

```html
<body class="candygs mobile">
	<div class="..."></div>
</body>
```

Then, set up a container for the layout with class **candygs-container** and its variables; a *max-width*, by selecting one of 5 options
* **candygs-container** : Set up a *max-width* container for each resolution - 720px - 960px - 1200px - 1560px - 1920px
  * **candygs-container-xl** : Set up a *max-width* container that will be no larger than 1560px
  * **candygs-container-lg** : Set up a *max-width* container that will be no larger than 1200px
  * **candygs-container-md** : Set up a *max-width* container that will be no larger than 960px
  * **candygs-container-sm** : Set up a *max-width* container that will be no larger than 720px

```html
<body class="candygs mobile candygs-container">
	<div class="..."></div>
</body>
```

Now you can set up the Container and Grid, which operate in accordance with the chosen layout.

```html
<body class="candygs mobile candygs-container">
	<div class="container">
		<div class="grid-8">
			<div class="row">
				<div class="grid-6"></div>
				<div class="grid-6"></div>
			</div>
		</div>
		<div class="grid-4"></div>
	</div>
</body>
```

You can also choose different values, depending on the screen resolution.
* **grid-** : For all resolutions
* **grid-xs-** : Only for mobile `@media (max-width: 767px)`
* **grid-sm-** : `@media (min-width: 768px)`
* **grid-md-** : `@media (min-width: 992px)`
* **grid-lg-** : `@media (min-width: 1200px)`
* **grid-xl-** : `@media (min-width: 1560px)`
* **grid-xxl-** : `@media (min-width: 1920px)`

```html
<body class="candygs mobile candygs-container">
	<div class="container">
		<div class="grid-xs-8 grid-sm-8 grid-md-7 grid-lg-6 grid-xl-5 grid-xxl-4"></div>
		<div class="grid-xs-4 grid-sm-4 grid-md-5 grid-lg-6 grid-xl-7 grid-xxl-8"></div>
	</div>
</body>
```

In additon to the class **grid-**, you can select:

* **prefix-** 
* **suffix-**
* **push-**
* **pull-**

Depending on your needs, choose the same variables as the **grid-**.

### LESS:
Coming soon

```

```

### SASS:
Coming soon

```

```
### PSD:
[Download psd templates](https://github.com/andreamariotti83/candy-grid-system/releases/download/v1.2.0/candy-grid-system-psd.zip).

## Author

Created by Andrea Mariotti. See the official site for more info: http://candygridsystem.com

* https://github.com/andreamariotti83

## Copyright and license

Code and documentation copyright 2016 Andrea Mariotti 
Code released under [the MIT license](https://github.com/andreamariotti83/candy-grid-system/blob/master/LICENSE).

## Thanks
