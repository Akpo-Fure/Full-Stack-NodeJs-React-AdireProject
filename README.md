# Full-Stack-NodeJs-React-AdireProject

Adire is a full stack web application built using ReactJs for the frontend and NodeJs for the backend, This applicaon enables tailors to create customers, manage customers, add and manage orders for these customers. The frontend was deployed to Vercel and setup using React Vite.js and made use of react-query in conjuction with axios to make requests and handle errors, TypeScript was heavily used for type safety and detection of errors in run-time, made use of react google-oauth for google single sign up, The backend was deployed to Render and built using NodeJs, ExpressJs, TypeScript and MongoDB and made use of tools like cloudinary for image uploads and jwt for authentication and authorization Attached is the link to the fully deployed app which produces a seamless user exprience https://adire1.vercel.app/.

## Features

- User signup and authentication using manual signup and Google Oauth 2.0
- CICD pipeline was setup using Github actions to automate the test, build and deployment process
- Backend deployment using Render
- Frontend deployment using Vercel
- Customer and Order CRUD
- Tailors could generate and download receipts using pdfKit
- implemented cloudinary for image uploads
- Protected routes for authorized access

## Getting Started

Follow these steps to set up and run the project on your local machine.

1. Clone the repository:

```bash
git clone [https://github.com/Akpo-Fure/Node-Js-Task-Manager.git](https://github.com/Akpo-Fure/Full-Stack-NodeJs-React-AdireProject.git)
```

2. Change directory to Adire-NodeJs-Backend
```
cd Adire-NodeJs-Backend
RUN yarn
RUn yarn build
RUn yarn dev
```

3. Change directory to Adire-NodeJs-Frontend
```
cd Adire-NodeJs-Backend
RUN yarn
RUn yarn build
RUn yarn dev
```

4. Set up environmental variables in .env file 

5. Visit Adire for full user experience
```
Checkout https://adire1.vercel.app/ for a full user experience
