# Pizza-Man

A website for ordering your favourite Pizza Online.


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


