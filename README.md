

# Brand Shop Website
live link:https://brand-shop-a9253.web.app

live link:https://steady-salamander-c92a13.netlify.app/

## Project Features

### Features 1: Navbar
- Displays navbar in connecting avatar part.
- After login user can see containing Image, name and logout button.

### Features 2: Dashboard
- Displays services-specific data and statistics.
- Each services cart has image, price, title and details button.

### Features 3: Details
- Display single services details page.

### Features 4: Login
- Displays login page with validation.

### Features 5: Register
Displays register page with validation.

### features 5: Customer feedback
- customer can comment us about our brand by use in filed name and email
3.Installation:
firstly install server side
npm init -y
npm install express cors mongodb dotenv
code .
then open vscode editor. we open package.json file and go to scripts then set "start" : "node index.js" after that i create index.js file and writting server code here.

secondly install client side
npm create vite@latest (name-of-your-project) -- --template react
npm install react-router-dom localforage match-sorter sort-by
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
npm i -D daisyui@latest
code .
after that i open vs code editor and setup tailwind css setup and daisyUi setup.then i start my projects main part.

4.Technologies Used:
@emotion/react
@emotion/styled
@tanstack/react-query
axios
firebase
framer-motion
localforage
match-sorter
react
react-datepicker
react-dom
react-helmet-async
react-hook-form
react-icons
react-responsive-carousel
react-router-dom
react-simple-captcha
sort-by
sweetalert2
5.Some Features:
The website is optimized for mobile, tablet, and desktop.
Three roles - Normal User/Tourist, Tour Guide, and Admin.
Navbar, Banner/Slider, Tourism and Travel Guide, Tour Type, Footer.
JWT authentication, tanstack query, toast notifications
Utilized toast or sweet alerts for CRUD operations, login/signup success/error messages.
Framer Motion Animation: Integrated Framer Motion for card animations.
