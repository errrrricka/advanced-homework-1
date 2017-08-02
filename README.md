#### Setup
Fork, clone, run yarn install, yarn start, pull request

#### Do
 * DONE*** Create a component folder to hold component files
 * Organize this web page into appropriate components
   * DONE*** ProductDetail - find a div with className="col-sm-4 col-lg-4 col-md-4"
   * DONE***  Header - find a div with className="navbar-header"
   * DONE*** Footer - find a footer element
   * DONE*** Carousel - find a div with className="row carousel-holder"
* DONE*** The ProductDetail should represent only one single product
* DONE*** The ProductDetail should take a prop called product with is an object, and use it to populate price, name, description reviews and stars.
* Make sure each component is in its own file and imported into App.js
  header - DONE
  Carousel - DONE
  ProductDetail - DONE (push)
* DONE*** Use the provided data in state.js to dynamically populate information instead of the hard coded html that is there now.
* DONE*** In index.js provide App with a prop called "products" sending in the product array
* App should use the product prop and map the array of products into an array of ProductDetail components
* Make the star images represent the number rating from data
