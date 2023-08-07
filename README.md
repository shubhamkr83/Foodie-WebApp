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

<h2>Folder Structure:-</h2>
``bash 
.
├── app</p>
│   ├── config</p>
|       └── passport.js</p>
│   ├── http</p>
│       ├── controllers</p>
│           ├── admin</p>
│               ├── orderController.js</p>
│               └── statusController.js</p>
│           ├── customers</p>
│               ├── cartController.js</p>
│               └── orderController.js</p>
│           ├── authController.js</p>
│           └── homeController.js</p>
│       └── middlewares  </p>
│           ├── admin.js</p>
│           ├── auth.js</p>
│           └── guest.js</p>
│   └── models  </p>
│       ├── menu.js</p>
│       ├── order.js</p>
│       └── user.js   </p>
├── public       </p>
│   ├── css</p>
│       └── app.css</p>
│   ├── img</p>
│   └── js</p>
│       ├── app.js</p>
│       └── app.js.LICENCE.txt</p>
├── resources </p>
│   ├── js</p>
│       ├── CardWidget.js</p>
│       ├── admin.js</p>
│       ├── apiService.js</p>
│       ├── app.js</p>
│       └── stripe.js</p>
│   ├── scss</p>
│       ├── _varible.scss</p>
│       └── app.scss</p>
│   └── views</p>
│           ├── admin.js</p>
│               └── orders.ejs</p>
│           ├── auth</p>
│               ├── login.ejs</p>
│               └── register.ejs</p>
│           ├── customers</p>
│               ├── cart.ejs</p>
│               ├── orders.ejs</p>
│               └── singleOrder.ejs</p>
│           ├── errors</p>
│               └── 404.ejs</p>
│           ├── home.ejs</p>
│           └── layout.ejs</p>
├── routes</p>
│   ├── api.js</p>
│   └── web.js</p>
├── .gitignore      </p>             
├── menus.json</p>
├── mix-manifest.json  </p>                   
├── package-lock.json   </p>                 
├── package           </p>        
├── server.js</p>
├── webpack.mix.js     </p>                
├── yarn-error.log     </p>               
├── yarn.lock         </p>          
└── README.md</p>
... ```



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

