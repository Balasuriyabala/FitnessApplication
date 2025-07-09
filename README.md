# FitnessApplication 

Front-end are client = npm install , npm start

IF YOU GET UNCAUGHT RUNTIME ERROR
WHILE INTERGRATING front-end and backend code two important steps need to done

1. Check with these steps front-end folder
const API = axios.create({
  baseURL: "",
});

2. Check with .env file in backend code 
it look like: 
PORT=7000
MONGODB_URL=mongodb://ip:27017/fitness
JWT=devops-secret-key
 
