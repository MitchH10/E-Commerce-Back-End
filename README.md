# E-Commerce Backend Api [![License: WTFPL](https://img.shields.io/badge/License-WTFPL-brightgreen.svg)](http://www.wtfpl.net/about/)

## Description
This is an express backend for an E-Commerse api. This api uses mysql with sequelize to store product, category, and tag data for items in a store. Using the REST standard following api request can be made to view all, view one, create, update, and delete products, categories, and tags.

## Video Showcase Link
[https://drive.google.com/file/d/1ErT-BOuV_G79VPHn3zIgNA3Y3_e4889i/view](https://drive.google.com/file/d/1ErT-BOuV_G79VPHn3zIgNA3Y3_e4889i/view)

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation
Install from github. Run an "npm init". Then run an "npm i" to install the packages used. After that open your mysql client and source the schema located in the db folder. After that, run the seed js files by typing "npm run seed". Then you are ready to run the server with "npm start".

## Usage
To use made requests to the following api routes: get routes: "localhost:3001/api/categories/", "localhost:3001/api/categories/:id", "localhost:3001/api/tags/", "localhost:3001/api/tags/:id", "localhost:3001/api/products/", "localhost:3001/api/products/:id". Post routes: "localhost:3001/api/categories/", "localhost:3001/api/tags/", "localhost:3001/api/products/". Put routes: "localhost:3001/api/categories/:id", "localhost:3001/api/tags/:id", "localhost:3001/api/products/:id". Delete routes: "localhost:3001/api/categories/:id", "localhost:3001/api/tags/:id", "localhost:3001/api/products/:id"

## License
[http://www.wtfpl.net/about/](http://www.wtfpl.net/about/) <br />
~~~
      DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
      Version 2, December 2004 

Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 

Everyone is permitted to copy and distribute verbatim or modified 
copies of this license document, and changing it is allowed as long 
as the name is changed. 

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

0. You just DO WHAT THE FUCK YOU WANT TO.
~~~

## Contributing
If you would like to contribute contact me via github or email

## Tests
To test use the seed data if you would like and use something like insomia to send requests to the server.

## Questions
For any questions contact me on: <br />
Github: [https://github.com/MitchH10](github.com/MitchH10) or <br />
Email: [mjh10@live.com](mjh10@live.com)

## Link to repo
[https://github.com/MitchH10/E-Commerce-Back-End](https://github.com/MitchH10/E-Commerce-Back-End)