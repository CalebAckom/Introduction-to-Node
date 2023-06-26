# Introduction to Node
 EDX's LinuxFoundationX LFW111x

## Chapter 2: Service Mocking

- Understand how to create a local file server with minimal effort.
- Learn how to create a very basic mock service with just Node.js core.
- Discover how to rapidly scaffold a Fastify service more involved mock services.

### About

The code is a JavaScript function that populates a list of products on a web page.
The function first:
- Creates an empty list of products.
- Then, it iterates through an array of product data and creates a new product item for each product.
  - Each product item is a <div> element with three <span> elements, one for each of the product's name, rrp, and info. 
- The function then appends each product item to the list of products.
- The function also defines a custom element called product-item. 
  - This custom element is a <div> element that has a shadow DOM.
  - The shadow DOM is a separate document that is used to encapsulate the DOM of the custom element.
  - This allows the custom element to have its own CSS and JavaScript.
- The function also defines an event listener for the click event on the #fetch element.
  - When the #fetch element is clicked, the function is called again to populate the list of products.

#### The code uses the async keyword to make the function asynchronous. This means that the function can perform long-running tasks without blocking the main thread. The await keyword is used to wait for the results of asynchronous tasks.