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

```

![Output](./Pic15.png)
