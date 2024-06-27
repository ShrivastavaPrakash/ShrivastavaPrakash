# Hi there, I'm Prakash Kumar! 👋
pip install Pillow
from PIL import Image, ImageDraw, ImageFont

# Create an image with a dark background
width, height = 1200, 400
background_color = (10, 10, 50)
image = Image.new('RGB', (width, height), background_color)
draw = ImageDraw.Draw(image)

# Load a font
font_path = "arial.ttf"  # Ensure this path is correct on your system
title_font_size = 72
subtitle_font_size = 36
font_title = ImageFont.truetype(font_path, title_font_size)
font_subtitle = ImageFont.truetype(font_path, subtitle_font_size)

# Define text and position
title_text = "Prakash Kumar"
subtitle_text = "Full Stack Data Scientist & Machine Learning Engineer"
contact_text = "+91-9721001545"

# Define text colors
text_color = (255, 255, 255)

# Calculate text width and height to center it
title_width, title_height = draw.textsize(title_text, font=font_title)
subtitle_width, subtitle_height = draw.textsize(subtitle_text, font=font_subtitle)
contact_width, contact_height = draw.textsize(contact_text, font=font_subtitle)

title_x = (width - title_width) / 2
title_y = (height - title_height) / 3
subtitle_x = (width - subtitle_width) / 2
subtitle_y = title_y + title_height + 20
contact_x = (width - contact_width) / 2
contact_y = subtitle_y + subtitle_height + 20

# Draw text on image
draw.text((title_x, title_y), title_text, fill=text_color, font=font_title)
draw.text((subtitle_x, subtitle_y), subtitle_text, fill=text_color, font=font_subtitle)
draw.text((contact_x, contact_y), contact_text, fill=text_color, font=font_subtitle)

# Save the image
image_path = "profile_banner.png"
image.save(image_path)

print(f"Banner saved as {image_path}")



![Profile Banner](https://yourimageurl.com/banner.png)

## About Me

A dynamic and goal-driven individual with exceptional leadership skills and an insatiable thirst for knowledge. I am pursuing my interest in Machine Learning and Artificial Intelligence to apply my theoretical knowledge to real-world scenarios and gain hands-on experience to augment my skills. Currently seeking immersive internship and job opportunities, I am committed to refining my abilities and making meaningful contributions to any team fortunate enough to have me.

![Profile Views](https://komarev.com/ghpvc/?username=ShrivastavaPrakash&style=flat-square)

- 🌍  I'm based in Noida, Uttar Pradesh, India
- ✉️  You can contact me at [iampk9430@gmail.com](mailto:iampk9430@gmail.com)
- 🧠  Currently enhancing my skills with courses on [Udemy](https://www.udemy.com/) and [ineuron](https://ineuron.ai/)
- 🚀  Always open to collaborating on interesting projects

## 🔧 Technical Skills

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sql&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-000000?style=for-the-badge&logo=matplotlib&logoColor=white)

## 📚 Education

- **Bachelor of Technology (Hons.) in Computer Science**  
  Lovely Professional University, Phagwara, Punjab (2020-2024)  
  Relevant Courses: Data Structures, Algorithms, DBMS, OS, Computer Networks, Software Engineering, AI, ML, Web Technologies, Cyber Security.  
  **CGPA: 7.13**

- **Intermediate**  
  R.L.S.Y College, Muzaffarpur, Bihar School Examination Board (2016-2019)  
  **Percentage: 70.2**

- **Matriculation**  
  Sunshine Prep./Public High School, CBSE (2015-2016)  
  **CGPA: 9.8**

## 🚀 Projects

### 1. Skin Disease Detection System
- **Technologies:** Deep Learning, CNN, TensorFlow
- **Description:** Developed a CNN-based system for detecting skin diseases, achieving a classification accuracy of 92%.
- **Skills Used:** Python, TensorFlow, Keras, CNN, Data Augmentation, Sequential Model

### 2. Document Verification Using LSTM
- **Technologies:** Deep Learning, LSTM, Keras
- **Description:** Designed and implemented an LSTM-based deep learning model for document verification.
- **Skills Used:** LSTM, Data Preprocessing, Visualization, Model Building, Model Evaluation, Embedding Layers, Tokenization

### 3. Credit Card Fraud Detection
- **Technologies:** Machine Learning, Autoencoders, Scikit-Learn
- **Description:** Leveraged autoencoder techniques to detect fraudulent activities, resulting in enhanced predictive performance.
- **Skills Used:** Scikit-Learn, Autoencoder, Random Forest, F1-score, precision, recall, AUC-ROC

### 4. Caesar Cipher Project
- **Technologies:** Python
- **Description:** A program to encrypt and decrypt messages using the Caesar cipher.
- **Skills Used:** Python

## 📜 Certifications

- **Python: 100 Days of Code - The Complete Python** (Udemy, Jan 2023)
- **Machine Learning: Unsupervised Learning, Recommenders, Reinforcement Learning** (Nov 2023)
- **C++: Core Industry Training and DSA** (Coding Ninja, Oct 2023 - Ongoing)
- **Data Science: Full Stack Data Science BootCamp 2.0** (ineuron, Ongoing)

## 🌐 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prakashkumar001/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ShrivastavaPrakash)

## 📈 GitHub Stats

![Prakash's GitHub stats](https://github-readme-stats.vercel.app/api?username=ShrivastavaPrakash&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ShrivastavaPrakash&layout=compact&theme=radical)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ShrivastavaPrakash&theme=radical)

## ✍️ Blog Posts

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

## 🏆 Achievements

<!-- ACHIEVEMENT-LIST:START -->
<!-- ACHIEVEMENT-LIST:END -->

---

⭐️ From [Prakash Kumar](https://github.com/ShrivastavaPrakash)
