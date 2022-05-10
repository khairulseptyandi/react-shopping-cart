# React Shopping Cart

# Step 1 : Create React


# Step 8 : Checkout Form
  1. Set Active Task Management Spreadsheet
  2. Create branch checkout-form
  3. Cart.js
  4. Make Cart items persistent
  5. Use localStorage on App constructor to load cart items (JSON.parse)
  6. Use localStorage on addToCart to save cart items (JSON.stringify) 
  7. Handle Click on Proceed
  8. Update showCheckout state to true on click
  9. Conditional rendering Checkout Form
  10. Get Email, Name and Address required input
  11. Define hanldeInput function
  12. Add Checkout Button
  13. Handle onSubmit Form Event by this.createOrder
  14. Create order object and pass to parent to handle it
  15. Publish Changes
  16. Pull request, merge, change to master
  
# Step 9 : Add Modal and Animation
   1. Create Branch animation-modal
   2. Show Animation
   3. Install react-reveal
   4. Create fade effect from bottom for product
   5. Create fade left for add to cart
   6. Create fade right for show checkout form
   7. Open Modal by click on product image
   8. Install react-modal
   9. Product.js
   10. Import Modal
   11. Set state for product to null
   12. Define openModal and closeModal
   13. Show Modal if product exist
   14. Create Modal
   15. Create zoom effect for Modal
   16. index.css
   17. Style Product Details

# Step 10 : Create Products Backend
   1. Install nodemon globally
   2. Add server.js
   3. Install express body-parser mongoose shortid
   4. Install MongoDB
   5. app = express()
   6. app.use(bodyParse.json())
   7. mongoose.connect()
   8. create Product model
   9. app.post("/api.products")
   10. Postman send post request
   11. route.get("/api/products")
   12. route.delete("/apiproducts/:id")