# ChatGPT-API Demo

A demo repo based on [OpenAI GPT-3.5 Turbo API](https://platform.openai.com/docs/guides/chat).

## fork from

[ddiu8081/chatgpt-demo](https://github.com/ddiu8081/chatgpt-demo)

## Run Locally

1. Setup & Install dependencies

    > First, you need [Node.js](https://nodejs.org/) installed.

    ```shell
    npm i
    ```

2. Make a copy of `.env.example`, then rename it to `.env`
3. Add your [OpenAI API key](https://platform.openai.com/account/api-keys) to `.env`
    ```
    OPENAI_API_KEY=sk-xxx...
    ```
4. Basic Auth to `.env`
    ```
    BASIC_AUTH=admin:123456
    ```
5. Run the app
    ```shell
    npm run dev
    ```

## Deploy With Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmeesii%2Fchatgpt-demo%26env%3DOPENAI_API_KEY%26env%3DBASIC_AUTH%26envDescription%3DOpenAI%20API%20Key%26envLink%3Dhttps%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys)

## License

MIT
