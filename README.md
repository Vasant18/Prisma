# Prisma Handson

## Project Description
Prisma Handson is a practice and hands-on repository designed to help developers understand and explore Prisma ORM, TypeScript, and PostgreSQL. This project provides examples and exercises to deepen your understanding of database interactions and schema management using Prisma.

---

## Tech Stack
- **TypeScript**: Strongly typed programming language that builds on JavaScript.
- **Prisma ORM**: Modern database toolkit for TypeScript and Node.js.
- **PostgreSQL**: Open-source relational database system.

---

## Installation Instructions

### Prerequisites
Ensure you have the following installed on your system:
- **Node.js** (v16 or higher)
- **npm**
- **PostgreSQL** (with a running instance and proper user permissions)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/prisma-handson.git
   cd prisma-handson
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your environment variables:
   - Create a `.env` file in the root directory.
   - Add the following configuration (update with your PostgreSQL credentials):
     ```env
     DATABASE_URL=postgresql://<username>:<password>@<host>:<port>/<database>
     ```

4. Generate Prisma client:
   ```bash
   npx prisma generate
   ```

5. Apply migrations to set up the database:
   ```bash
   npx prisma migrate dev --name init
   ```

---

## Usage Instructions

### Running the Project
1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser or API testing tool to interact with the application.

### Prisma Commands
- Open the Prisma Studio:
  ```bash
  npx prisma studio
  ```
- Run database migrations:
  ```bash
  npx prisma migrate dev --name <migration-name>
  ```
- Reset the database:
  ```bash
  npx prisma migrate reset
  ```

---

## Contribution Guidelines
We welcome contributions! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature/fix:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push the changes:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request to the main repository.

---

## License Information
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

