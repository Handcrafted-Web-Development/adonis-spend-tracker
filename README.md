<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# AdonisJS Spend Tracker 📊 - Building a RESTful API for Expense Tracking using AdonisJS 👨🏼‍💻

_Read this README carefully before starting any operations !_ ✌️

## Prerequisites 👨🏼‍🏫

- [Node.js](https://nodejs.org/) (version 20 or higher)
- [NPM](https://www.npmjs.com/)
- [Adonis CLI](https://adonisjs.com/)
- [Git](https://git-scm.com/)
- [MySQL](https://www.mysql.com/) or another database management system

## Installation Steps

1. **Clone the Project**

Open a terminal and run the following command to clone the project from the Git repository :

   ```shell
   git clone https://github.com/Handcrafted-Web-Development/adonis-spend-tracker.git
   ```
  or
   ```shell
   git@github.com:Handcrafted-Web-Development/adonis-spend-tracker.git
   ```

2. **Install Dependencies**

Navigate to the project directory and execute the following command to install dependencies :

   ```shell
   npm install
   ```

3. **Configure the Environment**

Duplicate the .env.example file and rename it to .env :

   ```shell
   cp .env.example .env
   ```
Open the .env file and configure the environment variables, such as the database connection (DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, DB_PASSWORD).

4. **Generate Application Key**

Run the following command to generate the application key :

   ```shell
   adonis key:generate
   ```

5. **Migrer la Base de Données**

Exécutez les migrations pour créer les tables de base de données :

   ```shell
   php artisan migrate
   ```

6. **Run Migrations**

Execute migrations to create the database tables :

   ```shell
   adonis migration:run
   ```

7. **Start the Server**

Run the following command to start the Adonis server :

   ```shell
   node ace serve --watch
   ```
Le site sera accessible à l'adresse http://127.0.0.1:3333 dans votre navigateur.

Happy coding ! 🚀
