# CS208 Lab 12.03

- Name: Summer Radkiewicz
- GitHub: [https://github.com/summerradkiewicz] (https://github.com/summerradkiewicz)
- Term: Spring 2026

## Project Description

This is built on from base code for a to-do list website that allows the user
to add and delete their own tasks, which persists through sessions. This
project adds the ability to edit task descriptions and mark them as complete/incomplete.

## Install the Database

To set up the database, run the `install_db.sh` script in the setup_scripts
directory. This script will install MariaDB and start the server running. You
only need to run this script once per Codespace.

```bash
./setup_scripts/install_db.sh
```

## Create the Database Tables

Create the initial tables by running the following command:

```bash
sudo mysql -u root -p < ./setup_scripts/create_demo_table.sql
```

## Install Dependencies

Install the required dependencies using npm:

```bash
npm install
```

## Run the Application

Start the application using the following command:

```bash
npm start
```

## Access the Application

On Codespaces, you can access the application by forwarding port 3000. Open the
forwarded port in your browser to view the application.