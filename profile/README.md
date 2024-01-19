# <img src="/profile/foodbank.svg" width="100%" height="140" alt="FoodBank">

## Project Description
The Food Bank application is an innovative solution designed to help address hunger issues and improve community access to food. This application facilitates the provision of free food, provides information about food provider locations, distribution schedules, and offers options for donors to contribute.

### Mobile Application
- [Download Mobile App](https://storage.googleapis.com/foodbank-assets/app-debug.apk)
#### Email & Password for Login
- Email: usertest@test.com
- Password: securepassword
### Web Application
- [Access Web App](https://web-food-bank.vercel.app)
#### Email & Password for Login
- Email: usertest@test.com
- Password: securepassword

### Postman Link
- [Food Bank Postman Workspace](https://www.postman.com/restless-station-764528/workspace/food-bank-workspace/overview)

## Key Features
- **Food Provider Search**: Search for food provider locations based on location or date.
- **Interactive Map**: Find food provider locations around you with an interactive map.
- **Food Provider Information**: View details of food provider locations, including address, operating hours, and types of food provided.
- **Event Schedule**: Plan your visit by checking upcoming event schedules.
- **Food Provider Registration and Verification**: Facilitate food providers in registering and getting verified.
- **Donations**: Contribute in the form of money or goods.
- **Notifications**: Receive notifications about new locations, event schedules, or other important information.
- **Feedback System**: Provide user feedback to enhance the quality of service.

## Website Login
`
{
    "email": "usertest@test.com",
    "password": "securepassword"
}
`

## Login Mobile

`
 "email": "usertest@test.com",
    "password": "securepassword"
`

## Admin Website
<img  src="/web/web1.png"  width="100%"   alt ="FoodBank">
<img  src="/web/web2.png"  width="100%"   alt ="FoodBank">
<img  src="/web/web3.png"  width="100%"   alt ="FoodBank">
<img  src="/web/web4.png"  width="100%"   alt ="FoodBank">
<img  src="/web/web5.png"  width="100%"   alt ="FoodBank">
<img  src="/web/web6.png"  width="100%"   alt ="FoodBank">


## User Mobile

<div>
    <div">
        <img src="/mobile/mobile1.jpg" width="414" height="896" alt="FoodBank">
        <img src="/mobile/mobile2.jpg" width="414" height="896" alt="FoodBank">
    </div>
    <div>
        <img src="/mobile/mobile3.jpg" width="414" height="896" alt="FoodBank">
        <img src="/mobile/mobile4.jpg" width="414" height="896" alt="FoodBank">
    </div>
    <div>
        <img src="/mobile/mobile5.jpg" width="414" height="896" alt="FoodBank">
        <img src="/mobile/mobile6.jpg" width="414" height="896" alt="FoodBank">
    </div>
</div>


## Backend JS
- link Postman `https://www.postman.com/restless-station-764528/workspace/food-bank-workspace/overview`

- endpoint API : 
1. login `https://backend-dot-food-bank-410807.et.r.appspot.com/auth/login`
2. register `https://backend-dot-food-bank-410807.et.r.appspot.com/auth/register`
3. create Booth `https://backend-dot-food-bank-410807.et.r.appspot.com/booth`
4. list booth `https://backend-dot-food-bank-410807.et.r.appspot.com/booth`
5. edit booth `https://backend-dot-food-bank-410807.et.r.appspot.com/booth/:id`
6. delete booth `https://backend-dot-food-bank-410807.et.r.appspot.com/booth/:id`
7. create food `https://backend-dot-food-bank-410807.et.r.appspot.com/food`
8. create transaction `https://backend-dot-food-bank-410807.et.r.appspot.com/transaction`
9. update transaction `https://backend-dot-food-bank-410807.et.r.appspot.com/transaction/:transactionId`
10. get all transaction user `https://backend-dot-food-bank-410807.et.r.appspot.com/transaction/user/:userGuid` 
11. get transaction booth `https://backend-dot-food-bank-410807.et.r.appspot.com/transaction/booth/:boothGuid`
12. get detail transaction  `https://backend-dot-food-bank-410807.et.r.appspot.com/transaction/:transactionGuid`


## Installation Application Back End

To Installation this project run

```bash
  npm install
```

- after that, create an .env file, you can copy all the contents from .env.example

-  then run it
```bash
  npm run dev
```
you don't need to think about databases and other configurations


## Installation Application Front End

To Installation this project run

```bash
  npm install
```

- after that, create an .env file, you can copy all the contents from .env.example

-  then run it
```bash
  npm run start
```
you don't need to think about databases and other configurations



---
**Food Bank App** © 2024, Tim Gity. Dikembangkan oleh Gity Headquarters.
