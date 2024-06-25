
# StockMarket App Project

This is a simple trading app built using Node.js, Express, and Handlebars. The app fetches and displays stock data using the IEX Cloud API.

## Features

- **Real-time Stock Data**: Fetches and displays live stock prices.
- **Stock Search**: Allows users to search for specific stocks by ticker symbol.
- **Handlebars Templating**: Uses Handlebars for rendering dynamic web pages.
- **Static Content**: Serves static files such as CSS and images.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Templating Engine**: Handlebars
- **API**: IEX Cloud API
- **Middleware**: body-parser
- **Styling**: CSS (served from the static folder)

## Installation

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js
- npm (Node package manager)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/Hezekiahpilli/stockmarketapp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd trading-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your API key:

   ```env
   IEX_API_KEY=pk_09830c677b0a461ba19d24bce404155e
   ```

5. Start the server:

   ```bash
   npm start
   ```

6. Open your browser and go to `http://localhost:5000` to view the app.

## Usage

- **Home Page**: Displays stock information for a default stock (e.g., Facebook).
- **Search Stock**: Enter the ticker symbol of the stock you want to search for in the search bar and submit.
- **About Page**: Provides information about the application.

## Project Structure

- `app.js`: Main server file where the Express app is configured.
- `views/`: Directory containing Handlebars templates.
  - `layouts/`: Main layout template.
  - `home.handlebars`: Template for the home page.
  - `about.handlebars`: Template for the about page.
- `model/`: Directory for static files (CSS, images, etc.).
- `.env`: Environment file for storing API keys and other sensitive information.

## Contributing

We welcome contributions to improve the app! Here are a few ways you can help:

- Report bugs and issues
- Suggest new features
- Submit pull requests to improve the codebase

To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [IEX Cloud](https://iexcloud.io/) for providing the stock data API.

## Contact

If you have any questions or feedback, feel free to reach out to us:

- **Email**: hezekiahpilli95@gmail.com
- **GitHub**:(https://github.com/Hezekiahpilli)

---

Thank you for using the StockMarket App! We hope it helps you stay informed about the stock market. Happy investing!
