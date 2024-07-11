# NeighbourGoods Marketplace

## Overview
NeighbourGoods Marketplace is a hyperlocal community-driven web application developed using Flask, SQLAlchemy, SQLite, Bcrypt, and Bootstrap Modals. The platform enables users to buy and sell goods within their neighborhood, fostering community interaction and convenience.

## Features
- **Dynamic Product Listings**: Users can view, add, edit, and delete product listings.
- **Purchasing and Selling**: Seamless transaction functionalities for buying and selling goods.
- **User Authentication**: Secure user login and registration system with session management.
- **Data Security**: Bcrypt hashing for password security and CSRF protection to prevent cross-site request forgery.
- **Wallet Feature**: Integrated wallet functionality for managing transactions within the platform.

## NeighbourGoods Marketplace

### Overview

NeighbourGoods Marketplace is a hyperlocal community-driven web application developed using Flask, SQLAlchemy, SQLite, Bcrypt, and Bootstrap Modals. The platform enables users to buy and sell goods within their neighborhood, fostering community interaction and convenience.

### Features

- **Dynamic Product Listings**: Users can view, add, edit, and delete product listings.
- **Purchasing and Selling**: Seamless transaction functionalities for buying and selling goods.
- **User Authentication**: Secure user login and registration system with session management.
- **Data Security**: Bcrypt hashing for password security and CSRF protection to prevent cross-site request forgery.
- **Wallet Feature**: Integrated wallet functionality for managing transactions within the platform.

### Project Structure

```bash
└── NeighbourGoods
    ├── instance
    │   └── market.db
    ├── market
    │   ├── forms.py
    │   ├── __init__.py
    │   ├── market.db
    │   ├── models.py
    │   ├── __pycache__
    │   │   ├── forms.cpython-312.pyc
    │   │   ├── __init__.cpython-312.pyc
    │   │   ├── models.cpython-312.pyc
    │   │   └── routes.cpython-312.pyc
    │   ├── routes.py
    │   ├── static
    │   │   ├── brand.jpg
    │   │   └── landing.jpg
    │   └── templates
    │       ├── base.html
    │       ├── home.html
    │       ├── includes
    │       │   ├── items_modals.html
    │       │   └── owned_items_modals.html
    │       ├── login.html
    │       ├── market.html
    │       ├── register.html
    │       └── register_product.html
    ├── __pycache__
    └── run.py
```

### Security Measures

- **Password Hashing**: All user passwords are securely hashed using Bcrypt.
- **CSRF Protection**: Cross-Site Request Forgery protection is implemented to ensure secure transactions and data integrity.

