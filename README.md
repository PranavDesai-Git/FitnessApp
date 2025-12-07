# MoveMentor – AI Fitness & Diet Assistant

MoveMentor is an AI fitness and diet assistant that analyzes posture in real time, gives feedback, counts reps, and tracks progress. It also collects user lifestyle, BMI, budget, and kitchen access to create personalized diet plans. Users can upload meal photos to get calorie and nutrition estimates.

---

## Project Overview

MoveMentor is an AI-powered fitness and nutrition system that helps users exercise correctly and eat smarter with personalized guidance. Using a webcam, it detects body keypoints, calculates joint angles, and evaluates workout form for exercises like squats, planks, and push-ups. It provides instant corrective feedback and accurate rep counting to prevent injuries and improve performance. On the diet side, MoveMentor collects details such as whether the user is a hosteller, bachelor, or living at home, whether they are a student or working professional, their budget, kitchen facilities (stove, fridge, etc.), and their height, weight, and BMI. Based on this profile, it generates practical diet plans that fit the user’s lifestyle, health goals, and affordability. Users can also upload meal photos; the app identifies the food and estimates calories and basic nutritional values, helping them stay aware of what they eat.

---

## Features

- Real-time posture detection using webcam  
- Form evaluation and live feedback based on joint angles  
- Repetition counting for supported exercises  
- User onboarding (living type, student/job, budget, stove/fridge, height, weight, BMI)  
- Personalized diet plans based on lifestyle, BMI, and budget  
- Meal photo analysis for calorie and nutrition estimation  
- Dashboard for posture, reps, accuracy, and recent meals

---

## Tech Stack

- Language: Python  
- Computer Vision: MediaPipe, OpenCV  
- Math / Logic: NumPy, Math  
- UI / Dashboard: Streamlit  
- Machine Learning for Food: CNN models (PyTorch/TensorFlow)  
- Visualization: Matplotlib / Plotly  
- Nutrition Data: Custom dataset or external nutrition APIs  

---

## Objectives

- Detect and analyze human posture in real time  
- Improve exercise safety with automatic form feedback  
- Track reps and performance accurately  
- Build a lifestyle-aware diet recommendation engine  
- Estimate calories from meal images and show nutrition details  

---

## Project Status

- Idea and design completed  
- Initial report and documentation completed  
- Implementation in progress  

---

## Future Work

- Voice-based coaching  
- Better multi-food detection in one plate  
- Mobile app version of MoveMentor  
- Integration with smartwatches and fitness bands  
