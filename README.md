# Savings Forecaster

A client-side savings forecaster built with Next.js, TypeScript, and Tailwind CSS. This application allows you to input incomes, expenses, interest rates, and optional tax scenarios to generate an interactive, day-by-day projection of your future savings. All data is processed locally in your browser, requiring no backend server.

## Features Roadmap

- **Client-Side Calculation**: All forecasting logic runs in the browser, ensuring quick feedback.
- **Multiple Income & Expense Streams**: Add recurring or one-off items to reflect your real financial situation.
- **Interest & Tax Scenarios**: Apply annual interest with daily compounding, and optionally factor in tax withholding.
- **Interactive Visualization**: View your balance evolution over time with dynamic charts and tables.
- **Data Export/Import**: Easily export your scenario for backup and import it later to continue where you left off.
- **Modern UI/UX**: Built with Next.js and Tailwind CSS for a sleek, responsive interface.

## Getting Started

1. **Clone the Repository**:
   	```bash
	git clone https://github.com/<YourUsername>/savings-forecaster.git
	cd savings-forecaster
	```

2. **Install Dependencies:**
	```bash
	npm install
	```

3. **Run the Development Server:**
	```bash
	npm run dev
	```
	Open http://localhost:3000 in your browser to view the app.

## Building for Production
	```bash
	npm run build
	npm start
	```
	Then, access http://localhost:3000 to use the production build.

## License
This project is released under the MIT License.