📦 Info Project

Name: aralia-web

Version: 0.0.0

Bundler: pakai Vite (modern & cepat).

Language: TypeScript (vue-tsc ada di script → pakai Vue + TS).

Jadi bukan React/Next.js, tapi Vue 3 + TypeScript 🎯

🔨 Scripts Penting

dev → jalanin project (pakai Vite).

build:* → build untuk berbagai environment (localhost, development, staging, production).

lint → ESLint + auto fix.

prettier → format kode.

prepare → setup Husky (git hooks).

danger:ci → integrasi dengan Danger.js buat lint/report di CI/CD.

👉 Good practice: project ini udah siap CI/CD + lint/formatting otomatis.

📚 Dependencies (Utama)

Vue 3 ecosystem

@vueuse/core → kumpulan composable Vue.

pinia → state management (replacement Vuex).

@tanstack/vue-table → table management (powerful, mirip react-table).

@vee-validate/zod → form validation pakai Zod.

Styling / UI

@tailwindcss/typography, @tailwindcss/aspect-ratio → plugin Tailwind.

class-variance-authority, clsx → class management (dipakai shadcn/ui pattern).

lucide-vue-next → icon library (versi Vue dari Lucide, sama kayak shadcn di React).

Utility

dayjs → date utils.

axios → HTTP client.

js-cookie → cookie management.

🧪 Dev Dependencies

@vitejs/plugin-vue → integrasi Vue ke Vite.

@vue/test-utils, vitest (via eslint plugin) → buat unit testing Vue.

eslint + prettier → linting & formatting.

@originjs/vite-plugin-federation → kemungkinan micro-frontend support.

🎯 Insight

Ini project Vue 3 + Vite + TypeScript + Pinia + Tailwind + Lucide (shadcn style).

Jadi beneran ada inspirasi shadcn/ui tapi versi Vue (karena shadcn asli untuk React). Mereka pakai pattern sama (CVA, clsx, lucide, tailwind).

Codebase ini sudah modern & rapi (CI/CD, lint, prettier, husky).

Ada setup testing (@vue/test-utils + Vitest), tinggal dicek apakah udah dipakai.
