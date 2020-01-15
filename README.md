<p align="center">
  <p style="font-size: 38px;" align="center">Favorite Fonts<p>
  <h3 align="center">A solo project for Chingu community.</h3>

  <p align="center">
  <a href="http://www.firsttimersonly.com"><img src="https://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square" alt="First-timers Friendly"></a>
  </p>
</p>

## 📖 Usage

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

## 👀 Dependencies

- ⚡️ [NuxtJS](https://nuxtjs.org/)

## 👤 Author

**LucasAlt**
* Website: https://lucasalt.fr
* Twitter: [@LucasCtrlAlt](https://twitter.com/LucasCtrlAlt)
* GitHub: [@LucasCtrk](https://github.com/LucasCtrl)

## 🤝 Contributing

1. Fork it (https://github.com/Chingu-Solo/solo-koala-82/fork)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## 📝 To-Do list

### **Requirements**

#### Structure
- [X] Header with minor navigation *(Logo and Catalog/Featured/Articles/About link list)*
- [ ] Nav with Major navigation / page-manipulation *(search, custom text, font-size, dark/light mode, grid/list mode, and reset)*
- [ ] Main section for the font cards
- [ ] Font cards which display the Font Name, the sample text, and an add button (the font creator is **not** available via the api, so it is not required in tiers 2 or 3)
- [ ] Back-to-top button that allows users to click and scroll back up to the top *(there could be up to 959 fonts displayed, so you need this!)*
- [ ] Footer section with your developer information

#### Style
- [ ] Sample text in each card should be displayed in the corresponding font
- [ ] Buttons/links should be evident (make sure the cursor changes, etc.)
- [ ] Implement a way to handle overflow from sample text in the font cards, as the font size is adjustable

#### Functionality
- [ ] Text typed into the custom text (type something) box should immediately change the sample text in each font card
- [ ] The sample text should return to the default sample if the input box (type something) no longer has any input
- [ ] Font size chooser should have at least four sizes and should immediately change the sample text font size in each font card
- [ ] Implement the clickable 'reset' icon on the far right of the major navigation; it should reset the page as if the page were reloaded *(do not actually reset the page)*
- [ ] On load, the page should display fonts sorted by current popularity, as returned by the Google Fonts Developer API *(see below)*
- [ ] The search feature should be fully functional and should display matching fonts (it's up to you if you want to do this via a 'submit' or through onchange)
- [ ] When the search input is cleared (via reset button or manually), the fonts should automaticaly display sorted by poplarity again

#### Other
- [ ] Your repo needs to have a robust README.md
- [ ] Make sure that there are no errors in the developer console before submitting

### **Extras (Not Required)**

- [ ] Make your design fully responsive (small/large/portrait/landscape, etc.)
- [ ] Implement the light/dark mode toggle buttons
- [ ] Implement the change display icon so you can flip between a grid layout and a list layout for the font cards
- [ ] Make the 'add-font' icon add the font to a list (localHost, Cache API, etc) for front-end persistence; users can then delete the font from the list


## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is unlicensed.
