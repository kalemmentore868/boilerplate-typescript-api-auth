# Steps to run

Clone project onto your machine by running the git clone git_url .
Create a database eg. capstone_data
Seed the database by running the seed.sql file in the seed folder.
To do this, navgiate to the seed folder in your terminal and run the following command : psql -f seed.sql resort_app
Create a .env file
Ensure your .env file have the below environment variables :
SECRET_KEY - You can assign it value
PORT - You can assign it any value you want. Just remember your server will be listening on the PORT number you specify here!
DATABASE_HOST- The name of your dataabase host, which should be localhost
DATABASE_USERNAME - Your database username
DATABASE_PORT - The port postgresql is running on. The default is 5432
DATABASE_NAME- The name of the database you created eg. capstone_data
Run npm install
Start Your Server by running npm run dev
Import all of my endpoints into insomnia
Create a new Request Collection by clicking the create button and then selecting Request Collection. Then give your collection a new name.
To the top of Insomnia, you would see Insomnia/The Name Of Your New Collection, click the drop down arrow and then select Import/Export.
Click Import Data, then From File, then search for the import file. The file is located in the insomnia-imports of the back-end folder and it is called Insomnia.json.
Complete the import process.
Test your end points in Insomnia
