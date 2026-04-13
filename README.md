# Bug Blaster

A React-based bug tracking application that helps teams manage and prioritize software issues efficiently.

## Features

- **Create Tickets**: Add new bug reports with title, description, and priority level
- **Edit Tickets**: Modify existing tickets to update information or status
- **Priority Sorting**: Sort tickets by priority (High to Low or Low to High)
- **Ticket Management**: View all tickets in an organized list format
- **Responsive Design**: Clean, user-friendly interface that works on different screen sizes

## Prerequisites

Before running this project, make sure you have the following installed:

- **Node.js** (version 14 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn**

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd bug-blaster
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

To start the development server:

```bash
npm start
```

This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) in your browser to view it.

The page will automatically reload when you make changes to the code.

## Building for Production

To build the app for production:

```bash
npm run build
```

This creates a `build` folder with optimized production files that can be deployed to a web server.

## Testing

To run the test suite:

```bash
npm test
```

This launches the test runner in interactive watch mode.

## Project Structure

```
src/
├── components/
│   ├── TicketForm.js      # Form for creating/editing tickets
│   ├── TicketItem.js      # Individual ticket display component
│   └── TicketList.js      # List container for all tickets
├── reducers/
│   └── ticketReducer.js   # State management for tickets
├── utilities/
│   └── sortingUtilities.js # Helper functions for sorting tickets
├── App.js                 # Main application component
├── App.css                # Application styles
├── styles.css             # Additional styling
└── index.js               # Application entry point
```

## Technologies Used

- **React** - Frontend framework
- **React Hooks** (useReducer) - State management
- **CSS** - Styling
- **Create React App** - Build tooling
- **Testing Library** - Testing utilities

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is private and proprietary.
