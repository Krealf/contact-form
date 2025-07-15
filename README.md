# Frontend Mentor - Contact form solution

This is a solution to the [Contact form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/contact-form--G-hYlqKJj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Complete the form and see a success toast message upon successful submission
- Receive form validation messages if:
  - A required field has been missed
  - The email address is not formatted correctly
- Complete the form only using their keyboard
- Have inputs, error messages, and the success message announced on their screen reader
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

Desktop:
<img width="1920" height="839" alt="chrome_zHv7Y65WRw" src="https://github.com/user-attachments/assets/fee34c56-9e3f-44fe-8bf4-af8c78408593" />


Mobile:
<img width="375" height="824" alt="chrome_9zUzzWR80k" src="https://github.com/user-attachments/assets/467699c3-3248-419d-af76-60bde73ca2e4" />

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/basic-layout-site-with-flexbox-and-stylization-inputs-wwjbgAQsms)
- Live Site URL: [GitHub IO](https://krealf.github.io/contact-form/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Russian:
> Я научился работать с тегаи form, input, label, textarea и их стилизацией. Для гибкости страницы я использовал Flexbox, что позволило мне сделать хороший адаптив под телефон. Но были такие проблемы:
> - Из-за ограниченной стилизации inputов с типом 'radio' было сложно реализовать функциональный закрашенный зелёный кружочек
> - Я не реализовал подсветку выбранного варианта в Query Type, так как не смог определить изменение стилей для "родительского элемента" (class=form__radio-item) по активации input (class=form__radio).
> - Не смог сделать отображение ошибки (message_error) после нажатия кнопки "submit"
> - Не смог сделать проверку поля Email на наличиие знака "@", отчего и не смог вывести поле с текстом "Please enter a valid email address"
> - Не смог сделать всплывающее сообщение об успешной отправке заполненной формы
> - Не смог сделать стилизацию галочки checkbox (form__agreement).

English:
> I have learned working with tags: form, input, label, textarea and stylization them. For adaptive i have used Flexbox and this have gived me opportunity easy made site for telephone. But i have problems:
> - Because limited stylization element "input" with type "radio" was diffucult realized functional green circle right on text.
> - I didn't realize black green outline active option in "fieldset" with class "form__fieldset", because i didn`t can realize editing style for parent element with class "form__radio-item" after choose right "input" with class "form__radio".
> - I cann't realize showing error after push button "submit"
> - I cann't realize checking field "email" for availability "@" and because i cann't realise showing error with text "Please enter a valid email address"
> - I cann't realize message for user about successful result
> - I cann't realize stylization icon check in checkbox (form__agreement)

### Useful resources

- [W3Schools]([https://www.example.com](https://www.w3schools.com/html/html_form_input_types.asp)) - This resource has helped me recall meterials about tag "input", his attribute and has gived me example with all value (Со всеми значениями атрибута type).
- [MDN]([https://www.example.com](https://developer.mozilla.org/en-US/)) - Good resource and he has helped me recall about tag "textarea" and his attribute.
- [BEM Methodology] - I have been using this resource for writing names class for my challange

## Author

- GitHub - [krealf](https://github.com/Krealf)
- Frontend Mentor - [@krealf](https://www.frontendmentor.io/profile/Krealf)
