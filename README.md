# AI-itinerary-generator
## 📌 Project Overview
This project integrates **YouTube transcript analysis, location extraction, flight search, and itinerary generation** to help users plan their trips efficiently. It uses:
- **YouTube Transcript API** to extract transcripts from travel vlogs.
- **OpenAI API** to identify mentioned locations.
- **SerpAPI (Google Flights)** to fetch flight details.
- **Custom Itinerary Generator** to suggest a travel plan based on the extracted data.

## 🚀 Features
- Extracts **transcripts** from YouTube travel vlogs.
- Identifies **locations** mentioned in the video.
- Fetches **flight details** (departure, arrival, prices, airlines, etc.).
- Calculates **return dates** based on trip duration.
- Generates a **custom travel itinerary**.

## 🛠️ Tech Stack
- **Python** (for script execution)
- **SerpAPI** (for Google Flights search)
- **OpenAI API** (for text processing)
- **YouTube Transcript API** (for extracting subtitles)
- **Requests & JSON** (for API interactions)

## 🔧 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
 git clone https://github.com/your-username/your-repo-name.git
 cd your-repo-name
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Set Up Environment Variables**
Create a `.env` file and add your API keys:
```plaintext
OPENAI_API_KEY=your_openai_api_key
SERP_API_KEY=your_serpapi_key
```

### **4️⃣ Run the Program**
```bash
python main.py
```

## 🎯 How It Works
1. The user **inputs a YouTube video URL**.
2. The script **extracts the transcript** and finds **mentioned locations**.
3. The user **enters departure location and travel date**.
4. The program **fetches flights** and calculates **return date**.
5. It generates a **custom travel itinerary**.

## 📌 Example Usage
```
Enter YouTube video URL: https://www.youtube.com/watch?v=XYZ123
📍 Locations mentioned in the vlog: Dubai, Abu Dhabi
Enter your boarding IATA code: BOM
Enter travel date (YYYY-MM-DD): 2025-04-01
Trip duration (days): 10
Fetching flights from BOM to DXB...

✈️ Available Flight Options:
🔹 Flight 1:
   🏢 Airline: Emirates
   🛫 Departure: 10:30 AM
   🛬 Arrival: 1:30 PM
   💰 Price: $450 USD
----------------------------------------
🗺️ Generated Travel Itinerary:
Day 1: Explore Burj Khalifa & Dubai Mall
...
```


