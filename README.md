# API Hunter

API Hunter is a web application that leverages Hunter's API to find and verify professional email addresses associated with a given domain. This tool simplifies the process of discovering contact information, making it invaluable for professionals engaged in outreach and networking activities.

## Features

- **Domain Search**: Retrieve all email addresses found for a specific domain, along with sources and confidence scores.
- **Email Finder**: Generate the most likely email address based on a person's name and domain.
- **Email Verifier**: Validate the deliverability of an email address to ensure its accuracy.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (version 6 or higher)
- A [Hunter API key](https://hunter.io/api) citeturn0search0

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Saloni2433/api-hunter.git
   cd api-hunter
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory and add your Hunter API key:

   ```env
   VITE_HUNTER_API_KEY=your_hunter_api_key
   ```

### Running the Application

To start the development server:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:3000` to access the application.

## Usage

1. **Domain Search**:

   - Enter a domain name (e.g., `example.com`) in the search bar.
   - Click "Search" to retrieve associated email addresses.

2. **Email Finder**:

   - Navigate to the "Email Finder" section.
   - Input the first name, last name, and domain of the person you're searching for.
   - Click "Find Email" to generate the most likely email address.

3. **Email Verifier**:

   - Go to the "Email Verifier" section.
   - Enter the email address you wish to verify.
   - Click "Verify" to check its deliverability.

## Built With

- [Vite](https://vitejs.dev/): Next Generation Frontend Tooling
- [React](https://reactjs.org/): A JavaScript library for building user interfaces
- [Hunter API](https://hunter.io/api): Powerful tools for finding and verifying professional email addresses citeturn0search0

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Hunter](https://hunter.io/) for providing a robust API for email discovery and verification.
