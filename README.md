# _Tap Room _

#### _A React application for kombucha store to track their kegs._ 

#### _September 11, 2020 | Fatma C. Dogan_

## Description

_An application built in React to track a taproom's taps by name, brand, price, flavor, and quantity. The application utilizes a tap list, a new tap form, and tap-specific details view to monitor inventory._

<!-- _View the live site at:_  -->


### Component Diagram

<img src="tap-room diagram.jpg" width="550px" />

## Specification user stories:
* As a user, I want to see a list/menu of all available kegs. For each keg, I want to see its name, brand, price and flavor
* As a user, I want to submit a form to add a new keg to a list.
* As a user, I want to be able to click on a keg to see its detail page.
* As a user, I want to see how many pints are left in a keg.
* As a user, I want to be able to click a button next to a keg whenever I sell a pint of it. This should decrease the number of pints left by 1. Pints should * not be able to go below 0.

## Setup/Installation Requirements

#### Node install

###### For macOS:
_If Homebrew is not installed on your computer already, then install Homebrew by entering the following two commands in Terminal:_
* $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
* $ echo 'export PATH=/usr/local/bin:$PATH' >> ~/.bash_profile

_Install Git with the following command:_
* $ brew install git

_Next, install Node.js by entering the following command in Terminal:_
* $ brew install node

###### For Windows:
_Please visit the [Node.js website](https://nodejs.org/en/download/) for installation instructions._

#### Install this application

_Clone this repository via Terminal using the following commands:_
```
cd desktop
<!-- git clone https:// -->
<!-- cd merch-site -->
```

_Next, install npm at the project's root directory, and start the server:_
```
npm install
npm start
```

_If everything is correct, the localhost site should open automatically_

_View the contents of this project by opening in VSCode:_
```
code .
```


## Technologies Used

* _React_
* _JavaScript_
* _WebPack_
* _CSS_
* _Git_

### License

*This webpage is licensed under the MIT license.*

Copyright &copy; 2020 **_Fatma C. Dogan_**