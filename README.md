# 🥗 AI Nutrition Coach

**AI-powered nutrition analysis from food images using a multimodal large language model.**

AI Nutrition Coach is a full-stack AI web application that analyzes food images and provides calorie estimates, nutritional breakdowns, and health insights. Users upload a food image, ask a natural language question, and receive a structured, easy-to-understand nutritional assessment.

This project demonstrates real-world use of **Generative AI**, **computer vision**, and **LLM-based reasoning** in a health and wellness use case.

---

## 🚀 Main Goal of the Project

Tracking calories and nutrition manually is time-consuming and error-prone. This application removes friction by combining image understanding with natural language reasoning to deliver instant, meaningful insights from a single photo.

From a technical perspective, this project showcases:

- Multimodal LLM integration (image + text)
- AI-backed decision support
- Clean full-stack implementation
- Practical GenAI use beyond chatbots

---

## 🧠 How It Works

1. User uploads a food image and enters a question
2. Image is encoded to Base64
3. Image + prompt are sent to a multimodal LLM
4. Model identifies food items and estimates nutrition
5. Output is formatted and rendered in the UI

---

## 🖼️ Application Walkthrough

### Web App UI – Image Upload & Query

![Web App UI](Output/Web-App%20UI.png)

Users can:

- Ask questions like _“How many calories are in this food?”_
- Upload a meal image
- Submit for AI-powered analysis

---

### Image Preview After Upload

![Image Upload Preview](Output/Input%20Image%20Upload.png)

The uploaded image is previewed before submission for better user confidence.

---

### AI-Generated Nutrition Output

📄 **Sample Output (PDF)**  
[View AI Nutrition Output](Output/AI%20Nutrition%20Coach%20Final%20Output.pdf)

The AI returns a structured response including:

- Food identification
- Portion size and calorie estimation
- Total calorie count
- Macronutrients and micronutrients
- Health evaluation
- Medical disclaimer

---

## 📊 Sample Output Summary

For a sample Chicken Biryani meal, the AI produced:

- **Identified Items:** Chicken Biryani, Raita
- **Calories:**
  - Chicken Biryani (350g): ~540 kcal
  - Raita (100g): ~50 kcal
- **Total Calories:** ~590 kcal
- **Macronutrients:**
  - Protein: ~40g
  - Carbohydrates: ~80g
  - Fats: ~20g

This structured output makes the information actionable and easy to interpret.

---

## 🧰 Tech Stack

**Backend**

- Python
- Flask

**AI / ML**

- Llama 4 Maverick 17B 128E Instruct FP8
- IBM watsonx.ai
- Multimodal LLM inference

**Frontend**

- HTML
- CSS
- JavaScript

**Other**

- Pillow (image handling)
- requests (API communication)

---

## 📁 Project Structure

AI Nutrition Coach/<br>
│<br>
├── app.py # Flask backend & AI integration<br>
├── requirements.txt # Python dependencies<br>
├── templates/<br>
│ └── index.html # Frontend UI<br>
├── static/<br>
│ └── style.css # Styling<br>
├── Output/<br>
│ ├── Web-App UI.png<br>
│ ├── Input Image Upload.png<br>
│ └── AI Nutrition Coach Final Output.pdf<br>
└── README.md<br>

## ⚠️ Disclaimer

The nutritional values provided by this application are approximate and based on general food data. Actual values may vary depending on portion size, ingredients, preparation methods, and individual factors. This tool is intended for informational purposes only and should not replace professional dietary or medical advice.
