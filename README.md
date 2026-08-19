# Fluidmind
<div align="center">
    <strong>Fluidmind</strong> is fluid note-taking for wandering minds - capture exploration first.
</div>

<div align="center">

[![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/-TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Dexie.js](https://img.shields.io/badge/-Dexie.js-%238B5CF6.svg?style=flat-square&logo=dexie&logoColor=white)](https://dexie.org/)
[![Zustand](https://img.shields.io/badge/-Zustand-%2344332D.svg?style=flat-square&logo=react&logoColor=white)](https://zustand-demo.pmnd.rs/)
[![Supabase](https://img.shields.io/badge/-Supabase-%233ECF8E.svg?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/)
[![Figma](https://img.shields.io/badge/-Figma-%23F24E1E.svg?style=flat-square&logo=figma&logoColor=white)](https://figma.com/)

</div>

## Features

## Getting Started
| **Step** | **Purpose** | **Instructions** |
|---|---|---|
| Git + GitHub Setup | Source code access | • Ensure Git is installed ([download](https://git-scm.com/install/windows) based on OS)<br>• Clone this GitHub repository using an IDE (e.g. Visual Studio Code)<br>&nbsp;&nbsp;&nbsp;&nbsp;• Click "Code" (green button) > HTTPS > copy the link<br>• Run `git clone "https://github.com/allison-pham/fluidmind"` |
| Installation | Local development | • Run `npm install -g supabase && npm install @supabase/supabase-js dexie nanoid zustand` |
| Environment variables | API keys | • Create a `.env` file and add it to `.gitignore` using `.env*`<br>• Add all environment variables to `.env` |
| Database (Supabase) | Store information | • Open [Supabase](http://supabase.com)<br>• Store info in `.env` file and Vercel:<br>`NEXT_PUBLIC_SUPABASE_URL`<br>`NEXT_PUBLIC_SUPABASE_ANON_KEY` |
| Run locally (frontend) | Local development | • Open up terminal: `npm run dev`<br>• Open http://localhost:3000 |