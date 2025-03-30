# Trademark Search Application

This project is a React-based web application that allows users to search for trademarks and view detailed information about them. It's designed to provide an intuitive interface for exploring trademark data, including status, owners, law firms, and attorneys associated with each trademark.

## Features

- Search for trademarks using keywords
- View trademark details including name, company, serial number, filing date, status, and classes
- Filter trademarks by status (All, Live/Registered, Pending, Abandoned, Others)
- Switch between grid and list view for search results
- Filter results by owners, law firms, and attorneys
- Sort results by various criteria
- Responsive design for both desktop and mobile devices

## Technologies Used

- React.js
- Next.js (App Router)
- Tailwind CSS (via shadcn/ui components)
- Lucide React for icons

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/trademark-search.git
   cd trademark-search
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Project Structure

- `app/`: Contains the main application components and pages
- `components/`: Reusable React components
- `styles/`: CSS files for styling components
- `public/`: Static assets like images

## Main Components

- `App.js`: The root component that renders the Navbar and SearchResult components
- `Navbar.js`: The navigation bar component
- `SearchResult.js`: The main component for displaying search results and filters

## API Integration

This application integrates with a trademark search API. The API endpoint is:

```
https://vit-tm-task.api.trademarkia.app/api/v3/us
```

The application sends POST requests to this endpoint with search parameters to retrieve trademark data.

## Deployment

This application can be easily deployed on Vercel or any other platform that supports Next.js applications. Make sure to set up any necessary environment variables for API keys or other configuration.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
