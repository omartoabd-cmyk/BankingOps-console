# BankOps Console frontend

The React and Material UI frontend provides customer and account tables, detail pages, and forms. Its Axios client sends requests to the Spring Boot API.

## Run locally

From `bank-backend`, start the API with `.\mvnw.cmd spring-boot:run`. In a second PowerShell terminal, run these commands from `bank-frontend`.

```powershell
npm.cmd ci
$env:REACT_APP_API_URL = 'http://localhost:8080/api/v1'
npm.cmd start
```

Open [http://localhost:3000](http://localhost:3000).
