# M&S Test

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### How it works!
Each product card has a button that dispatches the action `ADD_TO_CART` which passes the product into 3 mutations.

These are as follows:

`HANDLE_PRODUCT_ADD`: Looks for a record of the product if it finds increments the total if not adds new record.

`HANDLE_DISCOUNT`: Checks if there are over one quantity of Jeans with its ID and calculates the amount of discount required.

`HANDLE_TOTAL`: Calculates the totals of the cart.
