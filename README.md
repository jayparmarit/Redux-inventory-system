This project uses React + Redux Toolkit to manage product data such as adding, updating, and deleting products.

Below is a breakdown of the main Redux logic and component behavior shown in the screenshots.

🔹 Purpose

This file defines the Redux slice responsible for managing:

Product list

Update state

Loading state

✅ Key Learnings

Redux Toolkit simplifies state updates

createSlice removes the need for switch cases

useSelector reads data

useDispatch updates data

Correct folder naming is critical in Vite projects

src
 ├── Components
 <br/>
 │   ├── ProductForm.jsx
 <br/>
 │   └── ProductList.jsx
 <br/>
 │
 ├── feature
 <br/>
 │   └── product
 <br/>
 │       └── productSlice.js
 <br/>
 │
 ├── store
 <br/>
 │   └── store.js
 <br/>
