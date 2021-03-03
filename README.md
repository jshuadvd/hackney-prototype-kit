# Hackney prototype kit

Use this kit to quickly create HTML prototypes of Hackney services.

It's been built to work with the new [Hackney Design System](https://design-system.hackney.gov.uk) and to need minimal knowledge of coding to get started.

If you're looking for an even simpler way to get started, you could experiment with [this CodePen](https://codepen.io/jhackett1/pen/xxRWWKv?editors=1000) instead.

## Get started

There are two ways to use the prototyping kit, depending on whether you want to download and install it on your computer.

### 1. Use CodeSandbox

**[Run it in CodeSandbox now](https://githubbox.com/LBHackney-IT/hackney-prototype-kit)**

Recommended for beginners.

After

### 2. Install it locally

Recommended for developers and technical people.

This is a simple starter to allow you to create HTML pages using the Hackney pattern library.

Steps:

1. Download this repository to your machine by Clicking the green "Clone or download" button at the top right of the screen and select "Download Zip".
1. Extract the zip file.
1. Open index.html in a text editor of your choice. I'd recommend [VS Code](https://code.visualstudio.com/).
1. Replace "<!-- Page title goes here -->" with the title of your page
1. In the body of the page you will find placeholder comments for different components such as: header, breadcrumbs etc. For each component in turn if you decide you want to include that component then go to [LBH Frontend](http://lbh-frontend.herokuapp.com/), and click on the component.
1. Copy the component HTML and paste into index.html, making any changes necessary ([see Copying HTML for more information](#copying-html)).
1. Paste your code into index.html and make any required changes ()
1. Repeat this for all components required on your page.
1. Add any headings and body text that your page needs, using the [LBH Frontend Typography Page](http://lbh-frontend.herokuapp.com/examples/typography) as a reference.
1. To create other pages, copy and paste index.html into a new file and save it as an html file.

## Copying HTML

Copying a component's HTML from the Pattern library can be achieved in a couple of ways:

1. Find an example on [LBH Frontend](http://lbh-frontend.herokuapp.com/) that does the same thing that you want to do and change the bits that need changing.

OR

2. Generate your own code using the "Create HTML" form at the bottom of each component page.

If there's an example that does most of what you do, but you just need to change the text, and you think you'd be comfortable identifying which text to change, then I'd recommend option 1.

If none of the examples are quite right or you're not confident knowing which bits of text you'd need to change then option 2 will be best.

## To-do list

2. Use npm to get the latest version
3. Re-write docs
4. Test tricky components like tabs and contacts
5. Add a codesandbox link so people can play around without installing anything to their computer
