# DENSE-VIDEO-CAPTIONING-USING-HUGGINGFACE
A VIDEO CAPTIONING TOOL THAT DESCRIBES THE OBJECTS IN THE FRAME 

📽️ Video Captioning using BLIP Model

This project demonstrates how to automatically generate meaningful captions for videos using the BLIP (Bootstrapped Language-Image Pretraining) model from Salesforce. By combining the power of transformer-based vision-language models with video processing tools, the system extracts frames from a video and generates relevant natural language descriptions—one per second.

🧠 What It Does
	•	Allows users to upload any video
	•	Captures key video frames at 1-second intervals
	•	Uses the BLIP model to understand the content in each frame
	•	Generates accurate and human-like captions
	•	Overlays those captions directly onto the video
	•	Produces a final captioned video ready for download

💡 Why This Project?

Creating accessible and searchable video content is more important than ever. With advancements in AI, we can now generate natural language descriptions from visual data. This project bridges computer vision and natural language processing, making videos more interactive and informative.

Whether you’re a researcher, developer, or someone curious about how AI interprets visuals, this project offers a simple yet powerful demonstration.

🔧 Technologies Used
	•	🧠 BLIP Model (from Hugging Face Transformers)
	•	🎥 OpenCV for video frame processing
	•	🖼️ Pillow for image conversions
	•	⚙️ PyTorch for model execution
	•	📦 Google Colab for running the project in the cloud

🚀 How It Works
	1.	Upload a video
	2.	Extract 1 frame per second
	3.	Pass frames to the BLIP model for caption generation
	4.	Overlay each caption on the corresponding frame
	5.	Export the new captioned video

📌 Example Use-Cases
	•	Generating subtitles for educational or tutorial videos
	•	Creating summaries of surveillance footage
	•	Assisting visually impaired users with audio narration
	•	Enhancing metadata for video search engines

📂 Output Sample

A sample output video will contain frame-by-frame captions like:
	•	“A person riding a skateboard in a park”
	•	“Two people sitting on a bench talking”

📈 Future Enhancements
	•	Add audio-to-text (speech recognition)
	•	Enable multilingual captions
	•	Include motion tracking for dynamic frame selection
	•	Integrate a GUI or web interface
