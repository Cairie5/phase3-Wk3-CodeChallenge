# phase3-Wk3-CodeChallenge

# Restaurant-with-SQLAlchemy
Here you will work with three classes: Restaurant, Customer, and Review.The relationships between these models are defined as follows: a Restaurant has many Reviews, a Customer has many Reviews, and a Review belongs to both a Restaurant and a Customer. The code challenge contains several tasks, including setting up migrations, implementing object relationship methods, and creating aggregate and relationship methods.

## Table of content
Description
Installation requirement
Technology used
Licence
Authors info
## DESCRIPTION

### review.py
Here you'll implement methods for the Review class that represents reviews written by customers for restaurants.

### customer.py
Here you will implement methods for the customer class that represents customers who write reviews for restaurants. The Customer class has attributes for the given name and family name of the customer.

### restaurant.py
Here you'll implement methods for the Restaurant class that represents restaurants and their relationships with customers.

## INSTALLATION PROCESS

### Frontend
Git clone the repository to your local machine using the command 
```bash
https://github.com/Cairie5/phase3-Wk3-CodeChallenge
```
Navigate to the code challenge directory using cd Restaurants-with-SQLAlchemy
To install the necessary dependencies run pipenv install
TECHNOLOGY USED
python version pytest version sqlalchemy version

## Author
The author of this script is Patience Wangari Muraguri.

## LICENSE
MIT License

Copyright (c) 2023 Cairie5

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
