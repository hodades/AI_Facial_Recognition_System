# AI_Facial_Recognition_System
Traditional ways like using badges or signing attendance sheets have many issues: Security Problems, Time-Consuming, Lack of Live Tracking. So there is a solution : AI-powered, contactless access using facial recognition, Real-time identification: Quick and secure entry, Easy integration with existing systems.
--
I am a Master's student in Data & AI applied to business in Paris, and I am very interested in Data Science.

To practice working on Data Science projects, my colleague Hoda Dades and I designed an attendance system based on facial recognition. This is my first project in Data Science and Machine Learning, so it's quite basic. However, I have learned a lot, and it took many hours of work—but I really enjoyed it!

How It Works
We have a database with a list of students who need to be present for classes. Each student is linked to a photo.

To take attendance, students stand in front of a camera for a photo. This photo is then downloaded, and we run a notebook to process it. The system compares the new photo with the existing student photos stored in the "positive" folder.

We use the FaceNet model from PyTorch to calculate face embeddings and recognize individuals. If the model returns a value less than 1, it means the person is in our database, and they are added to the attendance list.

The Interface
We built a simple HTML-based interface, which runs locally using the XAMPP server.

What’s Next?
Since this is my first project, there are many things to improve. For example, I haven’t been able to directly connect the HTML and Python code yet. I would love to get some advice on how to improve this system!
