<div align="center">
<img width="1200" height="475" alt="Hanif Studio Banner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Hanif Studio

Full-stack Product Engineer portfolio. Jakarta-based developer building products end to end with AI integration.

## Tech Stack

- **Framework:** Next.js 15
- **Language:** TypeScript
- **Styling:** Tailwind CSS 4
- **UI:** React 19, Lucide Icons
- **Font:** Geist
- **Scheduling:** Cal.com Embed

## Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hanif-studio.git
   cd hanif-studio
   ```

2. Install dependencies:

   ```bash
   pnpm install
   # or
   npm install
   ```

3. Set up environment variables:

   ```bash
   cp .env.example .env.local
   ```

   Edit `.env.local` with your values:
   - `NEXT_PUBLIC_BASE_URL` — Your application URL (`http://localhost:3000` for dev)
   - `GEMINI_API_KEY` — Your Gemini API key from [Google AI Studio](https://ai.google.dev/)

4. Run the development server:

   ```bash
   pnpm dev
   # or
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Environment Variables

| Variable               | Description                                      | Required |
| ---------------------- | ------------------------------------------------ | -------- |
| `NEXT_PUBLIC_BASE_URL` | Base URL for SEO metadata                        | Yes      |
| `GEMINI_API_KEY`       | Gemini API key for AI features (server-side)     | Yes      |

## Build for Production

```bash
pnpm build
pnpm start
```

## Project Structure

```
hanif-studio/
├── app/              # Next.js App Router pages
├── components/       # React components
├── lib/              # Utility functions
├── public/           # Static assets
└── types.ts          # TypeScript type definitions
```

## License

MIT
