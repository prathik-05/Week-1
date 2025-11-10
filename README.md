Week-1
♻️ Smart Waste Classification – Week 1  
🔹 Goal: Build an image-based AI system that classifies waste into categories such as plastic, glass, paper, etc. The first step toward an automated waste-sorting solution.
 AI for Sustainability Internship
 
🌍 Overview
This week focuses on understanding and preprocessing the **Waste Classification Dataset**, which helps identify whether waste is **Organic** or **Recyclable**.  
Proper classification supports recycling efficiency, reduces landfill waste, and promotes sustainable waste management practices.

📊 Dataset Details
- Source: [Kaggle – Waste Classification Data](https://www.kaggle.com/datasets/techsash/waste-classification-data)
- Total Images: 22,564 (Train + Validation)
- Classes: 2 (Organic, Recyclable)
- Image Types: RGB (various sizes)
- Task: Image classification for sustainability

⚙️ Preprocessing Performed
| Step | Description |
|------|--------------|
| 🧹 Dataset Extraction | Extracted from Kaggle using `kaggle.json` |
| 📂 Folder Structure | Verified and organized into `TRAIN` and `TEST` folders |
| 🔄 Normalization | Pixel values scaled to [0, 1] using `ImageDataGenerator(rescale=1./255)` |
| 🎞️ Data Augmentation | Rotation, zoom, and flips to improve model generalization (next week) |
| 📊 Visualization | Displayed sample images and dataset distribution per class |

 📸 Sample Outputs
- Bar chart showing image distribution across classes  
- Sample images from each category (Organic vs Recyclable)  
- Confirmation of 18,052 training + 4,512 validation images  

✅ Result: 

🌱 Sustainability Impact
- Encourages **responsible waste sorting** using AI  
- Reduces **contamination in recycling bins**  
- Promotes **efficient recycling** and **resource conservation**  
- Supports **UN SDG 12: Responsible Consumption & Production**

📅 Next Steps (Week 2 Preview)
- Build a CNN model using TensorFlow/Keras  
- Train on preprocessed data  
- Evaluate model accuracy and save results  

👨‍💻 Author
**S Prathik Reddy**  
AI for Sustainability Intern | Edunet Foundation x AICTE  
GitHub Profile: [@prathik-05](https://github.com/prathik-05)
