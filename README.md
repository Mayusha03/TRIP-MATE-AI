<h1 align="center"> TripMate – AI Travel Itinerary Generator </h1>

<div align="center">
  <img height="200" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWcxNjVsZGZrYm1qc3B4emtiOXI1OXFrcW16czU5cGI3dGNmenllaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/jK35sw9qGlRYlgGBls/giphy.gif"  />
</div>
<br> 

<p align="justify"> An AI-powered travel planner built with <b></b>Streamlit, LangChain, and Hugging Face Transformers</b> that helps you generate a personalized, day-by-day travel itinerary based on your destination, interests, budget, and season.</p>

<p align="justify">Perfect for travelers looking for instant, intelligent, and editable trip plans! </p>

---

## 🚀 Features

* 🧳 Input your travel details: destination, days, interests, budget, and preferred season
* 🗺️ Generates a fully detailed, AI-crafted travel itinerary
* 📥 Download your itinerary as a `.txt` file for offline use

---

## 🛠️ Technologies Used

* `Streamlit` – UI framework for interactive web apps
* `Hugging Face Transformers` – Text generation using `google/flan-t5-small`
* `LangChain` – LLM chaining framework for flexible AI flows
* `python-dotenv` – For loading secure API keys from `.env` file

---

## 🎥 Demo Video
Watch how NutriMate works in action : [Click Here](https://youtube.com/shorts/2I6ErINhOMA?si=pKYIm-f7L5C2VLFD)

---

## 💡 How to Run Locally

1. Clone the repository

2. Create your `.env` file with Hugging Face token

```env
HUGGINGFACE_API_KEY=your-huggingface-token-here
```

3. Install dependencies

4. Run the app

```bash
streamlit run tripmate_ai_app.py
```

---

## 📌 Notes

* The app uses `google/flan-t5-small` for fast, budget-friendly text generation
* LangChain makes it easy to scale or switch models later
* Future enhancements may include Google Maps integration or hotel recommendations

---

Built by **Mayusha Athukorala** | BSc in Applied Data Science Communication | KDU
