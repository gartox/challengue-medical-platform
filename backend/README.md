# README

## Prerequisites
- Docker
- Node.js and npm

## Instructions

### Step 1: Start PostgreSQL with Docker
Run the following command to start a PostgreSQL container with Docker:
```
docker run --name easepractice  -e POSTGRES_USER=easepractice -e POSTGRES_PASSWORD=test123 -e POSTGRES_DB=dbeasepractice -p 5432:5432  -d postgres
```

### Step 2: Install Dependencies
Install the required Node.js dependencies by running:
```
npm install
```

### Step 3: Push Database Structure with Prisma
Use Prisma to push the database structure:
```
npx prisma db push
```

### Step 4: Start the Application
Finally, start the application with the following command:
```
npm start
```
