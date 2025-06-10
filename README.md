# Travel App AI

`travel-app` is a [Next.js](https://nextjs.org/) project that uses the AI SDK to dynamically generate and stream travel advice, leveraging OpenAI's GPT-4o model.

## Technologies

- Next.js 14
- React 18
- Tailwind CSS
- AI SDK: `@ai-sdk/openai` and `ai`
- Zod for schema validation

## Project Structure

```
travel-app/
├── public/               # Static assets (images, icons)
├── src/
│   └── app/
│       ├── api/          # API routes (Next.js App Router)
│       ├── actions.js    # Server-side function for UI streaming
│       ├── layout.js     # Default layout component
│       ├── page.js       # Main page with form to fetch the component
│       └── globals.css   # Global styles (Tailwind CSS)
├── next.config.mjs       # Next.js configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── package.json          # Dependencies and scripts
└── README.md             # Project documentation
```

## Prerequisites

- Node.js v14 or higher
- npm (or yarn)
- OpenAI API key

## Installation & Setup

1. Clone this repository:
   ```powershell
   git clone https://github.com/dropecosta/open-ai-react.git
   cd ai-react
   ```

2. Install dependencies:
   ```powershell
   npm install
   ```

3. Create a `.env.local` file in the root directory with your OpenAI API key:
   ```env
   OPENAI_API_KEY=your_api_key_here
   ```

## Available Scripts

- `npm run dev`   – Starts the development server
- `npm run build` – Builds the production assets
- `npm start`     – Runs the application in production mode
- `npm run lint`  – Runs the Next.js linter

## Usage

1. Start the development server:
   ```powershell
   npm run dev
   ```
2. Open [http://localhost:3000](http://localhost:3000) in your browser.
3. Click **Get Component** to receive streaming travel advice rendered as a React component.


## License

This project is licensed under the MIT License.

<br/><br/>


Developed with 🧡 by **Pedro Reis**  | 📧 dropecosta@gmail.com  | [LinkedIn](https://www.linkedin.com/in/dropecosta/) | [GitHub](https://github.com/dropecosta)
