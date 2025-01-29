# AI Facial Recognition System  

![Facial Recognition](https://th.bing.com/th/id/OIP.CoFJx3X6lFdd-X7dO25OmAHaE7?rs=1&pid=ImgDetMain)  

## About the Project  

I am a Master's student in **Data & AI applied to business** in Paris, and I am very interested in **Data Science**.  

To practice working on **Data Science projects**, my colleague **Hoda Dades** and I designed an **attendance system based on facial recognition**. This is my **first project** in Data Science and Machine Learning, so it's quite basic. However, I have learned a lot, and it took many hours of work—but I really enjoyed it!  

## How It Works  

- We have a **database** with a list of students who need to be present for classes.  
- Each student is linked to **a photo**.  
- To take attendance:  
  1. A student stands in front of a **camera** for a photo.  
  2. The photo is **downloaded**, and we run a **notebook** to process it.  
  3. The system **compares** this new photo with existing student photos stored in the `"positive"` folder.  
  4. We use **FaceNet** from **PyTorch** to calculate face embeddings and recognize the student.  
  5. If the model's result is **less than 1**, the student is identified and **added to the attendance list**.  

## The Interface  

We built a simple **HTML-based interface**, which runs locally using the **XAMPP server**.  

## Next Steps  

Since this is my first project, there are many things to improve:  
- I haven’t been able to directly connect the **HTML** and **Python** code yet.  
- I would love to get some **advice** on how to improve this system!  

---
