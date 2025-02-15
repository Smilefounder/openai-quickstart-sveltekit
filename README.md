# OpenAI API Quickstart - SvelteKit example

This is an example pet name generator app used in the OpenAI API. It uses the [SvelteKit](https://kit.svelte.dev/) framework with [Pico](https://picocss.com/). Check out the tutorial or follow the instructions below to get set up.

## Setup

1. If you don’t have Node.js installed, [install it from here](https://nodejs.org/en/) (Node.js version >= 14.6.0 required)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd openai-quickstart-sveltekit
   ```

4. Install the requirements

   ```bash
   $ npm install
   ```

5. Make a copy of the example environment variables file

   On Linux systems: 
   ```bash
   $ cp .env.example .env
   ```
   On Windows:
   ```powershell
   $ copy .env.example .env
   ```
6. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

7. Run the app

   ```bash
   $ npm run dev
   ```

You should now be able to access the app at [http://127.0.0.1:5173](http://127.0.0.1:5173)! For the full context for other examples, check out the [tutorial](https://beta.openai.com/docs/quickstart).