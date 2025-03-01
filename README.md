Topic 2: Components and Styling by Alexander Andersen
This repository contains three React-based tasks focusing on component creation and styling using Vite and CSS Modules. The goal is to practice building reusable UI components and applying modular styles in a clean, maintainable way.

Overview
Task 1: Social Media Profile
Displays user information such as name, tag, location, and activity stats. The data is imported from a JSON file and passed as props to the <Profile> component.

Task 2: Friend List
Renders a list of friends using the <FriendList> component. Each friend is represented by the <FriendListItem> component, showing avatar, name, and online/offline status. Data is also sourced from a JSON file.

Task 3: Transaction History
Implements a <TransactionHistory> component that renders a table of transactions (type, amount, currency). Each transaction is displayed as a table row, with data loaded from a JSON file.

Tech Stack
React for building UI components
Vite for fast development and bundling
CSS Modules for scoped, modular styling
JSON data files to keep the App component clean and focused on rendering
Project Structure
src/
├─ components/
│  ├─ Profile/
│  ├─ FriendList/
│  ├─ FriendListItem/
│  └─ TransactionHistory/
├─ data/
│  ├─ userData.json
│  ├─ friends.json
│  └─ transactions.json
├─ App.jsx
├─ main.jsx
└─ index.css

Each component has its own folder with a .jsx file and a corresponding .module.css file.
JSON files store data for each task (user, friends, transactions), which are imported into App.jsx.
Installation and Setup
Clone the repository:

bash
Copiază
git clone https://github.com/your-username/goit-neo-react-hw-module1.git
Install dependencies:

bash
Copiază
cd goit-neo-react-hw-module1
npm install
Start development server:

bash
Copiază
npm run dev
Open http://localhost:5173 (default Vite port) in your browser.

Build for production:

bash
Copiază
npm run build
Then preview the production build:

bash
Copiază
npm run preview
Usage
Open the app in your browser to view the three tasks on a single page:

Task 1: Social Media Profile
Task 2: Friend List
Task 3: Transaction History
Each section is displayed with centered layout and modular CSS styling.

Contributing
Feel free to submit pull requests or open issues if you have suggestions for improvements or encounter any problems.

License
This project is released under the MIT License, so you can use it for any purpose with attribution.

Enjoy customizing and building upon these components for your own React projects!
