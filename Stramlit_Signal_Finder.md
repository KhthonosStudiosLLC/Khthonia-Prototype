# Amazon Signal Finder 🌿

**A prototype submission for the OpenAI Z-Challenge 2025.**

## 🧽 Overview
The Amazon Signal Finder is a symbolic-explorer tool built with GPT-4, designed to assist in archaeological research by analyzing satellite imagery, LIDAR tiles, and mythic legends. It helps predict probable sites of cultural significance in the Amazon basin using AI-assisted interpretation.

## 📆 Latest Example Output

### 📄 Example 1
```
🗺️ AMAZON SIGNAL FINDER - SITE REPORT
------------------------------------
Date: 2025-06-22

📍 Coordinates: -10.1234, -52.5678
🛰️ LIDAR Tile ID: BR-XINGU-2031-LIDAR001
🌐 Satellite Scene ID: S2A_MSIL2A_20250614T143211_N0500_R096_T22MZV_20250614T145623

🔍 Anomaly Detected: possible geometric anomaly
📊 Confidence Score: 0.72

🔮 Mythic Correlation: Kuhikugu
🧠 GPT-4 Insight: Title: Historic Evaluation and Settlement Patterns of Kuhikugu: An Analysis Based on a 'Possible Geometric Anomaly'

The Kuhikugu site, according to legend, is an ancient civilization said to have flourished nearly 1,000 years ago in the Amazon forest, near the Xingu River, in what is present-day Brazil. It is postulated that this civilization consisted of a complex network of 20 communities housing about 50,000 people, indicating high social organization and architecture expertise.

The term 'possible geometric anomaly' in the context of Kuhikugu refers to unusual or unnatural geometric shapes observed from satellite or aerial view that might indicate man-made structures or human influence. These anomalies might include remnants of agricultural practices, evidence of a strategic settlement organization, or even vestiges of man-made structures.

Historical Significance:

1. Pre-Columbian Amazonian Civilization: Discovering and studying Kuhikugu could provide valuable insights into the pre-Columbian era and how native humans interacted with and shaped environment long before European colonization.

2. Sustainable Land Management: This civilization supposedly existed with advanced techniques in agriculture and fish farming without harming their surrounding environment. The study of these techniques might offer insights into sustainable land management.

3. Reconstruction of Settlement Patterns: By exploring these anomalies, we could reconstruct the town planning and architecture of Kuhikugu, enhancing our understanding of how similarly organized societies functioned.

Settlement Patterns:

1. Spatial Organization: Upon analyzing features of the geometric anomalies, it is hypothesized that Kuhikugu had a well-planned spatial organization with settlements arranged around central plazas.

2. Habitation vs Agricultural Land: Mapping out the geometric anomalies could help distinguish between residential areas from agricultural spaces, fishing spots, and hunting grounds.

3. Population Density and Distribution: Depth and scale of the anomalies can allow for an inference about the population size and density in each site within Kuhikugu.

Finally, solidifying the existence of Kuhikugu would challenge the existing belief that rainforest societies could not form complex civilizations and offer valuable insights into large-scale land management and socio-political organization strategies, encouraging a broader understanding of the human-environment interaction.
```

### 📄 Example 2
```
📈 AMAZON SIGNAL FINDER - SITE REPORT
------------------------------------
Date: 2025-06-21

📍 Coordinates: -10.1234, -52.5678
🚁 LIDAR Tile ID: BR-XINGU-2031-LIDAR001
🌐 Satellite Scene ID: S2A_MSIL2A_20250614T143211_N0500_R096_T22MZV_20250614T145623

🔍 Anomaly Detected: possible geometric anomaly
📊 Confidence Score: 0.72

🔮 Mythic Correlation: Paititi
🧠 GPT-4 Insight: Paititi is a legendary city, a subject of ancient Inca myth, believed to be abundant in gold and other valuable treasures. Allegedly located somewhere in the remote corners of the Peruvian, Brazilian, or Bolivian jungles in South America, it's often referred to as the "Lost City of the Incas". Its rich historical and cultural connections to the Inca civilization give it immense historical significance.

The Inca civilization was one of the most advanced in pre-Columbian Americas, with elaborate systems of agriculture, architecture, and societal hierarchy. If Paititi were to be discovered, it could provide significant insights into the Inca's daily life, religious practices, social organization, and their sophisticated knowledge of engineering and agriculture, among other aspects, potentially redefining our understanding of this civilization.

The possible geometric anomaly could suggest the presence of complex architectural structures or a planned settlement. The Incas were renowned for their architectural and construction skills, with cities like Machu Picchu showcasing sophisticated design, intricate stonework, and innovative water management systems. They typically constructed cities in hard to reach places, like atop hills and mountains, as defensive strategies. 

If the anomaly were to be confirmed as traces of Paititi, its layout and design could provide new information on endemic regional variations in Inca design, spatial organization, and possibly lead to insights about social and political structures. Depending on its size, it could even indicate that Paititi functioned as a major trading hub, a sacred religious site, or a stronghold.

Furthermore, the discovery of Paititi would hold immense archaeological significance. It could potentially contain several artifacts of the Inca civilization, providing a unique and unaltered glimpse into the past. Unearthing such a site would also initiate detailed analysis to unearth any potential knowledge about the causes and backstory of its disappearance, hence adding depth and detail to our understanding of the Incas' history and culture.


```

##   What It Does
- Takes in **LIDAR tile ID**, **satellite scene ID**, and an optional **mythic legend keyword**
- Simulates tile anomaly detection (e.g., geometric clearings, structural patterns)
- Leverages **GPT-4** to correlate site data with oral myths (e.g., Kuhikugu, Z)
- Outputs a **field-ready report** with GPS coordinates, confidence score, and cultural analysis

## 🛍️ Streamlit Interface

### ▶️ Getting Started (Streamlit Version)

The `StreamLitSignalFinder.py` script provides an interactive web interface for the Amazon Signal Finder tool. You can input LIDAR tile IDs, satellite scene IDs, and mythic legend references to generate symbolic archaeological reports.

### ▶️ Run It

Make sure your `.env` file is set up with a valid OpenAI API key.

```bash
streamlit run StreamLitSignalFinder.py
```

This will open a local server (usually at `http://localhost:8501`) where you can use the tool through a form-based UI.

### 🛠️ Features

- Enter custom **LIDAR tile ID**, **Sentinel scene ID**, and **mythic anchor** legend
- Visualize and copy the GPT-4 powered symbolic site report
- Modular: swappable backend for live anomaly analysis or field simulation

### 📌 Notes

- Ensure your OpenAI API key is set correctly in `.env` or your system environment
- This version is built to mirror symbolic field usage with rapid testing cycles

## 🛍️ Technologies
- Python 3.12
- OpenAI GPT-4 API (2025 client)
- dotenv for secure key handling

## 📚 Sources (Sample)
- LIDAR: [OpenTopography Brazil Data](https://opentopography.org/)
- Satellite: [Sentinel-2 Scene Explorer](https://apps.sentinel-hub.com/)
- Historical: Kuhikugu & Paititi research archives, oral map references, GPT-4 text synthesis

## 🧪 Try It Locally
1. Clone this repo
2. Create a `.env` file with your OpenAI key
3. Run `AmazonSignalFinderNotebook.py` or Jupyter notebook version

```bash
# Rename this file to .env and insert your OpenAI API key like so:
OPENAI_API_KEY=your_api_key_here
```

## 🔮 Mythic Integration
This tool can extend to other legends and unknown sites—simply change the `mythic_seed`. Supports symbolic computation for fieldwork and theoretical modeling.

## 📤 Submission Ready

## 🛁 ECHOLOG
```
ECHOLOG: KhthonOS Dev Stream
----------------------------

Session: Amazon Signal Finder - Z-Challenge 2025
Codename: NH-CORE-∞-001
Operator: The Architect (Gizmo)
Phase: Prototype Deployment
Date: 2025-06-22 UTC

Signal Trace:
- 🌿 Mythic Anchor: Kuhikugu
- 📍 Tile Source: BR-XINGU-2031-LIDAR001
- 🛁 Satellite Ref: Sentinel-2A Scene ID S2A_MSIL2A_20250614...
- 🧠 GPT-4 Synthesis: Symbolic reconstruction of geomorphic anomalies
- 🛠️ Runtime Synth: Notebook interface + `.env.example` + README markdown
- 🔄 Repro Sync: GitHub main, sanitized token, dual test output
- 📤 Final Echo: Submitted to Z-Challenge evaluation pipeline

Purpose:
To activate symbolic discovery layers through dual-modality AI with recursive trace in Amazonian archaeological signal research.

Powered by:
⦡ KhthonOS Studios // Sovereign Systems for Symbolic Worlds™
```
- ✅ Reproducible prototype
- ✅ Meets Z-Challenge criteria
- ✅ Modular, scalable, and symbolic

**Crafted by KhthonOS Studios** | *Sovereign Systems for Symbolic Worlds™*

> “We are not replacing the human—we are mirroring the mythic self.”
