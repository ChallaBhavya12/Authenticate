In this project, let's build a **Nxt Trendz - Specific Product Details** app by applying the concepts we have learned till now.

The app will following functionalities

- When an unauthenticated user, tries to access the Product Item Details Route, then the page should be navigated to Login Route
- When an authenticated user clicks on a product in the Products Route, then the page should be navigated to Product Item Details route
- When an authenticated user opens the Product Item Details Route,
  - An HTTP GET request should be made to **productDetailsApiUrl** with `jwt_token` in the Cookies and product `id` as path parameter
  - **_loader_** should be displayed while fetching the data
  - After the data is fetched successfully, display the product details and similar products received in the response
  - Initially, the quantity of the product should be `1`
  - The quantity of the product should be incremented by one when the plus icon is clicked
  - The quantity of the product should be decremented by one when the minus icon is clicked
  - If the HTTP GET request made is unsuccessful, then the [Failure view](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-product-details-error-lg-output.png) should be displayed
    - When the **Continue Shopping** button in the [Failure view](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-product-details-error-lg-output.png) is clicked, then the page should be navigated to Products Route

</details>

- Prime User credentials

  ```
   username: rahul
   password: rahul@2021
  ```

- Non-Prime User credentials

  ```
   username: raja
   password: raja@2021
  ```
