🤖 AI Content Generator
## Description
A powerful and intuitive AI Content Generator built using Next.js, ShadCN UI, and PostgreSQL, with seamless integrations for Razorpay and Clerk. This application empowers users to generate high-quality content, manage subscriptions, and securely authenticate, all within a beautifully designed interface.


## 🚀 Getting Started
1. Clone the Repository
Start by cloning the repository:
git clone https://github.com/your-username/ai-content-generator.git  
cd ai-content-generator  

2. Install Dependencies
Run the following command to install the required dependencies: npm install  

3. Set Up the Database
Initialize and migrate the PostgreSQL database: npx prisma migrate dev  

4. Start the Application
Run the development server: npm run dev  
Visit the application at http://localhost:3000.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

DATABASE_URL=your_postgres_database_url  
NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_api_key  
CLERK_API_KEY=your_clerk_api_key  
RAZORPAY_KEY_ID=your_razorpay_key_id  
RAZORPAY_KEY_SECRET=your_razorpay_key_secret  



## Features

- Authentication
Secure, seamless authentication powered by Clerk.
- Content Generation
Generate high-quality AI-driven content with minimal effort.
- Payment Integration
Integrated with Razorpay to handle subscriptions and payments.
- User-Friendly Interface
Intuitive and responsive design built with ShadCN UI for an exceptional user experience.
- Database Management
PostgreSQL ensures data reliability and scalability.


## Tech Stack
    
**Next.js**	Framework for building SSR and static apps.
**ShadCN UI**	Elegant UI components for modern design.
**PostgreSQL**	Relational database for data management.
**Razorpay**	Payment gateway for subscriptions.
**Clerk**	User authentication and session management.

## Acknowledgements

- Next.js for providing an incredible development experience.
- ShadCN UI for its modern and intuitive components.
- Clerk for making authentication effortless.
- Razorpay for reliable payment handling.
PostgreSQL for robust database management.

