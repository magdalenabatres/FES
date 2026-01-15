# Copilot Instructions for E-Commerce Project

## Project Overview
This E-Commerce project is structured to provide a seamless shopping experience. The architecture is modular, with distinct components handling different aspects of the application, such as user authentication, product management, and order processing.

## Key Components
- **index.html**: The main entry point of the application. It links to styles and scripts necessary for rendering the UI.
- **assets/**: Contains images, fonts, and other static resources used throughout the application.
- **Routing/**: Manages the navigation and routing logic of the application, ensuring users can navigate between different views.

## Developer Workflows
- **Building the Project**: Use the command `npm run build` to compile the project assets for production.
- **Testing**: Run `npm test` to execute the test suite. Ensure all tests pass before merging changes.
- **Debugging**: Utilize browser developer tools to inspect elements and debug JavaScript. Console logs are used extensively for tracking application state.

## Project Conventions
- **File Naming**: Use kebab-case for file names (e.g., `product-list.js`).
- **Component Structure**: Each component should have its own directory within the `Routing/` folder, containing its HTML, CSS, and JavaScript files.

## Integration Points
- **API Communication**: The application communicates with external APIs for product data and user authentication. Check the `api.js` file in the `assets/` directory for integration details.
- **State Management**: Use a centralized state management approach to handle data flow between components. Refer to the `store.js` file for implementation details.

## Examples of Patterns
- **Component Communication**: Components communicate via props and events. For example, the `ProductCard` component emits an event when a product is added to the cart.
- **Styling**: CSS is organized in a modular fashion, with styles scoped to individual components to avoid conflicts.

## Conclusion
These instructions should help AI agents understand the structure and workflows of the E-Commerce project. For any unclear sections, please provide feedback for further refinement.