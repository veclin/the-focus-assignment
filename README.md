# The Focus Assignment
This assignment is designed to get you to produce a large project over a long period of time using everything you learn in this course. You’ll apply semantic HTML to content; employ CSS to style a design comp, and use a grid to translate the comp to a working web page.

Before reading any further, take a moment to inspect all the files and folders in this project.

## Description
You will create a transfer of [this Photoshop PSD](comps/focus.psd), created by Michael Reimer at [`bestpsdfreebies.com`](http://www.bestpsdfreebies.com/), into a web page. (The original is found [here](http://www.bestpsdfreebies.com/freebie/focus-psd-theme/).) A responsive version is not required; only replicate the PSD file at the native dimensions of `1600 × 2494`. The starter CSS, fonts, and assets you’ll need are discussed below.

## Grid
You will need [this Chrome extension](https://github.com/code-warrior/the-modular-grid) in order to transfer the page accurately using a web grid.

## Assets
All the images you’ll need are in the `img` folder and all the fonts you’ll need are in the `fonts` folder. You’ll want to use `comps/focus.jpg` as a background in your page to make sure you’re keeping true to the original design, and you’ll need `comps/focus.psd` to extract data related to colors, font sizes, leading, etc.

## Reset CSS
Eric Meyer’s reset CSS (`reset.css`) is provided in the `css` folder and included at the top of the style sheet stack in `index.html`.

## Fonts
The PSD comp `focus.psd` uses three typefaces: [Pacifico](https://fonts.google.com/specimen/Pacifico), [Raleway](https://fonts.google.com/specimen/Raleway), and Helvetica Neue. (Download these fonts to your machine.) The web versions of the regular weight of Pacifico and the regular, light, and semibold versions of Raleway are included in the `fonts` directory. (These have `.woff2` extensions.)

Helvetica Neue, however, isn’t included, since it’s not open. Try employing Helvetica Neue in the `font-family` property and fall back to Helvetica.

The path to each font is listed below.

**Pacifico Regular**: `fonts/Q_Z9mv4hySLTMoMjnk_rCXYhjbSpvc47ee6xR_80Hnw.woff2`  
**Raleway Regular**: `fonts/QAUlVt1jXOgQavlW5wEfxQLUuEpTyoUstqEm5AMlJo4.woff2`  
**Raleway Light**: `fonts/-_Ctzj9b56b8RgXW8FAriQzyDMXhdD8sAj6OAJTFsBI.woff2`  
**Raleway SemiBold**: `fonts/xkvoNo9fC8O2RDydKj12bwzyDMXhdD8sAj6OAJTFsBI.woff2`  

## Instructions
* Put your first and last names in the `title` element of the `index.html` file.
* All your work **must** go in `index.html` and `style.css`.
* **Do not** edit/alter/remove **any** of the files in the scaffold of this project, including images.
* **Do not add** any files to this project; everything you need for this project is included in the scaffold.
* **Do not** replace this folder with another folder of the same name, as that will remove the `.gitignore` files.
* Use the hash sign (`#`) as the value to the `href` attribute in all anchors.

## Due
This assignment is due by 11:59 PM on Sunday, 9 December 2018.

## Submission
1. Log into GitHub.
2. Fork this repo.
3. Clone your fork.
4. Checkout your personal branch.
5. Generate all the commits required for your project.
6. Issue a pull request back to the source repo. Make sure the `base` and `compare` branches are yours. See [these videos](http://code-warrior.github.io/tutorials/git/github/) for help, noting the “Issuing Pull Requests” section.

Only the following files should appear as “changed” in your pull request.
1. `index.html`
2. `css/style.css`

## Grading
| Item                                 | Points |
|--------------------------------------|:------:|
| **Correct color scheme implemented** | `10`   |
| **Images laid out correctly**        | `10`   |
| **Web fonts implemented**            | `10`   |
| **Abides to design comp**            | `20`   |
| **Valid W3C HTML, per validator**    | `15`   |
| **Valid W3C CSS, per validator**     | `15`   |
| **Prohibited files altered**         | `20`   |
