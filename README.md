![logo](https://github.com/user-attachments/assets/1f74760e-ac03-46fc-a5bf-ac38123f033a) 
# Event Planning Web Application

**EVENTR** is a web-based multiuser platform for collaboratively planning dining events. Users vote on locations and times, and the system automatically selects the most popular options. It was developed as a project in the Software Architecture course at the University of Innsbruck.

## Features

- **Role-Based Access**:
  - **User**: Participate in events, vote, manage personal events.
  - **Manager**: All user permissions + manage restaurants.
  - **Admin**: All manager permissions + manage users and tags.
 
## Sample Users for different Roles
| Role(s)        	 | Username 	        | Password 	  |
|------------------|-------------------|-------------|
| ADMIN          	 | _alexandra_        	 | _123456_   	 |
| MANAGER          	 | _manager_        	 | _123456_   	 |
| USER          	 | _test_user_    	       | _pass_   	 |

- **Voting System**:
  - Create events and invite participants.
  - Vote on preferred locations and times.
  - System calculates and selects the winning option.

- **Notification Service**:
  - Email alerts about new events and voting results.

- **Security & Access**:
  - Encrypted password storage.
  - Restricted access based on user roles.

## Technologies

- Java 17
- Spring Boot (MVC, Security, Scheduling, etc.)
- Jakarta Faces (JSF) with PrimeFaces for UI
- JPA (Hibernate) for persistence
- H2 In-Memory Database (development)
- JUnit 5 for testing
- Maven 3.6+
- IntelliJ IDEA (recommended)

### Running Locally

```bash
mvn spring-boot:run
```

## Views

**-> Login page**
<img width="956" alt="login" src="https://github.com/user-attachments/assets/c7162903-78f1-4e1b-9a4e-73c29bd6ac27" />


**-> Home page**
<img width="941" alt="home" src="https://github.com/user-attachments/assets/8c4a67ce-32d9-4381-a7e1-9b733dfb81b9" />

**-> Local-search page**
<img width="940" alt="search" src="https://github.com/user-attachments/assets/d93faa3a-d1f5-482d-896d-49883418441d" />
<img width="933" alt="search2" src="https://github.com/user-attachments/assets/8696b832-ea56-44c2-bcac-3f45abaa7831" />

**-> Voting**
<img width="943" alt="vote" src="https://github.com/user-attachments/assets/8b45af98-ad1e-4fa1-ad8e-ce36628cf2b9" />

**-> Events/History**
<img width="935" alt="last" src="https://github.com/user-attachments/assets/0f1d195a-fbf9-492c-a8c4-7360fa525897" />

**-> Manage Pages**
<img width="165" alt="manage" src="https://github.com/user-attachments/assets/17eaabbc-bfaa-49c9-95ce-e33713e0f26d" />

*-> Manage Restaurants Page*
<img width="941" alt="manageres" src="https://github.com/user-attachments/assets/a21c2efb-8eb4-4db3-80bc-fcafde0c7593" />

*-> Manage Users Page*
<img width="940" alt="manageUse" src="https://github.com/user-attachments/assets/dc695e61-0540-4f8a-976c-40141782e6a9" />

*-> Manage Tags Page*
<img width="947" alt="manageTag" src="https://github.com/user-attachments/assets/013ec79d-9c02-4ad0-9c36-f20f8196440b" />






