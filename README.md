# Parking Lot Management  

## About 

Parking lot manager (PLM) is a web application that oversees UBC parking spaces, allowing existing users to create parking sessions, view analytics and update their vehicle and personal information. Our application is an inventory tracker that features a parking log, a record of both vacant and occupied parking spaces, and updates instantaneously to ensure individuals are able to gain insight of the usage of the parking spots. Moreover, our application contains a history page, in which users are able to view parking history, ticket history and summary, and have the ability to select the information they wish to view. 

## Commands 

- Starting postgreSQL(mac): brew services start postgresql 
- Accessing postgreSQL: psql -U postgres -d postgres 
- Rebuild database: psql -U postgres -d postgres -f ./sql_scripts/rebuild_db.sql 
- Run server: yarn dev 
- Run client: yarn start
