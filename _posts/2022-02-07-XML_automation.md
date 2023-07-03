---
layout: post
title: add posting automation
tags: automation python pandas selenium marketing adds

---
automatic Add poster

##### problem

in my 3d printing business i had to post multiple adds for all my products online
doing this manually would take a lot of time, and i could  do manual mistakes

##### solution

find a way to atumatically post the adds with a program

##### idea

i can store all my data in a file (in this case i chose excel to take advantage of the grid properties and structure )
with python i can read the file , store the info in a add_object and make an list of add_objects
now with the list of objects i can load the information to the web with selenium

##### requierments 

* download the latest chrome browser => https://chromedriver.chromium.org/downloads
* download the project from my github => github_link
* download the requierments for the project




github =>

To enable typography plugin, inter font, and customizations by updating `tailwid.config.js` as follows:

```js
const defaultTheme = require('tailwindcss/defaultTheme')

module.exports = {
  content: [
    './**/*.html'
  ],
  darkMode: 'media',
  theme: {
    extend: {
      typography: {
        DEFAULT: {
          css: {
            pre: {
              padding: "0",
              color: "#1F2933",
              backgroundColor: "#F3F3F3"
            },
            code: {
              padding: "0.2em 0.4em",
              backgroundColor: "#F3F3F3",
              color: "#DD1144",
              fontWeight: "400",
              "border-radius": "0.25rem"
            },
            "code::before": false,
            "code::after": false,
            "blockquote p:first-of-type::before": false,
            "blockquote p:last-of-type::after": false,
          },
        },
      },
      fontFamily: {
        sans: ['Inter var', ...defaultTheme.fontFamily.sans],
      },
    },
  },

  variants: {
    extend: {},
  },
  plugins: [
    require('@tailwindcss/typography'),
  ],

}
```

See more examples at [here](https://harrywang.me/2022/01/18/tailpages-tutorial-technical.html)
