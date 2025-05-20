## 🌍 TripMate – AI Travel Itinerary Generator

An AI-powered travel planner built with **Streamlit**, **LangChain**, and **Hugging Face Transformers** that helps you generate a personalized, day-by-day travel itinerary based on your destination, interests, budget, and season. Perfect for travelers looking for instant, intelligent, and editable trip plans!

---

## 🚀 Features

* 🧳 Input your travel details: destination, days, interests, budget, and preferred season
* 🗺️ Generates a fully detailed, AI-crafted travel itinerary using natural language processing
* ✍️ Provides an editable text box so you can customize your itinerary
* 📥 Download your itinerary as a `.txt` file for offline use
* 🤗 Uses **Flan-T5** via Hugging Face Transformers
* 🧠 Enhanced with **LangChain** for modular LLM workflows
* 🔐 API keys managed securely via `.env` configuration

---

## 🛠️ Technologies Used

* `Streamlit` – UI framework for interactive web apps
* `Hugging Face Transformers` – Text generation using `google/flan-t5-small`
* `LangChain` – LLM chaining framework for flexible AI flows
* `python-dotenv` – For loading secure API keys from `.env` file

---

## 💡 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/tripmate-ai-planner.git
cd tripmate-ai-planner
```

### 2. Create your `.env` file with Hugging Face token

```env
HUGGINGFACE_API_KEY=your-huggingface-token-here
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
streamlit run tripmate_ai_app.py
```

---

## 📌 Notes

* The app uses `google/flan-t5-small` for fast, budget-friendly text generation
* LangChain makes it easy to scale or switch models later
* Future enhancements may include Google Maps integration or hotel recommendations

---

Built by **Mayusha Athukorala**
BSc in Applied Data Science Communication | KDU
