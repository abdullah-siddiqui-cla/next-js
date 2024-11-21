# Task 1: Create products and products/:id Routes
## Build a `products` Page
- Use the App Router to create a products page (`app/products/page.js/ts`).
- Fetch products from the API endpoint `https://dummyjson.com/products` server-side.
- Display the products in a list or grid format, showing the product name and price.
- Style the page using Tailwind CSS or ShadCN components.

## Make Each Product Clickable using next Link
- Each product should link to a dynamic route, products/:id.

## Build the `products/:id` Page
- Use a dynamic segment (`app/products/[id]/page.js/ts`) to create the route.
- Fetch the details of a single product server-side from the API endpoint `https://dummyjson.com/products/:id.`
- Display the product's name, price, description, and image.
- Style the page using Tailwind CSS or ShadCN components.

# Task 2: Create products/new Page with a Form
## Build the Form
- Create a `products/new` page (`app/products/new/page.js/ts`) and mark it as a `client component`.
- Add a form with a single input field for entering a product's name.

## Add Validation
- Use `Zod` for validation to ensure the product name:
  - Has at least 2 characters.
  - Does not exceed 50 characters.
- Integrate Zod with React Hook Form using @hookform/resolvers/zod.
- Handle Form Submission
- On form submission, log the form data to the console and display a success message.

## Style the Form
- Use Tailwind CSS or `ShadCN` to style the form with proper input fields, error messages, and a submit button.

# Bonus
Ensure the `products` and `products/:id` pages handle errors gracefully if the API fails to respond.