# Forkify - recipe search application

Last project from "The Complete JavaScript Course" by Jonas Schmedtmann.

### Features:
1. You can search for any recipe that you want and then the app will fetch data from [this API](https://forkify-api.herokuapp.com/).
2. You can then scroll through different results that are appeared and select one of them. 
3. When you select recipe then the app displays that recipe with an image, total time to prepare and ingredients. 
   - You can also adjust the number of servings which will automatically affect the quantity of all ingredients. 
4. Then you can add all of these ingredients to a shopping list where you can also adjust the number of ingredients or delete some of them. 
5. Another cool feature is that you can save any recipe in the section called favourites and everything will be saved in local storage.⁣⁣

---

### Running the project locally

First, to clone the repository on your local machine, run the following command:
```bash
git clone https://github.com/vladocodes/forkify-app
```

In order to run this project locally it's necessary to have installed **npm package manager**, if you don't have it run the following command to install the latest version:
```bash
npm install -g npm@latest
```

To install all necessary dependencies, run the following command:
```bash
npm install
```

Run the development server:
```bash
npm run start
```

The project will be available at http://localhost:8000/

To quit the local web server press `CTRL + BREAK`.
