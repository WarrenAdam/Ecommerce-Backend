# Ecommerce-Backend
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Description

Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:

- What was your motivation?
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
- What problem does it solve?
- What did you learn?

## Overview

The following was adpated from the Module 13 coding bootcamp protal.

User Story:<br>
AS A manager at an internet retail company<br>
I WANT a back end for my e-commerce website that uses the latest technologies<br>
SO THAT my company can compete with other e-commerce companies

Acceptance Criteria:<br>
GIVEN a functional Express.js API<br>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file<br>
THEN I am able to connect to a database using Sequelize<br>
WHEN I enter schema and seed commands<br>
THEN a development database is created and is seeded with test data<br>
WHEN I enter the command to invoke the application<br>
THEN my server is started and the Sequelize models are synced to the MySQL database<br>
WHEN I open API GET routes in Insomnia Core for categories, products, or tags<br>
THEN the data for each of these routes is displayed in a formatted JSON<br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core<br>
THEN I am able to successfully create, update, and delete data in my database

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To use the Express JS API, you must install packages MySQL2 and Sequelize. In addition, you need to install dotenv to hide sensitve information (such as; database name, MySQL2 username and password). This can be done by running the following command npm install in the terminal, as the package.json is already provided in the starter code.

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```

## Credits
To better understand Sequelize modeling and route structures, I watched the following video: https://www.youtube.com/watch?v=Crk_5Xy8GMA

## License

MIT License

Copyright (c) 2023 WarrenAdam

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
