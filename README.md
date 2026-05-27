MIAUYUDA
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Miauyuda, is the final project of Ironhack's bootcamp, was developed in collaboration with Patricia Lago and Oscar Gomez. Is a SPA (Single Page Application) that connects pets with veterinarians to provide 24/7 online assistance.

Technologies used

Frontend: React, Bootstrap

Backend: Express, Node.js, MongoDB


# final-project-server


 Base URL/auth
| HTTP Method | URI PAth | Description       |
|-------------|----------|-------------------|
| POST        | /signup  | Signup  user      |
| POST        | /login   | Login user        |
| GET         | /verify  | Verify auth token |
 
 
 Base URL/professionals
| HTTP Method | URI path                | Description                       |
|-------------|-------------------------|-----------------------------------|
| GET         | /                       | All professionals list            |
| POST        | /newProfessional        | Create new professional           |
| GET         | /:professionalId        | Matching ID professional details  |
| PUT         | /:professionalId        | Matching ID professional edition  |
| DELETE      | /:professionalId        | Matching ID professional deletion |


Base URL/clients
| HTTP Method | URI path          | Description                 |
|-------------|-------------------|-----------------------------|
| POST        | /newClient        | Create new client           |
| GET         |/:clientId         | Matching ID client details  |
| PUT         |/:clientId         | Matching ID client edit     |
| DELETE      |/:clientId         | Matching ID client deletion |


BaseURL/requests
| HTTP Method | URI path           | Description                 |
|-------------|--------------------|-----------------------------|
| GET         | /                  | All requests list           |
| POST        | /newRequest        | Create new request          |
| GET         | /:requestId        | Matching ID request details |
| PUT         | /:requestId        | Matching ID request edit    |
| DELETE      | /:requestId        | Matching ID client deletion |


BaseURL/pets
| HTTP Method | URI path       | Description              |
|-------------|----------------|--------------------------|
| GET         | /              | All pets list            |
| POST        | /newPet        | Create new pet           |
| GET         | /:petId        | Matching ID pet details  |
| PUT         | /:petId        | Matching ID pet edition  |
| DELETE      | /:petId        | Matching ID pet deletion |

## Team Members

**Patricia Lago Espino**  
- Github: [patriiilago](https://github.com/patriiilago)  
- LinkedIn: [Patricia Lago](https://www.linkedin.com/in/patri-lago)  

**Teresa Arranz Carrasco**  
- Github: [Tere1102](https://github.com/Tere1102)  
- LinkedIn: [Teresa Arranz Carrasco](https://www.linkedin.com/in/teresa-arranz-carrasco)  

**Oscar Gomez Diez**  
- Github: [OscarDev83](https://github.com/OscarDev83)  
- LinkedIn: [Óscar Gómez Díez](https://www.linkedin.com/in/%C3%B3scar-g%C3%B3mez-d%C3%AFez-b967202a/) 

## Deployment

**Client:** [https://miiauyuda.netlify.app/](https://miauyuda.netlify.app/)  
**Server:** [https://miauyuda.fly.dev/](https://miauyuda.fly.dev/)
