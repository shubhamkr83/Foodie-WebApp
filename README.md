# Foodie-WebApp
<h2>Realtime Food order app using NodeJs, Express and MongoDB.</h2>
<p>In this project we will build a realtime online food order app using Node Js, Express Js and Mongo DB. we will be using tailwind css for frontend as a css framework and will be using EJS template engine as well. we will be using socket.io for realtime communication. Using This app we will be able to order a food and get realtime notifications about food status.</p>

<h3>Live Project:- https://foodie-webapp.onrender.com </h3>


<h2>Features:-</h2>
<ol>
    <li>Login system</li>
        <ol>
            <li>Cookies and sessions</li>
            <li>Use Database as session store</li>
        </ol>
    <li>Registration</li> 
    <li>User roles</li>
    <li>Admin roles</li>
    <li>Shopping cart</li> 
    <li>Realtime pizza status tracker</li>
        <ol>
            <li>Real time web socket private connections</li>
        </ol>
</ol>


<h2>Technology Used:-</h2>
<ul>
<li>NodeJs</li>
<li>Express</li>
<li>MongoDB</li>
<li>EJS</li>
<li>Tailwind CSS</li>
<li>SASS</li>
<li>Passportjs (passport-local)</li>
<li>Axios</li>
<li>Bcrypt</li>
<li>express-ejs-layouts</li>
<li>express-flash</li>
<li>express-session</li>
</ul>


<h2>Project Screenshot:- </h2>
<h3>Hero Section</h3>

![Screenshot (333)](https://github.com/shubhamkr83/Foodie-WebApp/assets/72254047/56eb1756-df78-4285-b138-e216ee34b385)

<h3>All Food Items</h3>

![Screenshot (334)](https://github.com/shubhamkr83/Foodie-WebApp/assets/72254047/d34e0cb1-334a-4c84-a9e0-23a62ac2e4d5)


<h3>Cart Page</h3>

![Screenshot (337)](https://user-images.githubusercontent.com/72254047/232264866-eaacc611-fa6e-4784-95f3-0811d71639d7.png)

<h3>Register Page</h3>

![Screenshot (335)](https://user-images.githubusercontent.com/72254047/232264894-22330503-6413-483a-b2f1-1b0fc4cceb90.png)

<h3>Customer Realtime Food Tracker Page</h3>

![Screenshot (338)](https://user-images.githubusercontent.com/72254047/232264926-3e7011d0-1a0f-492e-8aeb-886826e9e403.png)

<h3>Admin Page</h3>

![Screenshot (339)](https://user-images.githubusercontent.com/72254047/232266233-f972e5be-3e3f-4416-a744-5ea8ac2f880f.png)


<h2>Folder Structure:-</h2>
<pre>
.
├── app
│   ├── config
|       └── passport.js
│   ├── http
│       ├── controllers
│           ├── admin
│               ├── orderController.js
│               └── statusController.js
│           ├── customers
│               ├── cartController.js
│               └── orderController.js
│           ├── authController.js
│           └── homeController.js
│       └── middlewares 
│           ├── admin.js
│           ├── auth.js
│           └── guest.js
│   └── models
│       ├── menu.js
│       ├── order.js
│       └── user.js 
├── public     
│   ├── css
│       └── app.css
│   ├── img
│   └── js
│       ├── app.js
│       └── app.js.LICENCE.txt
├── resources 
│   ├── js
│       ├── CardWidget.js
│       ├── admin.js
│       ├── apiService.js
│       ├── app.js
│       └── stripe.js
│   ├── scss
│       ├── _varible.scss
│       └── app.scss
│   └── views
│           ├── admin.js
│               └── orders.ejs
│           ├── auth
│               ├── login.ejs
│               └── register.ejs
│           ├── customers
│               ├── cart.ejs
│               ├── orders.ejs
│               └── singleOrder.ejs
│           ├── errors
│               └── 404.ejs
│           ├── home.ejs
│           └── layout.ejs
├── routes
│   ├── api.js
│   └── web.js
├── .gitignore           
├── menus.json
├── mix-manifest.json                  
├── package-lock.json                   
├── package          
├── server.js
├── webpack.mix.js                
├── yarn-error.log                 
├── yarn.lock                 
└── README.md
</pre>

