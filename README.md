## Installation

Install the project dependencies using npm:
```bash
npm install
```
## Set Up Environment Variables

Create a new file named .env.local in the root of your project and paste the following content:
```
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=

NEXT_PUBLIC_API_ENDPOINT=
NEXT_PUBLIC_PROD_API_ENDPOINT=

DATABASE_URL=

UPSTASH_REDIS_URL=
UPSTASH_REDIS_TOKEN=

AUTH_SECRET=

QSTASH_URL=
QSTASH_TOKEN=

RESEND_TOKEN=
```
Obtain these credentials by signing up on the ImageKit, NeonDB, Upstash, and Resend and Replace the placeholder values . 

## Running the Project
```
npm run dev
```
Open http://localhost:3000 in your browser to view the project.
