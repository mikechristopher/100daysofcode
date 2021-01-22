---
layout: post
title: "Fun Friday - Day 13"
date: 2021-01-22
category-name: post
---

Over half way done on the ES6 modules on FCC today.  Getting in good stead and understanding some of the fundimentals of it all.  Still getting stuck on some loops however but liking some of the shorthand (desctructuring assignments) that ES6 brings in comparison to writing out all of the functions.

For example - when learning about dot or bracket notations - this below certainly seems easier to read

```javascript
const LOCAL_FORECAST = {
  yesterday: { low: 61, high: 75 },
  today: { low: 64, high: 77 },
  tomorrow: { low: 68, high: 80 }
};
//writes the today figures from low and high in the local forecast constant into a new constant of lowToday and HighToday
const {today: {low: lowToday, high: highToday}} = LOCAL_FORECAST;
//return output into console
console.log(lowToday, highToday)
```

#### ***What have I completed today*** :white_check_mark:

- 50% of ES6 - FCC Modules

#### ***What is next on the list*** :pencil2:

- Finish FCC ES6
- Further investigation into using Vue as a platform going forward as well as incorporating Tailwind CSS.  This has been put on a backbone for now.  I need to get some further knowledge in and do some of the more basic JS functions first before I go ahead and decide on a platform to write in - that will come later.  Tailwind certainly looks to be a CSS framework for me for the future however to speed small projects up.

#### ***What have I been reading / watching?*** :books: :tv:

- FCC JS Concepts
