# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion 

```javascript
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2 ").innerHTML = "Rohan Malo"

document.querySelector(".side-bar .crayons-card .color-base-70 ").innerHTML = "building awesome staff with code"
```

### Output

![Output](./one.png)

--------------------------------------------------------------------------------------

2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Picture_3.png)

### Fetch all the product name and store in an array

```javascript
let arr = []

for (let i = 0; i < 7; i++) {
    arr.push(document.querySelectorAll(".as-imagegrid-item-title")[i].innerText.splt("\n")[0])
     }

// Using for in loop 
```

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

![Store](./two.PNG)


---------------------------------------------------------------------------------------


3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

### Output

```javascript
let list = document.querySelector(".article .accordion-homepage")
​
newEle = document.createElement("section")
​
newEle.textContent = "New item added by Rohan"
​
list.append(newEle)

newEle.className = "parent" 

```

![Output](./three.png)


--------------------------------------------------------------------------------------------

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./Pic6.png)

### Tasks

      Change the contact number

### Output

```javascript
 document.querySelector(".one-tel-number ").innerText = "+91 6289038527"
```

![Output](./fore.png)


--------------------------------------------------------------------------------------------

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out

### Output


```javascript
document.querySelector(".diwali-deals-product-sale-btn").innerText = "Check Out"
```

![Output](./five.png)


--------------------------------------------------------------------------------------------

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

### Output

```javascript
let search = document.querySelector(".searchinput___19uW0")

search.addEventListener('mouseover', () => { search.style.background = "red" });
```

![Sample One](./six.png)

--------------------------------------------------------------------------------------------

7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### Output

```javascript
let search = document.querySelector('#top-nav-search-input')

search.value = "CSS Selector"

document.querySelector('.search-form').submit()
```

![Output](./seven.png)


--------------------------------------------------------------------------------------------

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Output

```javascript

let lang = document.querySelector('#SIvCob').children

for(ele in lang){
     if( ele % 2 === 0 ){
          lang[ele].remove()
     }
}

```

![Output](./eight.png)

--------------------------------------------------------------------------------------------

9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

### Output

```javascript
let str = document.querySelector('.display-heading-1')

str.style.fontFamily = "monospace"

str.style.color = "#AB341D"
```

![Output](./nine.png)


--------------------------------------------------------------------------------------------

10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

### Output


```javascript
let str = document.querySelector('.btn-cta-big .login-btn-text')

str.addEventListener("mouseover", () => { str.style.background = "red" } )

```

![Output](./ten.png)


--------------------------------------------------------------------------------------------

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Output


```javascript
document.querySelector('.icon-logo').style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')"
```

![Output](./eleven.png)


--------------------------------------------------------------------------------------------


12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./Pic22.png)

### Tasks

     change the background colour of the button to blue.

### Output


```javascript
document.querySelector('.btn').style.background = "blue"
```

![Output](./twelve.png)


--------------------------------------------------------------------------------------------

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### Output

```javascript
document.querySelector('.fl-heading-text').innerHTML = "JSBOOTCAMP"
```

![Output](./thertin.png)


--------------------------------------------------------------------------------------------

14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

### Output


```javascript
document.querySelector('.HotDealsAll__Heading__2fIbe').style.fontSize = "80px"
```

![Output](./fortin.png)


--------------------------------------------------------------------------------------------

15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

### Output

```javascript
document.querySelector('.ps-title a').style.float = "right"
```

![Output](./fiften.png)


--------------------------------------------------------------------------------------------

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### Output

```javascript
document.querySelector('.section-title_title__VEDfK').innerHTML = "Start with Scratch"
```

![Output](./sixten.png)

--------------------------------------------------------------------------------------------

