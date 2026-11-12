🚀 Maria Movsesyan — AI Automation Engineer & Vibe Coding Specialist
(Հայերեն տարբերակը կարդալու համար իջեք ներքև)
🇬🇧 English Description
Welcome to my portfolio! Here are my practical and learning projects developed while mastering modern technologies, web development, no-code/AI flow programming, and business process automation.
🛠 Tech Stack & Tools
AI-Assisted Web Dev & Prototyping: Bolt.new, Lovable, Next.js (App Router), React, React Native (Expo), TypeScript, Tailwind CSS, shadcn/ui, Supabase (incl. Edge Functions), Vercel
Business Automation & No-Code: Make.com (Integromat), Webhooks, Data Store, Make AI Agents, Google Sheets + Apps Script
Scripting & AI Integration: Python (Pandas, Requests, Playwright, Aiogram 3.x), OpenAI Vision / GPT-4o, Gemini (function calling), Groq
LLM & RAG: Hugging Face Transformers, Ollama, Gemma 2, BAAI/bge-m3 embeddings, FAISS, Gradio
Payments & Integrations: Stripe Checkout, Telegram Bot API (webhooks)
Version Control: Git, GitHub, Claude Code
💼 Practical Projects & Case Studies
1. 🌐 Dr. Varazdat Avetisyan — AI & Academic Portfolio Web Platform
A modern multilingual web platform for presenting academic and technological projects, prototyped and built with modern AI-driven tools.
Stack: Bolt.new, Lovable, Next.js, Tailwind CSS (Bento Grid), Supabase (Database & Storage), Vercel.
Key Features: Responsive design, 3-language support (EN, AM, RU), Supabase integration for media storage and feedback collection.
2. 📚 Telegram IT Bookshop Automation Bot
An interactive Telegram bot for automating online book sales.
Stack: Telegram Bot API, Make.com, Google Sheets, Make Data Store.
Key Features: Dynamic product catalog from a spreadsheet, smart shopping cart with session tracking (chat_id) via Data Store, automatic price calculation and order logging.
3. 🤖 List.am Telegram Search Bot
An asynchronous bot for automated data scraping and searching on Armenia's largest classifieds platform.
Stack: Python 3.10+, Aiogram 3.x, Playwright (Chromium), BeautifulSoup4.
Key Features: Dynamic URL generation for real estate and transport searches, semantic parameter extraction (NLU), anti-bot bypass via Playwright and User-Agent rotation.
4. 💳 Automated Payment Receipt Verification & Accounting System
An intelligent workflow for automated tuition payment receipt verification.
Stack: Make.com, Telegram Bot API, OpenAI Vision / Make AI Agent, Google Drive, Google Sheets.
Key Features: Receipt processing via Vision AI, flexible student record matching in spreadsheets regardless of name order, automatic monthly folder creation in Google Drive, and dynamic =HYPERLINK formula insertion into Google Sheets.
5. 🕯️ Aroma Lights — E-commerce Store with Telegram Bot & AI Assistant
A full-featured online store of scented candles and diffusers: website, Telegram bot with an AI consultant, and a Google Sheet that works as the owner's control panel.
Live: aromalight.vercel.app · @AromaLightStore_bot
Stack: Next.js 13.5 (App Router), TypeScript, Tailwind, shadcn/ui, Supabase (Postgres, RLS, Storage), Stripe Checkout, Telegram Bot API, Gemini (function calling) with Groq fallback, Google Sheets + Apps Script, Vercel + Vercel Cron.
Key Features:
One AI agent serving two channels (website and bot): product recommendations, adding to cart and checkout right from the chat.
Owner mode in the bot: a read-only AI analyst that answers questions on real sales and review data.
Manager workflow: order statuses with customer notifications, daily report at 21:00, low-stock alerts, AI review moderation (sentiment, spam filtering).
AI product creation from a photo and a few words: names, descriptions and SEO in 3 languages (AM, RU, EN).
Two-way Google Sheets ↔ database sync: prices, stock, restock, promo codes, automatic translation of empty cells.
Reliable money and stock logic in Postgres (SECURITY DEFINER functions, row locking — the last item can't be sold twice), card payments with auto-cancel of unpaid orders, promo codes.
6. ⚖️ Armenian Labor Code AI Assistant (RAG)
A question-answering system that answers questions about the Labor Code of the Republic of Armenia in Armenian and cites the article the answer comes from.
Stack: Python, pypdf, BAAI/bge-m3 embeddings, FAISS / NumPy, Gemma 2 9B (4-bit, bitsandbytes), Hugging Face, Ollama, Gradio.
Key Features:
RAG pipeline: text extraction, splitting by «Հոդված N» (article) headings, vector search (cosine similarity) of the top 5 articles, answer generation based on the found articles.
Two versions: Google Colab (free T4 GPU, Hugging Face models) and fully local on Windows via Ollama — no internet or token needed, data never leaves the computer.
Embedding cache, streaming answers, web interface for uploading the code and asking questions.
Documented troubleshooting guide for common errors (tokens, GPU memory, PDF encoding, Gemma float16 instability).
7. 💸 FinTracker AI — Personal & Business Expense Tracker (AI agent)
A mobile app and Telegram bot where an AI agent turns a receipt photo, a voice note, pasted text or a bank screenshot into a verified expense record, with personal/business tagging, projects, day closing and reports. Course project, UI in Armenian, Russian and English.
Stack: Expo SDK 58, React Native, TypeScript, Expo Router, zustand, i18next; Supabase (Auth, Postgres + RLS, private Storage, Edge Functions, pg_cron, Vault); Gemini 3.5 / 3.8 Flash with Cloudflare Llama 4 Scout fallback; Telegram Bot API.
Key Features:
Agentic parsing pipeline: the app never calls the AI directly; Edge Functions check the plan and quota, call an LLM router (three Gemini models, then Cloudflare), validate the result and return an editable draft that the user confirms.
Resilience: per-model timeouts, automatic failover on 429/503/timeouts, one retry on invalid JSON, a manual-entry fallback, and a re-check on another model when confidence is low.
Accuracy layer: the line-item sum is the source of truth, the printed receipt total is stored separately, discounts and weighed goods are handled, mismatches are flagged to the user.
Per-user correction memory and two-step duplicate detection (same receipt, same purchase from another source).
The Telegram bot reuses the same parsers and database as the app.
Rules enforced on the server: RLS, a private receipts bucket, closed-day edit guard in the database, plan limits before LLM calls, automatic deletion of receipt photos after 1 year.
Quality: 12 automated test suites and 8 SQL checks; eval on real Armenian receipts: 7 of 8 receipts and 95 of 96 individual checks passed.
Built with an AI-agent workflow: I wrote the specs and verified every result on a phone and on real receipts, Claude Code implemented migrations, code and tests.
Repository: private, a code walkthrough is available on request.
🇦🇲 Հայերեն Նկարագրություն
Բարի գալուստ իմ պորտֆոլիո! Այստեղ ներկայացված են իմ գործնական և ուսումնական նախագծերը, որոնք մշակվել են ժամանակակից տեխնոլոգիաների, վեբ մշակման, AI/no-code հարթակների և բիզնես գործընթացների ավտոմատացման միջոցով:
🛠 Տեխնոլոգիական Կույտ (Tech Stack)
AI-Աջակցությամբ Վեբ Մշակում & Պրոտոտիպավորում: Bolt.new, Lovable, Next.js (App Router), React, React Native (Expo), TypeScript, Tailwind CSS, shadcn/ui, Supabase, Vercel
Բիզնես Ավտոմատացում & No-Code: Make.com (Integromat), Webhooks, Data Store, Make AI Agents, Google Sheets + Apps Script
Սկրիպտավորում & AI Ինտեգրացիա: Python (Pandas, Requests, Playwright, Aiogram 3.x), OpenAI Vision / GPT-4o, Gemini (function calling), Groq
LLM & RAG: Hugging Face Transformers, Ollama, Gemma 2, BAAI/bge-m3 էմբեդինգներ, FAISS, Gradio
Վճարումներ & Ինտեգրացիաներ: Stripe Checkout, Telegram Bot API (webhooks)
Կառավարման Գործիքներ: Git, GitHub, Claude Code
💼 Գործնական Նախագծեր և Քեյսեր
1. 🌐 Dr. Varazdat Avetisyan — AI & Academic Portfolio Web Platform
Ժամանակակից բազմալեզու վեբ հարթակ՝ ակադեմիական և տեխնոլոգիական նախագծերի ներկայացման համար, ստեղծված ժամանակակից AI գործիքների և պլատֆորմների միջոցով։
Տեխնոլոգիաներ: Bolt.new, Lovable, Next.js, Tailwind CSS (Bento Grid), Supabase (Database & Storage), Vercel.
Հիմնական Հնարավորություններ: Ադապտիվ դիզայն, եռալեզու աջակցություն (EN, AM, RU), Supabase ինտեգրացիա մեդիա ֆայլերի պահպանման և հետադարձ կապի համար։
2. 📚 Telegram IT Bookshop Automation Bot
Ինտերակտիվ Telegram բոտ՝ առցանց գրքերի վաճառքի ավտոմատացման համար։
Տեխնոլոգիաներ: Telegram Bot API, Make.com, Google Sheets, Make Data Store.
Հիմնական Հնարավորություններ: Ապրանքների դինամիկ կատալոգ աղյուսակից, խելացի զամբյուղ՝ սեսիաների պահպանմամբ (chat_id) Data Store-ի միջոցով, գումարի ավտոմատ հաշվարկ և պատվերների գրանցում։
3. 🤖 List.am Telegram Որոնման Բոտ (Telegram Search Bot)
Ասինխրոն բոտ Հայաստանի խոշորագույն հարթակից տվյալների ավտոմատացված հավաքագրման և որոնման համար։
Տեխնոլոգիաներ: Python 3.10+, Aiogram 3.x, Playwright (Chromium), BeautifulSoup4.
Հիմնական Հնարավորություններ: URL-ների դինամիկ գեներացում անշարժ գույքի և տրանսպորտի որոնման համար, պարամետրերի իմաստային վերլուծություն (NLU), արգելափակումների շրջանցում Playwright-ի և User-Agent-ների ռոտացիայի միջոցով։
4. 💳 Automated Payment Receipt Verification & Accounting System
Ինտելեկտուալ համակարգ՝ ուսման վարձի վճարման անդորրագրերի ավտոմատ ստուգման համար։
Տեխնոլոգիաներ: Make.com, Telegram Bot API, OpenAI Vision / Make AI Agent, Google Drive, Google Sheets.
Հիմնական Հնարավորություններ: Չեկերի ճանաչում Vision AI-ի միջոցով, ուսանողների տվյալների ճկուն որոնում աղյուսակում՝ անկախ անվան հերթականությունից, Google Drive-ում ամսական թղթապանակների ավտոմատ ստեղծում և Google Sheets-ում =HYPERLINK բանաձևերի տեղադրում։
5. 🕯️ Aroma Lights — Առցանց խանութ Telegram-բոտով և AI խորհրդատուով
Բուրավետ մոմերի և դիֆուզորների լիարժեք առցանց խանութ՝ կայք, Telegram-բոտ AI խորհրդատուով և Google Sheets աղյուսակ՝ որպես սեփականատիրոջ կառավարման վահանակ։
Հղումներ: aromalight.vercel.app · @AromaLightStore_bot
Տեխնոլոգիաներ: Next.js 13.5 (App Router), TypeScript, Tailwind, shadcn/ui, Supabase (Postgres, RLS, Storage), Stripe Checkout, Telegram Bot API, Gemini (function calling)՝ Groq պահեստային մատակարարով, Google Sheets + Apps Script, Vercel + Vercel Cron։
Հիմնական Հնարավորություններ:
Մեկ AI գործակալ՝ երկու ալիքի համար (կայք և բոտ)․ ապրանքների առաջարկ, զամբյուղի լրացում և պատվերի ձևակերպում անմիջապես զրույցից։
Սեփականատիրոջ ռեժիմ բոտում․ AI վերլուծաբան, որը պատասխանում է վաճառքների և կարծիքների իրական տվյալներով և միայն կարդում է։
Մենեջերի աշխատանքային հոսք․ պատվերների կարգավիճակներ՝ գնորդին ծանուցումներով, օրական հաշվետվություն ժամը 21:00-ին, սպառվող ապրանքների զգուշացումներ, կարծիքների AI մոդերացիա (տոնայնություն, սպամի զտում)։
Ապրանքի ստեղծում AI-ով՝ լուսանկարից և մի քանի բառից․ անվանումներ, նկարագրություններ և SEO տեքստեր 3 լեզվով (AM, RU, EN)։
Google Sheets ↔ տվյալների բազա երկկողմանի համաժամեցում․ գներ, մնացորդներ, մուտք, պրոմոկոդեր, դատարկ վանդակների ավտոմատ թարգմանություն։
Գումարների և մնացորդների հուսալի տրամաբանություն Postgres-ում (SECURITY DEFINER ֆունկցիաներ, տողերի կողպում՝ վերջին ապրանքը չի կարող երկու անգամ վաճառվել), քարտով վճարում՝ չվճարված պատվերների ավտոմատ չեղարկմամբ, պրոմոկոդեր։
6. ⚖️ ՀՀ Աշխատանքային օրենսգրքի AI օգնական (RAG)
Հարց-պատասխան համակարգ, որը պատասխանում է ՀՀ Աշխատանքային օրենսգրքի վերաբերյալ հարցերին հայերենով և նշում է այն հոդվածը, որից վերցված է պատասխանը։
Տեխնոլոգիաներ: Python, pypdf, BAAI/bge-m3 էմբեդինգներ, FAISS / NumPy, Gemma 2 9B (4-bit, bitsandbytes), Hugging Face, Ollama, Gradio։
Հիմնական Հնարավորություններ:
RAG հոսք․ տեքստի արտահանում, բաժանում ըստ «Հոդված N» վերնագրերի, ամենամոտ 5 հոդվածի վեկտորային որոնում (cosine similarity), պատասխանի գեներացում գտնված հոդվածների հիման վրա։
Երկու տարբերակ․ Google Colab (անվճար T4 GPU, Hugging Face մոդելներ) և ամբողջովին լոկալ Windows-ում՝ Ollama-ի միջոցով, առանց ինտերնետի և token-ի, տվյալները չեն լքում համակարգիչը։
Էմբեդինգների քեշ, պատասխանի աստիճանական ցուցադրում (streaming), վեբ ինտերֆեյս՝ օրենսգիրքը բեռնելու և հարց տալու համար։
Հաճախ հանդիպող սխալների և դրանց լուծումների փաստաթղթավորված ուղեցույց (token-ներ, GPU հիշողություն, PDF կոդավորում, Gemma-ի float16 անկայունություն)։
7. 💸 FinTracker AI — Անձնական և բիզնես ծախսերի հաշվառում (AI գործակալ)
Բջջային հավելված և Telegram բոտ, որտեղ AI գործակալը չեկի լուսանկարը, ձայնային հաղորդագրությունը, տեքստը կամ բանկի սքրինշոթը վերածում է ստուգված ծախսի գրառման՝ անձնական/բիզնես նշումով, նախագծերով, օրվա փակմամբ և հաշվետվություններով։ Ուսումնական նախագիծ, ինտերֆեյսը՝ հայերեն, ռուսերեն և անգլերեն։
Տեխնոլոգիաներ: Expo SDK 58, React Native, TypeScript, Expo Router, zustand, i18next; Supabase (Auth, Postgres + RLS, փակ Storage, Edge Functions, pg_cron, Vault); Gemini 3.5 / 3.8 Flash՝ Cloudflare Llama 4 Scout պահեստային մոդելով; Telegram Bot API։
Հիմնական Հնարավորություններ:
Գործակալային վերլուծության հոսք․ հավելվածը երբեք ուղիղ չի դիմում AI-ին. Edge Functions-ը ստուգում է պլանը և քվոտան, կանչում է LLM ուղղորդիչը (երեք Gemini մոդել, ապա Cloudflare), ստուգում է արդյունքը և վերադարձնում խմբագրելի սևագիր, որը օգտատերը հաստատում է։
Հուսալիություն․ մոդելների ժամանակային սահմաններ, ավտոմատ անցում 429/503/ժամանակի սպառման դեպքում, մեկ կրկնություն անվավեր JSON-ի դեպքում, ձեռքով մուտքի տարբերակ և կրկնակի ստուգում այլ մոդելով ցածր վստահության դեպքում։
Ճշգրտության շերտ․ տողերի գումարը ճշմարտության աղբյուրն է, չեկի տպված ընդհանուրը պահվում է առանձին, զեղչերն ու կշռվող ապրանքները հաշվվում են, անհամապատասխանությունը նշվում է օգտատիրոջը։
Օգտատիրոջ ուղղումների հիշողություն և կրկնակի գրանցման երկքայլ ստուգում (նույն չեկ, նույն գնումը այլ աղբյուրից)։
Telegram բոտը օգտագործում է նույն վերլուծիչները և նույն բազան, ինչ հավելվածը։
Սերվերում գործող կանոններ․ RLS, փակ bucket, փակված օրվա խմբագրման արգելք բազայում, պլանի սահմանաչափ LLM-ից առաջ, չեկերի լուսանկարների ավտոմատ ջնջում 1 տարի հետո։
Որակ․ 12 ավտոթեստային հավաքածու և 8 SQL ստուգում․ իրական հայկական չեկերի eval-ում 8 չեկից 7-ը և 96 առանձին ստուգումից 95-ը անցան։
Մշակում AI գործակալով․ ես գրել եմ տեխնիկական առաջադրանքները և ստուգել յուրաքանչյուր արդյունք հեռախոսով ու իրական չեկերով, իսկ Claude Code-ը իրականացրել է միգրացիաները, կոդը և թեստերը։
Պահոց: փակ է, կոդի ներկայացումը՝ ըստ հարցման։
