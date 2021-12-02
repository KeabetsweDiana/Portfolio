# React
This is my portfolio developed using React.

---
How to bootstrap this app:

//install Bootstrap as a dependency for your app

npm install bootstrap

//Once you have Bootstrap installed, go ahead and include it in the app’s entry JavaScript file.

//Install jquery and popper.js

npm install jquery popper.js

//Add the new dependencies

import 'bootstrap/dist/css/bootstrap.min.css';
import $ from 'jquery';
import Popper from 'popper.js';
import 'bootstrap/dist/js/bootstrap.bundle.min';
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import App from './App';
import registerServiceWorker from './registerServiceWorker';

ReactDOM.render(<Dropdown />, document.getElementById('root'));
registerServiceWorker();

//The link to my portfolio app
https://keabetswe.herokuapp.com/
