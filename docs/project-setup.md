# ⚙️ Setup

### ✅ Prerequisites

- [Node Version Manager (nvm)](https://github.com/nvm-sh/nvm) installed
- Git installed
- A terminal with access to the project root

### 📦 Installation

1. **Install the Node.js version**

   ```bash
   nvm install
   ```

   This installs the version declared in `.nvmrc`.

2. **Set the default Node.js version (optional)**

   ```bash
   nvm alias default lts/*
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Run the development server**

   ```bash
   npm run dev
   ```

5. **Open the app in your browser**

   Use [http://localhost:3000](http://localhost:3000) or the port shown in your terminal output.

### 📝 Available Scripts (Mock)

- `npm run dev` - Starts the development server
- `npm run build` - Creates a production build
- `npm run start` - Runs the production server
- `npm run lint` - Runs linting checks
- `npm run lint:check` - Checks formatting rules
- `npm run lint:fix` - Applies formatting fixes

### 🧩 Notes for Template Usage

- Replace script descriptions with real behavior from `package.json`
- Update the default URL/port if your app uses a different value
- Add project-specific prerequisites if needed (for example, Docker, PostgreSQL, or Redis)
