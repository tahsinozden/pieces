# pieces
A vote application which enables users to create voting events and as well as enable others to vote for items inside an event.



## How to Run the Project
### Front-End
`npm` and `grunt-cli` have be installed in your system for front-end part of the application.
Then `node_modues.zip` needs to be placed under the path `pieces-frontend` folder.
Under the path `pieces-frontend`, the following command `grunt serve` should be run to server the frontend part of the application.
The application will be run under the following address `http://localhost:9000`.

### Back-End
`pieces-backend` folder can be imported into an Eclipse IDE as a maven project. Then with the following running configuration, the application can be run. `spring-boot:run -e -X`.
The application will be run on the following address `http://localhost:8080`

#### Note
The vote table links provided by the application just after creating of a vote table will be available under the address `http://localhost:8080/all-votes/<table_id>`



