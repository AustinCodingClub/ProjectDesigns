# eCommerce Project

---
This project is to create product that achieves two things...
- Allow a user to shop for item
- Allow a supplier to upload a catalog

While sounding simple, these are two very different use cases. The user is looking for a simple, easy to use interface that allows them to find and purchase items. The supplier is looking for a way to upload a catalog of items and manage their inventory.

---
## For a phase 1, we will focus in two areas...
1. User Interface
2. Backend architecture



### User Interface
The user interface should be simple. It should allow a user to
- Browse items
  - The user should be able to select a catalog and view the items in that catalog
- Add items to a cart
  - The user should be able to add items to a cart
        - Items should stay in a cart until the user checks out or is removed by the user
- Checkout
  - The user should be able to check out and pay for the items in the cart
    - For now this just means a simple form that allows the user to enter their payment information

### Backend Architecture
The backend architecture should be robust. We will be using a microservices' architecture. This will allow us to scale the application as needed. We will also be using a NoSQL database to store the items. This will allow us to store a large amount of items and scale as needed.
We want
We need the following services for the first phase...
1. Catalog Service
    - This service will control access to suppliers' catalogs.
    - Add a catalog to the db
    - Add an item to a catalog
    - Remove an item from a catalog
    - Remove a catalog from the db
2. Cart Service
    - This service will control access to a user's cart
    - Add an item to a cart
    - Remove an item from a cart
    - Get a user's cart
    - when a user checks out, the cart will be converted to an order and sent to the order service
3. Order Service
    - This service will control access to a user's orders
    - Add an order to the db
    - Get a user's orders
    - Remove an order from the db
4. User Service
    - This service will control access to a user's information
    - Add a user to the db
    - Remove a user from the db
    - Get a user's information
    - Update a user's information
    - Authenticate tokens
    - SUPPORT OPENID CONNECT
---

## Phase 2
TBD
