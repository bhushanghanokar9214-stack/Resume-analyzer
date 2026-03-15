# AI Resume Analyzer

## Steps to run

1. Install dependencies:
   npm install

2. Add OpenAI API key:
   Create a `.env` file in root with:
   OPENAI_API_KEY=your_openai_api_key_here

3. Run locally:
   npm run dev

4. Deploy to Vercel:
   - Connect GitHub repo
   - Vercel auto-detects serverless function in api/analyze.js
   - Set OPENAI_API_KEY in Vercel Environment Variables
