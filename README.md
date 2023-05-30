# Tours

This is a project that involves creating three components: Tours, Tour, and Loading. The Tours component is responsible for rendering a list of Tour components. The data for the tours is fetched from a URL using the fetch API. Before the data is loaded, a loading spinner or message is displayed using the Loading component.

### Components

#### Tours

The Tours component renders a list of Tour components based on the fetched data. It manages the state of the tours data and handles the "remove tour" functionality.

#### Tour

The Tour component represents an individual tour. It receives the tour data as props and renders the tour's image, info, name, and price. It also includes buttons for the "remove tour" and "read more" functionalities.

#### Loading

The Loading component displays a loading spinner while the data is being fetched.

### Implementation

To run the project, follow these steps:

1. Clone the repository to your local machine.
1. Navigate to the project directory.
1. Install the necessary dependencies by running the following command: `npm install`

- Also you can check the project at this URL https://abdabhasan-tours.netlify.app
- Figma URL [Tours](https://www.figma.com/file/OnLoM3AzBFaHzSc2iolJS0/Tours?node-id=0%3A1&t=wiRXOlTLN5ehekYI-1)

### Conclusion

This project demonstrates the creation of React components for rendering tours data, implementing functionalities like removing a tour, expanding the description, and re-fetching the data. Feel free to customize and enhance the project according to your specific requirements.
