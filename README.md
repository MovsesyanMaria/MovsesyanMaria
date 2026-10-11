# 🚀 Maria Movsesyan — AI Automation Engineer & Vibe Coding Specialist

*(Հայերեն տարբերակը կարդալու համար իջեք ներքև)*

## 🇬🇧 English Description

Welcome to my portfolio! Here are my practical and learning projects developed while mastering modern technologies, web development, no-code/AI flow programming, and business process automation.

---

### 🛠 Tech Stack & Tools
* **AI-Assisted Web Dev & Prototyping:** Bolt.new, Lovable, Next.js (App Router), React, TypeScript, Tailwind CSS, shadcn/ui, Supabase, Vercel
* **Business Automation & No-Code:** Make.com (Integromat), Webhooks, Data Store, Make AI Agents, Google Sheets + Apps Script
* **Scripting & AI Integration:** Python (Pandas, Requests, Playwright, Aiogram 3.x), OpenAI Vision / GPT-4o, Gemini (function calling), Groq
* **LLM & RAG:** Hugging Face Transformers, Ollama, Gemma 2, BAAI/bge-m3 embeddings, FAISS, Gradio
* **Payments & Integrations:** Stripe Checkout, Telegram Bot API (webhooks)
* **Version Control:** Git, GitHub, Claude Code

---

### 💼 Practical Projects & Case Studies

#### 1. 🌐 Dr. Varazdat Avetisyan — AI & Academic Portfolio Web Platform
A modern multilingual web platform for presenting academic and technological projects, prototyped and built with modern AI-driven tools.
* **Stack:** Bolt.new, Lovable, Next.js, Tailwind CSS (Bento Grid), Supabase (Database & Storage), Vercel.
* **Key Features:** Responsive design, 3-language support (EN, AM, RU), Supabase integration for media storage and feedback collection.

#### 2. 📚 Telegram IT Bookshop Automation Bot
An interactive Telegram bot for automating online book sales.
* **Stack:** Telegram Bot API, Make.com, Google Sheets, Make Data Store.
* **Key Features:** Dynamic product catalog from a spreadsheet, smart shopping cart with session tracking (`chat_id`) via Data Store, automatic price calculation and order logging.

#### 3. 🤖 List.am Telegram Search Bot
An asynchronous bot for automated data scraping and searching on Armenia's largest classifieds platform.
* **Stack:** Python 3.10+, Aiogram 3.x, Playwright (Chromium), BeautifulSoup4.
* **Key Features:** Dynamic URL generation for real estate and transport searches, semantic parameter extraction (NLU), anti-bot bypass via Playwright and User-Agent rotation.

#### 4. 💳 Automated Payment Receipt Verification & Accounting System
An intelligent workflow for automated tuition payment receipt verification.
* **Stack:** Make.com, Telegram Bot API, OpenAI Vision / Make AI Agent, Google Drive, Google Sheets.
* **Key Features:** Receipt processing via Vision AI, flexible student record matching in spreadsheets regardless of name order, automatic monthly folder creation in Google Drive, and dynamic `=HYPERLINK` formula insertion into Google Sheets.

#### 5. 🕯️ Aroma Lights — E-commerce Store with Telegram Bot & AI Assistant
A full-featured online store of scented candles and diffusers: website, Telegram bot with an AI consultant, and a Google Sheet that works as the owner's control panel.
* **Live:** [aromalight.vercel.app](https://aromalight.vercel.app) · [@AromaLightStore_bot](https://t.me/AromaLightStore_bot)
* **Stack:** Next.js 13.5 (App Router), TypeScript, Tailwind, shadcn/ui, Supabase (Postgres, RLS, Storage), Stripe Checkout, Telegram Bot API, Gemini (function calling) with Groq fallback, Google Sheets + Apps Script, Vercel + Vercel Cron.
* **Key Features:**
  * One AI agent serving two channels (website and bot): product recommendations, adding to cart and checkout right from the chat.
  * Owner mode in the bot: a read-only AI analyst that answers questions on real sales and review data.
  * Manager workflow: order statuses with customer notifications, daily report at 21:00, low-stock alerts, AI review moderation (sentiment, spam filtering).
  * AI product creation from a photo and a few words: names, descriptions and SEO in 3 languages (AM, RU, EN).
  * Two-way Google Sheets ↔ database sync: prices, stock, restock, promo codes, automatic translation of empty cells.
  * Reliable money and stock logic in Postgres (`SECURITY DEFINER` functions, row locking — the last item can't be sold twice), card payments with auto-cancel of unpaid orders, promo codes.

#### 6. ⚖️ Armenian Labor Code AI Assistant (RAG)
A question-answering system that answers questions about the Labor Code of the Republic of Armenia in Armenian and cites the article the answer comes from.
* **Stack:** Python, `pypdf`, BAAI/bge-m3 embeddings, FAISS / NumPy, Gemma 2 9B (4-bit, bitsandbytes), Hugging Face, Ollama, Gradio.
* **Key Features:**
  * RAG pipeline: text extraction, splitting by «Հոդված N» (article) headings, vector search (cosine similarity) of the top 5 articles, answer generation based on the found articles.
  * Two versions: **Google Colab** (free T4 GPU, Hugging Face models) and **fully local** on Windows via Ollama — no internet or token needed, data never leaves the computer.
  * Embedding cache, streaming answers, web interface for uploading the code and asking questions.
  * Documented troubleshooting guide for common errors (tokens, GPU memory, PDF encoding, Gemma float16 instability).

---
---

## 🇦🇲 Հայերեն Նկարագրություն

Բարի գալուստ իմ պորտֆոլիո! Այստեղ ներկայացված են իմ գործնական և ուսումնական նախագծերը, որոնք մշակվել են ժամանակակից տեխնոլոգիաների, վեբ մշակման, AI/no-code հարթակների և բիզնես գործընթացների ավտոմատացման միջոցով:

---

### 🛠 Տեխնոլոգիական Կույտ (Tech Stack)
* **AI-Աջակցությամբ Վեբ Մշակում & Պրոտոտիպավորում:** Bolt.new, Lovable, Next.js (App Router), React, TypeScript, Tailwind CSS, shadcn/ui, Supabase, Vercel
* **Բիզնես Ավտոմատացում & No-Code:** Make.com (Integromat), Webhooks, Data Store, Make AI Agents, Google Sheets + Apps Script
* **Սկրիպտավորում & AI Ինտեգրացիա:** Python (Pandas, Requests, Playwright, Aiogram 3.x), OpenAI Vision / GPT-4o, Gemini (function calling), Groq
* **LLM & RAG:** Hugging Face Transformers, Ollama, Gemma 2, BAAI/bge-m3 էմբեդինգներ, FAISS, Gradio
* **Վճարումներ & Ինտեգրացիաներ:** Stripe Checkout, Telegram Bot API (webhooks)
* **Կառավարման Գործիքներ:** Git, GitHub, Claude Code

---

### 💼 Գործնական Նախագծեր և Քեյսեր

#### 1. 🌐 Dr. Varazdat Avetisyan — AI & Academic Portfolio Web Platform
Ժամանակակից բազմալեզու վեբ հարթակ՝ ակադեմիական և տեխնոլոգիական նախագծերի ներկայացման համար, ստեղծված ժամանակակից AI գործիքների և պլատֆորմների միջոցով։
* **Տեխնոլոգիաներ:** Bolt.new, Lovable, Next.js, Tailwind CSS (Bento Grid), Supabase (Database & Storage), Vercel.
* **Հիմնական Հնարավորություններ:** Ադապտիվ դիզայն, եռալեզու աջակցություն (EN, AM, RU), Supabase ինտեգրացիա մեդիա ֆայլերի պահպանման և հետադարձ կապի համար։

#### 2. 📚 Telegram IT Bookshop Automation Bot
Ինտերակտիվ Telegram բոտ՝ առցանց գրքերի վաճառքի ավտոմատացման համար։
* **Տեխնոլոգիաներ:** Telegram Bot API, Make.com, Google Sheets, Make Data Store.
* **Հիմնական Հնարավորություններ:** Ապրանքների դինամիկ կատալոգ աղյուսակից, խելացի զամբյուղ՝ սեսիաների պահպանմամբ (`chat_id`) Data Store-ի միջոցով, գումարի ավտոմատ հաշվարկ և պատվերների գրանցում։

#### 3. 🤖 List.am Telegram Որոնման Բոտ (Telegram Search Bot)
Ասինխրոն բոտ Հայաստանի խոշորագույն հարթակից տվյալների ավտոմատացված հավաքագրման և որոնման համար։
* **Տեխնոլոգիաներ:** Python 3.10+, Aiogram 3.x, Playwright (Chromium), BeautifulSoup4.
* **Հիմնական Հնարավորություններ:** URL-ների դինամիկ գեներացում անշարժ գույքի և տրանսպորտի որոնման համար, պարամետրերի իմաստային վերլուծություն (NLU), արգելափակումների շրջանցում Playwright-ի և User-Agent-ների ռոտացիայի միջոցով։

#### 4. 💳 Automated Payment Receipt Verification & Accounting System
Ինտելեկտուալ համակարգ՝ ուսման վարձի վճարման անդորրագրերի ավտոմատ ստուգման համար։
* **Տեխնոլոգիաներ:** Make.com, Telegram Bot API, OpenAI Vision / Make AI Agent, Google Drive, Google Sheets.
* **Հիմնական Հնարավորություններ:** Չեկերի ճանաչում Vision AI-ի միջոցով, ուսանողների տվյալների ճկուն որոնում աղյուսակում՝ անկախ անվան հերթականությունից, Google Drive-ում ամսական թղթապանակների ավտոմատ ստեղծում և Google Sheets-ում `=HYPERLINK` բանաձևերի տեղադրում։

#### 5. 🕯️ Aroma Lights — Առցանց խանութ Telegram-բոտով և AI խորհրդատուով
Բուրավետ մոմերի և դիֆուզորների լիարժեք առցանց խանութ՝ կայք, Telegram-բոտ AI խորհրդատուով և Google Sheets աղյուսակ՝ որպես սեփականատիրոջ կառավարման վահանակ։
* **Հղումներ:** [aromalight.vercel.app](https://aromalight.vercel.app) · [@AromaLightStore_bot](https://t.me/AromaLightStore_bot)
* **Տեխնոլոգիաներ:** Next.js 13.5 (App Router), TypeScript, Tailwind, shadcn/ui, Supabase (Postgres, RLS, Storage), Stripe Checkout, Telegram Bot API, Gemini (function calling)՝ Groq պահեստային մատակարարով, Google Sheets + Apps Script, Vercel + Vercel Cron։
* **Հիմնական Հնարավորություններ:**
  * Մեկ AI գործակալ՝ երկու ալիքի համար (կայք և բոտ)․ ապրանքների առաջարկ, զամբյուղի լրացում և պատվերի ձևակերպում անմիջապես զրույցից։
  * Սեփականատիրոջ ռեժիմ բոտում․ AI վերլուծաբան, որը պատասխանում է վաճառքների և կարծիքների իրական տվյալներով և միայն կարդում է։
  * Մենեջերի աշխատանքային հոսք․ պատվերների կարգավիճակներ՝ գնորդին ծանուցումներով, օրական հաշվետվություն ժամը 21:00-ին, սպառվող ապրանքների զգուշացումներ, կարծիքների AI մոդերացիա (տոնայնություն, սպամի զտում)։
  * Ապրանքի ստեղծում AI-ով՝ լուսանկարից և մի քանի բառից․ անվանումներ, նկարագրություններ և SEO տեքստեր 3 լեզվով (AM, RU, EN)։
  * Google Sheets ↔ տվյալների բազա երկկողմանի համաժամեցում․ գներ, մնացորդներ, մուտք, պրոմոկոդեր, դատարկ վանդակների ավտոմատ թարգմանություն։
  * Գումարների և մնացորդների հուսալի տրամաբանություն Postgres-ում (`SECURITY DEFINER` ֆունկցիաներ, տողերի կողպում՝ վերջին ապրանքը չի կարող երկու անգամ վաճառվել), քարտով վճարում՝ չվճարված պատվերների ավտոմատ չեղարկմամբ, պրոմոկոդեր։

#### 6. ⚖️ ՀՀ Աշխատանքային օրենսգրքի AI օգնական (RAG)
Հարց-պատասխան համակարգ, որը պատասխանում է ՀՀ Աշխատանքային օրենսգրքի վերաբերյալ հարցերին հայերենով և նշում է այն հոդվածը, որից վերցված է պատասխանը։
* **Տեխնոլոգիաներ:** Python, `pypdf`, BAAI/bge-m3 էմբեդինգներ, FAISS / NumPy, Gemma 2 9B (4-bit, bitsandbytes), Hugging Face, Ollama, Gradio։
* **Հիմնական Հնարավորություններ:**
  * RAG հոսք․ տեքստի արտահանում, բաժանում ըստ «Հոդված N» վերնագրերի, ամենամոտ 5 հոդվածի վեկտորային որոնում (cosine similarity), պատասխանի գեներացում գտնված հոդվածների հիման վրա։
  * Երկու տարբերակ․ **Google Colab** (անվճար T4 GPU, Hugging Face մոդելներ) և **ամբողջովին լոկալ** Windows-ում՝ Ollama-ի միջոցով, առանց ինտերնետի և token-ի, տվյալները չեն լքում համակարգիչը։
  * Էմբեդինգների քեշ, պատասխանի աստիճանական ցուցադրում (streaming), վեբ ինտերֆեյս՝ օրենսգիրքը բեռնելու և հարց տալու համար։
  * Հաճախ հանդիպող սխալների և դրանց լուծումների փաստաթղթավորված ուղեցույց (token-ներ, GPU հիշողություն, PDF կոդավորում, Gemma-ի float16 անկայունություն)։

---
*Created with a focus on efficiency, architecture cleanliness, and practical value.*
