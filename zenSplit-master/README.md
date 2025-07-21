# zenSplit - Group Expense Tracker

zenSplit is a web application to keep track of individual and group expenses, making it easy to split bills and settle up among friends or groups. Built with Next.js, React, MongoDB, and Tailwind CSS.

## Features

- Add, view, and delete expenses for a group
- Add and remove friends from the group
- Automatic calculation of each member's balance (who owes whom and how much)
- Settlement suggestions to simplify payments
- Responsive and modern UI
- Persistent storage using MongoDB

## Tech Stack

- **Frontend:** Next.js (App Router), React, Tailwind CSS, React Icons
- **Backend:** Next.js API routes
- **Database:** MongoDB

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn
- MongoDB database (local or cloud, e.g., MongoDB Atlas)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/zenSplit.git
   cd zenSplit/zenSplit-master
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables:**
   - Create a `.env.local` file in the root directory.
   - Add your MongoDB connection string:
     ```
     MONGODB_URI=your_mongodb_connection_string
     MONGODB_DB=your_database_name
     ```

4. **Run the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- **Add Friends:** Use the form to add group members.
- **Add Expenses:** Click "Add Expense", fill in the details, and select who paid and who participated.
- **View Balances:** See how much each person owes or gets back.
- **Settle Up:** View suggested settlements to clear all debts.
- **Remove Friends:** Remove a friend and all their related expenses.

## Project Structure

- `src/app/` - Main application pages and layout
- `src/app/api/` - API routes for expenses and friends
- `src/lib/mongodb.js` - MongoDB connection helper
- `tailwind.config.js` - Tailwind CSS configuration

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Push to your fork and open a pull request

## License

This project is licensed under the MIT License.

## Contact

For questions or support, please open an issue in the repository.
