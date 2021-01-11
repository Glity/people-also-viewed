# **Glity - A Food Reviews and Ratings Web Application**

## **About**

- An interactive restaurants web application for food reviews and ratings. This is a micro-service MERN full-stack application.

## **Table of Contents**

- [Client Demo](#Demo)
- [Dependencies](#Dependencies)
- [Deployment](#Dependencies)
- [Database Schema Design](#MongoDB)

## **Demo**

<p align="center">
<img src="https://hackreactor-restaurant-images.s3-us-west-2.amazonaws.com/static-images/FTC-img1.png" width="75%"></p>

<p align="center">
<img src="https://hackreactor-restaurant-images.s3-us-west-2.amazonaws.com/static-images/FTC-img2.png" width="75%"></p>

<p align="center">
<img src="https://hackreactor-restaurant-images.s3-us-west-2.amazonaws.com/static-images/FTC-img3.png" width="75%"></p>

## **Technologies / Framworks Used**
- MongoDB
- Moongoose.js
- Express.js
- React
- Node.js
- Styled Components
- Jest / Enzyme

## **Dependencies**

From within the root directory:

```sh
npm install
```

## **Requirements**

- Node 10.5.0
- npm 6.14.7
- MongoDB 4.2.8

## **Development**

From within the root directory:

To run dev environment/webpack

```sh
  npm run react-dev
```

To run server

```sh
  npm start
```

To seed database

```sh
  npm run seed
```

To run tests

```sh
  npm run test
```

To access local browser

```sh
  To get started with People Also Viewed Module, run http://localhost:3000/ on your local web browser.
```

## **Database Schema Design**

### **MongoDB**:

```
const restaurantSchema = new mongoose.Schema({
  id: Number,
  name: String,
  reviews: Number,
  reviewsNum: Number,
  price: Number,
  category: Array,
  displayImgURL: String,
  heart: Boolean,
  super_rated: Boolean,
  inner_img: Array,
  unique_id: Number,
  reviewModal: Array,
  individual_rating: Number
});
```