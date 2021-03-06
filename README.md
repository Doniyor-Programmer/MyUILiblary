# MyUILiblary
---
## Helper Classes
---
#### Align Classes
1. **text-center** - text-align: center;
2. **block-center** - margin: 0 auto;
---
#### Display Classes
1. **hidden** - visibility: hidden;
2. **visible** - visibility: visible;
3. **d-none** - display: none;
4. **d-block** - display: block;
5. **d-flex** - display: flex;
6. **f-centered** - justify-content and align-items: center;
7. **f-space-around** - justify-content: space-around;
8. **f-space-between** - justify-content: space-between;
---
#### Sizes Classes
1. **w-100** - width: 100%;
2. **w-50** - width: 50%;
3. **w-300** - width: 300px;
4. **w-500** - width: 500px;
5. **h-100** - height: 100%;
6. **h-50** - height: 50%;
7. **h-300** - height: 300px;
8. **h-500** - height: 500px;
---
#### We used SCSS in this lib here examples
```css
  /* Colors */
  $primary: #025fff;
  $success: #2a9924;
  $danger: #ea2e41;
  $warning: #ffc907;
  $dark: #343a40;
```
---
```css
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');

  * {
      font-family: 'Roboto', sans-serif;
  }
```
---
```css
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  .container {
      max-width: 1140px;
      padding: 0px 15px;
      margin: 0 auto;
  }
```
---
#### Font Classes
```css
  .fz-16 {
    font-size: 16px;
  }
  .fz-20 {
      font-size: 20px;
  }
  .fz-24 {
      font-size: 24px;
  }
  .bold {
      font-weight: bold;
  }
  .thin {
      font-weight: 300;
  }
  .italic {
      font-style: italic;
  }
  .text-color-primary {
      color: $primary;
  }
  .text-color-success {
      color: $success;
  }
  .text-color-danger {
      color: $danger;
  }
  .text-color-warning {
      color: $warning;
  }
  .text-color-dark {
      color: $dark;
  }
```
---
#### Paddings and margins there are almost same
__You can use padding with p names__
```css
  .m10 {
    margin: 10px;
  }
  .m20 {
      margin: 20px;
  }
  .mt-10 {
      margin-top: 10px;
  }
  .mr-10 {
      margin-right: 10px;
  }
  .mb-10 {
      margin-bottom: 10px;
  }
  .ml-10 {
      margin-left: 10px;
  }
  .mt-20 {
      margin-top: 20px;
  }
  .mr-20 {
      margin-right: 20px;
  }
  .mb-20 {
      margin-bottom: 20px;
  }
  .ml-20 {
      margin-left: 20px;
  }
```
---
---
---
## JavaScript Helpers
---
1. **$(selector)** - alternative to querySelector and All
2. **$(selector).addClass()** - alternative to classList.add()
3. **$(selector).removeClass()** - alternative to classList.remove()
4. **$(selector).toggleClass()** - alternative to classList.toggle()
5. **$(selector).contains()** - alternative to classList.contains()
6. **$(selector).getAttr()** - alternative to Node.getAttribute()
7. **$(selector).setAttr()** - alternative to Node.setAttribute(), but here 2nd arg is optional
8. **$(selector).toggleAttr()** - toggle attribute also here 2nd arg is optional
9. **$(selector).show()** - used for style.display = ''
10. **$(selector).hide()** - used for style.display = 'none'
11. **$(selector).toggle()** - used for toggle display
12. **$(selector).on(eventName, callback)** - alternative to addEventListener
13. **$(selector).off(eventName, callback)** - alternative to removeEventListener
14. **$(selector).click(1 - callback, 2- without callback)** - alternative to 1 - addEventListener or 2 - click()
15. **$(selector).fadeIn(duration, by default display block but you can change, callback optional)** - js animation
16. **$(selector).fadeOut(duration, callback optional)** - js animation
17. **$(selector).fadeToggle(duration, by default display block but you can change, callback optional)** - js animation
18. **$(selector).html()** - if there is arg it used for change innerHTML else get innerHTML
19. **$(selector).eq(index)** - alternative for querySelectorAll(selector)[0]
20. **$(selector).index()** - current index of elem inside of parent
21. **$(parent selector).find(child or children selector)** - used for finding >
22. **$(selector).closest(selector)** - alternative to Node.closest()
23. **$(selector).siblings()** - all elements inside of parent
---
---
---
