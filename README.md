## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Overview

Pizza Paradise is a web-based application that allows users to customize their pizza by selecting size and toppings, add them to a cart, and place an order. The application uses Twilio to send order confirmations via SMS.

This project serves as a practical example of using Vue.js for building interactive UIs, Tailwind CSS for styling, and integrating external APIs.

## Features

-   **Pizza Customization:**
    -   Select pizza size (small, medium, large).
    -   Choose multiple toppings using checkboxes.
-   **Cart Management:**
    -   Add customized pizzas to a cart.
    -   View cart items with size, toppings, and price.
    -   Calculate the total order price.
-   **Order Placement:**
    -   Collects user's name, address, and phone number.
    -   Validates input fields.
    -   Places order with a loading state.
    -   Sends SMS confirmation via Twilio.
    -   Displays order confirmation/error message to the user.
-   **User-Friendly UI:**
    -   Responsive design using Tailwind CSS.
    -   Error messages shown for invalid input.
    -   Loading states and success message.
-   **Unit Tests:**
    -   Includes Jest tests to test the methods of the components
 

## Technologies Used

-   [Vue.js](https://vuejs.org/): JavaScript framework for building user interfaces.
-   [Tailwind CSS](https://tailwindcss.com/): CSS framework for styling.
-   [Twilio](https://www.twilio.com/): API for sending SMS messages.
-   [Jest](https://jestjs.io/): JavaScript testing framework.
-   [@vue/test-utils](https://test-utils.vuejs.org/): Vue.js testing library.
 - [libphonenumber-js](https://www.npmjs.com/package/libphonenumber-js): Library used for phone number validation

## Future Enhancements

-   **Backend Integration:** Implement a backend server to securely manage Twilio API calls, store order data, and potentially handle payments.
-   **Payment Gateway:** Integrate a payment gateway to allow users to pay for their orders.
-   **More Input Validation:** Implement more complex phone number validation using a library like `libphonenumber-js` and additional error handling.
-   **Real-time Updates:** Enhance the app with real-time updates using websockets for live order tracking.
-   **User Authentication:** Add user authentication to enable personalized order history.
-   **Re-usable components:** Refactor code to use re-usable components to improve code quality.
-  **End-to-end testing:** Add end-to-end testing to test the entire workflow.

## Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature: `git checkout -b feature-name`
3.  Commit your changes: `git commit -m "Add some feature"`
4.  Push to the branch: `git push origin feature-name`
5.  Open a pull request.
