# Frontend Mentor - E-commerce product page solution

This is a solution to the [E-commerce product page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ecommerce-product-page-UPsZ9MJp6). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents
- [Overview](#overview)
- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
### The challenge
Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Open a lightbox gallery by clicking on the large product image
- Switch the large product image by clicking on the small thumbnail images
- Add items to the cart
- View the cart and remove items from it

### Screenshot
![](./screenshot.jpg)

### Links
- Solution URL: [Solution URL ](https://github.com/JuzzJoel/ecommerce-product-page-main)
- Live Site URL: [Live site URL ](https://ecommerce-product-page-main-mu-murex.vercel.app/)

## My process
### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- JavaScript

### What I learned
I learned how to implement a lightbox gallery and how to use JavaScript to update the cart display.

javascript
function updateCartDisplay() {
  amtElement.textContent = amt;
  const total = (amt * 125.00).toLocaleString("en-US", { minimumFractionDigits: 2 });
  resultElement.textContent = $${total};
  if (amt > 0) {
    cartItems.style.display = "flex";
    checkoutButton.style.display = "block";
    emptyCartMessage.style.display = "none";
  } else {
    cartItems.style.display = "none";
    checkoutButton.style.display = "none";
    emptyCartMessage.style.display = "block";
  }
}


*Continued development*
I want to continue improving my JavaScript skills and learn how to use more advanced features like async/await and promises.

*Useful resources*
- https://developer.mozilla.org/en-US/ - This website provides excellent documentation and resources for web developers.
- https://www.w3schools.com/ - This website provides tutorials, examples, and reference materials for web development.

*Author*
- Frontend Mentor - https://www.frontendmentor.io/profile/JuzzJoel
- Twitter - https://x.com/JOOlajire

*Acknowledgments*
I would like to thank Frontend Mentor for providing the design and challenge.

