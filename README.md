# Gauravs-pizza

An E-Commerce website for ordering Pizza Online

[![Netlify Status](https://api.netlify.com/api/v1/badges/2bba3c69-b525-44c9-b4ac-7883b15745b3/deploy-status)](https://app.netlify.com/sites/gaurav-pizza/deploys)

## Demo

<div align="center">
    <img src="./readme_img/demo.gif" style="width: 640px" />
</div>

**NOTE:** The features shown in the demo is not exhaustive. Only the core features are showcased in the demo.

## Tools used

1. React: To create the Single Page App
2. React-Router: For Routing
3. Redux: For State Management
4. Firebase: As a DataBase


# Screen shot of the web application


![Screenshot (303)](https://user-images.githubusercontent.com/103983412/233249368-a9d03918-195e-4486-b1a1-fb41c31dda2d.png)





![Screenshot (304)](https://user-images.githubusercontent.com/103983412/233249388-8eb1a66a-5042-49da-9e0f-9b8b476373cf.png)



![Screenshot (305)](https://user-images.githubusercontent.com/103983412/233249485-4a1fca7e-affb-4596-bd34-22a6b6e4799c.png)






![Screenshot (306)](https://user-images.githubusercontent.com/103983412/233249533-1bf9e42e-90fe-46c2-bb1d-6dc44a126332.png)

## Firebase Setup

You need to create a firebase configeration file holding the firebase settings in the path `/src/firebase/config.js`. The required format is:

```javascript
const firebaseConfig = {
	apiKey: "API-KEY",
	authDomain: "AUTH-DOMAIN.firebaseapp.com",
	databaseURL: "DATABASE-URL.firebaseio.com",
	projectId: "PROJECT-ID",
	storageBucket: "STORAGE-BUCKET.appspot.com",
	messagingSenderId: "MESSAGING-SENDER-ID",
	appId: "APP-ID",
	measurementId: "MEASUREMENT-ID",
};

export default firebaseConfig;
```

Data needs to be stored in the following format:-

```javascript
[
	{
		name: "CATEGORY NAME",
		items: [
			{
				desc: "PIZZA DESCRIPTION",
				id: "ID",
				img: "IMAGE LINK",
				name: "PIZZA NAME",
				price: 100, // PRICE
			},
		],
	},
];
```

An example data is given in `/src/firebase/exampleData.json`

## How to Use

To use the project follow the steps given below:

1. Install the necessary modules (`npm install`).
2. Setup Firebase Project and configuration
3. Use `npm start` to run the react app
