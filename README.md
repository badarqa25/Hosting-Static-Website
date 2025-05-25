# 🌍 Travel Explorer – Static Website

**Travel Explorer** is a professional static travel website designed using only HTML with embedded CSS. The website uses vibrant gradients, neon-themed buttons, smooth animations, and two images (`travel.jpg` and `profile.jpg`) for a modern and engaging visual experience.

## 📁 Project Structure

TravelExplorer/
│
├── index.html # Main page with hero image
├── about.html # About Me page with profile photo
├── places.html # Places page listing destinations
├── travel.jpg # Hero banner image
└── profile.jpg # Profile picture for About Me

markdown
Copy
Edit

## 🌐 Features

- ✅ Fully responsive and lightweight (pure HTML)
- ✅ Gradient backgrounds and neon UI elements
- ✅ Animated tabs and hover effects
- ✅ Profile and destination images
- ✅ Suitable for hosting on AWS S3 or any static hosting

## 🚀 Hosting Instructions (for AWS S3)

1. **Create an S3 Bucket**  
   - Name it uniquely (e.g., `my-travel-site`)
   - Disable Block All Public Access
   - Enable static website hosting

2. **Upload Files**  
   - Upload all HTML files and images (`index.html`, `about.html`, `places.html`, `travel.jpg`, `profile.jpg`)

3. **Set Bucket Policy**  
   Add the following policy to allow public read access:
   ```json
   {
     "Version": "2012-10-17",
     "Statement": [{
       "Sid": "PublicReadGetObject",
       "Effect": "Allow",
       "Principal": "*",
       "Action": "s3:GetObject",
       "Resource": "arn:aws:s3:::my-travel-website-badarqa"
     }]
   }
Access My Site
http://my-travel-website-badarqa.s3-website-us-east-1.amazonaws.com/index.html

📸 Screenshots
Add screenshots of the site once deployed for reference.
![image](https://github.com/user-attachments/assets/170ce527-a374-4110-b164-938d4923e053)


🧑 Author
Created by: Badarqa
Website: https://www.linkedin.com/in/badarqa-shakoor-08a951124/
Year: 2025
