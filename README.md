![image](https://github.com/samueldharma/Code-Assistant/assets/132459662/f749c8b5-3a66-4ba2-a207-463831e36c91)<a href="https://chat.vercel.ai/">
  <h1 align="center">Code Assistant Chatbot</h1>
</a>

<p align="center">
  An open-source AI chatbot app template built with Next.js, the Vercel AI SDK, OpenAI, and Vercel KV.
</p>

<br/>


## Running locally (DO NOT FOLLOW THIS, FOLLOW THE STEP AFTER THIS)

You will need to use the environment variables [defined in `.env.example`](.env.example) to run Next.js AI Chatbot. It's recommended you use [Vercel Environment Variables](https://vercel.com/docs/projects/environment-variables) for this, but a `.env` file is all that is necessary.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various OpenAI and authentication provider accounts.

1. Install Vercel CLI: `npm i -g vercel`
2. Link local instance with Vercel and GitHub accounts (creates `.vercel` directory): `vercel link`
3. Download your environment variables: `vercel env pull`

```bash
pnpm install
pnpm dev
```

## How to run the code, follow the steps below
```bash
npm i
npm i -g vercel
npm run dev
```
Your app template should now be running on [localhost:3000](http://localhost:3000/).

## After cloning, there will be an error "missing secret ..." , do as i mention below

ID: Bikin file baru namanya ".env" di dalam /ui lalu didalam file nya paste text yang gw kirim di grup line

ENG: Create an ".env" file in /ui and paste the text i sent in the line group starting with this "# You must first activate a Billing Account here: https://platform.openai.com/account/billing/overview"

