# Insights Copilot UI

A modern, React-based frontend for the Insights Copilot – enabling natural language querying and interactive data visualizations powered by AI.

## 🌟 Features

- 💬 Conversational UI powered by AI agents  
- 📊 Interactive charts and dashboards  
- ⚡ Seamless integration with [CopilotKit](https://github.com/CopilotKit)  
- 🎨 Styled with Tailwind CSS  
- 🔌 Connects to a Hugging Face-hosted backend for instant setup  

## 🛠️ Tech Stack

- **Next.js + React**  
- **Tailwind CSS**  
- **Recharts**  
- **CopilotKit**  
- **TypeScript**

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/arthikrangan/insights-copilot-ui.git
cd insights-copilot-ui/frontend
```

### 2. Configure Environment Variables

Create a `.env.local` file in the `frontend` directory:

```env
NEXT_PUBLIC_API_URL=https://arthikrangan-text-to-sql-agent-api.hf.space
SERVER_API_URL=https://arthikrangan-text-to-sql-agent-api.hf.space
OPENAI_API_KEY=your_openai_api_key_here
```

> You can generate an OpenAI API key from [platform.openai.com](https://platform.openai.com/account/api-keys)

### 3. Install Dependencies

```bash
pnpm install
```

> If you don't have `pnpm`, install it globally:  
> `npm install -g pnpm`

### 4. Start the App

```bash
pnpm run dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

## 📦 Build for Production

To build the app for production:

```bash
pnpm run build
pnpm start
```

## 📄 License

This project is licensed under the MIT License. See [LICENSE](../LICENSE) for details.
