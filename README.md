# ucreate-projects
This is an Inventory management project to keep records of each project in company like thier Domain expiry data, Ssl Expiry date and DNS Records.

  ## About Project

- Language: PHP (7.0)
- Framework: Laravel ( 5.2 )
- Database: PostgreSql

## How to install project on local
  
    Open CLI and run following commands to set up at local:
   - **Clone the project**
        >
            git clone https://github.com/neemchand/ucreate-projects.git

   - **Set permissions**
       >
            sudo chmod -R 777 { project-storage-path }
            sudo chmod -R 777 { project-bootstrap-path }

   - **Go to project directory**
       >
            cd formspace-api        

 - **Install the dependencies**    
 >
           composer install
  


## Database installation
- **How to install postgresql ( Ubuntu )**
    >
        sudo apt-get install postgresql postgresql-contrib
- **Which UI being used to connect to DB**
    >
        pgadmin
- **Create  database**
    >
         1. login to pgsql
          sudo psql -h localhost -U postgres    
           2. create database measurematch;

## Post Installation steps
 - **Run database migrations**
    >
        php artisan migrate

- **Start server**
    >
        php artisan serve
        The API will be running on localhost:8000 
