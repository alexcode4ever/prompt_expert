## About the project

A simple project to store AI prompts using Next.js 13. 
Example: 
https://prompt-expert-sigma.vercel.app/

![pe](https://github.com/alexcode4ever/prompt_expert/assets/122391735/a6a842f7-605b-41ec-af33-e90d33a3f44a)


- Next.js 13 new app folder structure
- TailwindCSS
- Mongoose


### Installation
To get started, just clone the repository

```
git clone https://github.com/alexcode4ever/prompt_expert.git
```

Then, create a .env file with below parameters

```
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=
GOOGLE_ID=
GOOGLE_CLIENT_SECRET=
MONGODB_URI=
```
Enter the `GOOGLE_ID`, `GOOGLE_CLIENT_SECRET` and `MONGODB_URI` for Next Auth and MongoDB connection

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

<!-- ROADMAP -->
## Roadmap

- [ ] Add prompt preview
- [ ] Add tag auto completion


