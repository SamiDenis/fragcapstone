# capstone

***Welcome to Dream of Fragrance***

Your go to for all things fragrance

Dream of Fragrance can be accessed through its main page at :( https://fragcapstone-ju9gwd0r4.vercel.app/Mens/Cart )

On the main page, the user is able to "click" on one of two options: Mens or Womens. Once "clicked", the user will be able to view an array of fragrances. What the user will see is each individual fragrance's image, name, brand, type and price. Once the user decides their preferred fragrance, they are able to "click" the *ADD* button. By pressing the *ADD* button, the user is adding the selected fragrance to their cart.

In both the Mens and Womens pages, there is a *NEW* button below their respected banners. If the user does not see a particular fragrance, they are able to create it using the *NEW* button. By pressing the button, the user will be redirecting to a page containing a form, where they can populate the fragrance name, image, and price. Once the *SUBMIT* button is "clicked" at the button, the user will get an alert that their fragrance was created. The user will be able to view their new fragrance in the page it was created in (Mens/Womens).

Once the user has added their favored fragrances to their cart, they may view them in the Cart page. If the user decided they did not want a particular fragrance in their cart, they may be able to remove it by clicking the *DELETE* button. If the description of a particular fragrance is incorrect (such as price drop), the user is able to edit the fragrance (by name, image, or price) by "clicking" the *EDIT* button.


Frontend created using: *React.js 

Dependencies Installed:
    npx create-react-app
    npm run start
    





The APIs used were created:

FRAGRANCE API LINK: 
(Mens) https://fragbackend.herokuapp.com/Mens 

(Womens) https://fragbackend.herokuapp.com/Womens



API CREATED LINKS : 

(Mens) https://fragbackend.herokuapp/Mens 

(Womens) https://fragbackend.herokuapp/Womens



(Using GET) https://fragbackend.herokuapp/Mens ==> *page accessing the info for mens fragrance and their properties

(Using GET) https://fragbackend.herokuapp/Womens ==> *page accessing the info for womens fragrances and their properites

(Using GET) https://fragbackend.herokuapp/Mens/Womens ==> *page accessing the info for womens fragrances and their properites

(Using GET) https://fragbackend.herokuapp/Mens/Cart ==> *page will give info on the products [mens] in their cart

(Using GET) https://fragbackend.herokuapp/Womens/Cart ==> *page will give info on the products [womens] in their cart

(Using POST) https://fragbackend.herokuapp/Mens/Cart ==> *page will now have a form with info regarding new frangrance created

(Using POST) https://fragbackend.herokuapp/Womens/Cart ==> *page will now have a form with info regarding new frangrance created

(Using POST) https://fragbackend.herokuapp/Mens ==> *page will now have a form [mens] with info regarding new frangrance created

(Using POST) https://fragbackend.herokuapp/Womens ==> *page will now have a form [womens] with info regarding new frangrance created

(Using GET) https://fragbackend.herokuapp/Mens/Cart/:id ==> *page updating the id numbers for each individual frangrance [mens]

(Using GET) https://fragbackend.herokuapp/Womens/Cart/:id ==> *page updating the id numbers for each individual frangrance [womens]

(Using PUT) https://fragbackend.herokuapp/Mens/Cart/:id ==> *page updating all files containing a fragrance [mens]

(Using PUT) https://fragbackend.herokuapp/Womens/Cart/:id ==> *page updating all files containing a fragrance [womens]

(Using DELETE) https://fragbackend.herokuapp/Mens/Cart/:id ==> *page deleting all files specific to their id [mens]

(Using DELETE) https://fragbackend.herokuapp/Womens/Cart/:id ==> *page deleting all files specific to their id [womens]



Backend created using: *Node.js *Mongoose *MongoDB *CORS *Express

Dependencies Installed:
    npm init
    npm install express
    npm install mongoose
    npm install cors


Frontend and Backend information made by Samantha Denis