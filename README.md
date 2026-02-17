# VidyaGuide AI

Agentic AI Platform for Students - Career guidance, resume evaluation, skill recommendations, and learning roadmaps.

## Features

1. **Resume Evaluation** - ATS score, improvements, missing skills, formatting tips
2. **Career Guidance** - Personalized career paths based on degree, interests, goals
3. **Skill Recommendations** - Identify skill gaps and recommend top skills
4. **Learning Roadmap** - Step-by-step learning plan with courses, YouTube, projects
5. **Save Roadmaps** - Store and track your learning roadmaps (requires MongoDB)

## Setup

### 1. Install dependencies

```bash
npm install
```

### 2. Environment variables

Create `.env.local` in the project root:

```env
OPENAI_API_KEY=sk-your-openai-api-key
MONGODB_URI=mongodb+srv://user:pass@cluster.mongodb.net/vidyaguide
```

- **OPENAI_API_KEY** (required for AI): Get from [platform.openai.com](https://platform.openai.com/api-keys)
- **MONGODB_URI** (optional): For saving roadmaps and profiles. Get free cluster at [mongodb.com/atlas](https://www.mongodb.com/cloud/atlas)

### 3. Run development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Tech Stack

- **Frontend**: Next.js 14, React, Tailwind CSS
- **Backend**: Next.js API Routes
- **AI**: OpenAI GPT-4o-mini
- **Database**: MongoDB (optional)
