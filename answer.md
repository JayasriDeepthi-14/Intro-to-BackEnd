# Q1. Role of Frontend (FE)

Frontend is the part of a web application that users directly see and interact with. It focuses on presenting information in a clear visual form and providing smooth interaction experience.

### User Interface:
The frontend designs the visible screens such as buttons, forms, text, images, and navigation menus. Technologies like HTML, CSS, Tailwind, and React help create attractive and responsive layouts that fit different devices.

### User Interaction:
All actions performed by the user—clicking a button, typing in input box, selecting checkbox, or switching tabs—are handled by the frontend using JavaScript and React Hooks. It gives immediate feedback so the application feels alive.

### Communication with Backend:
Frontend sends user requests to backend through HTTP/HTTPS using fetch or Axios (inside services). It receives processed data and displays it in components without exposing server complexity to the user.

# Q2. Role of Backend (BE)

Backend works behind the scenes on the server and manages core processing of the application.

### Server-side Processing:
It executes programs that generate dynamic responses, validate user data, and perform calculations. Node.js or other languages run here continuously.

### Database Handling:
Backend connects to databases like MySQL, MongoDB, or Firebase Firestore to store and retrieve information. All CRUD operations are coordinated by this layer.

### Security and Authentication:
User credentials are verified in backend. It protects private routes, creates tokens/sessions, and blocks unauthorized access, ensuring data privacy and integrity.

# Q3. Business Logic

Business Logic is the set of rules that define how the application should behave according to organization needs. It stands between UI and database.

## Real–World Examples

### E-commerce Discount Rule:
If cart total is more than ₹2000, apply 10% discount; for new users give extra 5%. This calculation is pure business decision coded in application layer.

### Banking App Transfer Limit:
User cannot send more than ₹50,000 per day without KYC. The logic checks previous transactions before approving.

### Todo App Ownership:
Each authenticated user should view only their own todos and not others’. The filtering rule belongs to business logic.

# Q4. Client–Server Model

Client–Server Model is an architecture where two main entities cooperate to deliver services.

### Who is the Client:
Client is the user device or browser that requests information—React application running on Vite is a client.

### Who is the Server:
Server is a remote computer that processes client request and sends response. Firebase / Node APIs act as servers.

### How Communication Happens:
Client sends request via internet using protocols like HTTP. Server reads the URL, performs business logic, accesses database, and returns JSON. Frontend renders it to human readable form.

# Q5. Three-Tier Architecture

3-Tier Architecture divides web application into three independent layers.

### Presentation Layer:
Contains UI built with React + Tailwind + shadcn/ui. It handles layout and user events only.

### Application Layer:
Implements rules like validation, calculations, protected route checks using Context API and service abstraction.

### Data Layer:
Firestore database stores todos and user details permanently.

### Why This Architecture Used

1. Easy maintenance
2. Scalability
3. Reusability
4. Better security
5. Parallel development.

# Q6. JavaScript as a Backend Language

JavaScript is used in backend mainly through Node.js runtime.

### Performance:
Node.js uses non-blocking event loop which handles many requests with low memory, giving high speed for real-time apps.

### Ecosystem:
Huge npm library support for Firebase, authentication, email services, file handling, and APIs makes development fast.

### Popular Frameworks

1. Express.js
2. Nest.js
3. Koa.js
Fastify.

JavaScript enables same language in frontend and backend, reducing learning curve and improving productivity.
