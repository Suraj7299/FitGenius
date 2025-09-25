# 💪 FitGenius – AI-Powered Fitness & Nutrition Assistant

**FitGenius** is your all-in-one **AI fitness companion**, designed to provide **personalized workout plans**, **custom diet programs**, and a **voice-powered fitness assistant**. With real-time program generation and AI-driven insights, FitGenius helps you stay consistent and achieve your fitness goals with ease.  

---

## ✨ Highlights

- 🚀 **Tech Stack:** Next.js, React, TailwindCSS, Shadcn UI  
- 🎙️ **Voice AI Assistant (Vapi)**  
- 🧠 **LLM Integration (Gemini AI)**  
- 🏋️ **Personalized Workout Plans**  
- 🥗 **Custom Diet Programs**  
- 🔒 **Authentication & Authorization (Clerk)**  
- 💾 **Database (Convex)**  
- 🎬 **Real-time Program Generation**  
- 💻 **Modern Layouts**  
- 🎭 **Client & Server Components**  

---

## ⚡ Features

🤖 **Smart AI Assistant** – Engage in natural conversations about your goals, preferences, and physical condition.  

🏋️ **Workout Personalization** – Receive exercise routines tailored to your fitness level, injuries, and objectives.  

🥗 **Diet Recommendations** – AI-generated diet plans considering allergies and dietary preferences.  

🔐 **User Authentication** – Secure sign-in with GitHub, Google, or Email/Password (via Clerk).  

📂 **Program Management** – Create and manage multiple fitness programs (latest one stays active).  

📱 **Responsive UI** – Sleek and modern design optimized for all devices.  

---

## 🛠 Tech Stack

- **Frontend:** Next.js, React, TailwindCSS, shadcn/ui  
- **AI & Voice:** Gemini AI (LLM), Vapi (Voice Assistant)  
- **Authentication:** Clerk  
- **Database:** Convex (real-time)  
- **Deployment:** Vercel  

---

## ⚙️ Installation & Setup

Follow these steps to set up **FitGenius** locally:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/FitGenius.git
cd FitGenius

# 2️⃣ Install dependencies
npm install

# 3️⃣ Create a .env.local file in the root with the following content:
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=your_vapi_workflow_id
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key

# Convex Database
CONVEX_DEPLOYMENT=your_convex_deployment
NEXT_PUBLIC_CONVEX_URL=your_convex_url

# 4️⃣ Run the development server
npm run dev

Now open your browser and navigate to:
http://localhost:3000
