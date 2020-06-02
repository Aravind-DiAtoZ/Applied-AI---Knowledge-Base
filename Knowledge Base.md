## Diatoz Applied AI team - Knowledge Base



Instructions to add resources:

1. Contents

   - Text 

     - Contextual details 

   - Code

     - Sample snippets

   - Hyperlinks

   - Videos

     - iframe - youtube videos

       

2. Important Notice

3. Interesting Facts

4. Reference links

   

## Flask

[Flask](https://palletsprojects.com/p/flask/) is a lightweight [WSGI](https://wsgi.readthedocs.io/) web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around [Werkzeug](https://palletsprojects.com/p/werkzeug) and [Jinja](https://palletsprojects.com/p/jinja) and has become one of the most popular Python web application frameworks.


```
from flask import Flask, escape, request

app = Flask(__name__)

@app.route('/')
def hello():
    name = request.args.get("name", "World")
    return f'Hello, {escape(name)}!'
```

```
$ env FLASK_APP=hello.py flask run
 * Serving Flask app "hello"
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```



#### Important Notice:

`While lightweight and easy to use, **Flask’s built-in server is not suitable for production** as it doesn’t scale well. Some of the options available for properly running Flask in production are documented here.`

`If you want to deploy your Flask application to a WSGI server not listed here, look up the server documentation about how to use a WSGI app with it. Just remember that your Flask application object is the actual WSGI application.`



<iframe width="560" height="315" src="https://www.youtube.com/embed/Z1RJmh_OqeA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



Reference links:

https://flask.palletsprojects.com/en/1.1.x/deploying/





Typical problems to which AI methods are applied

- [Optical character recognition](https://en.wikipedia.org/wiki/Optical_character_recognition)
- [Handwriting recognition](https://en.wikipedia.org/wiki/Handwriting_recognition)
- [Speech recognition](https://en.wikipedia.org/wiki/Speech_recognition)
- [Pose estimation](https://en.wikipedia.org/wiki/Pose_(computer_vision)), 
- [activity recognition](https://paperswithcode.com/task/action-recognition-in-videos)
- [face recognition](https://en.wikipedia.org/wiki/Facial_recognition_system), 
- [emotion recognition](https://en.wikipedia.org/wiki/Emotion_recognition)
- [Artificial creativity](https://en.wikipedia.org/wiki/Artificial_creativity)
- [Computer vision](https://en.wikipedia.org/wiki/Computer_vision)
- [virtual reality](https://en.wikipedia.org/wiki/Virtual_reality),
- [image processing](https://en.wikipedia.org/wiki/Image_processing),
- [Pixel-art scaling algorithms](https://en.wikipedia.org/wiki/Pixel-art_scaling_algorithms)
- [Image scaling](https://en.wikipedia.org/wiki/Image_scaling)
- [Photo](https://en.wikipedia.org/wiki/Photo_manipulation) and[ video manipulation](https://en.wikipedia.org/wiki/Video_manipulation), 
- Super Resolution
- [Diagnosis (artificial intelligence)](https://en.wikipedia.org/wiki/Diagnosis_(artificial_intelligence))
- [Game theory](https://en.wikipedia.org/wiki/Game_theory) and[ strategic planning](https://en.wikipedia.org/wiki/Strategic_planning)
- [Game artificial intelligence](https://en.wikipedia.org/wiki/Game_artificial_intelligence) and [computer game bot](https://en.wikipedia.org/wiki/Computer_game_bot)
- [Natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing),
- [translation](https://en.wikipedia.org/wiki/Translation) and[ chatterbots](https://en.wikipedia.org/wiki/Chatterbot)
- [Nonlinear control](https://en.wikipedia.org/wiki/Nonlinear_control) and[ robotics](https://en.wikipedia.org/wiki/Robot)
- [Marketing](https://en.wikipedia.org/wiki/Artificial_intelligence_marketing)



**Other fields in which AI methods are implemented**

- [Artificial life](https://en.wikipedia.org/wiki/Artificial_life)
- [Automated reasoning](https://en.wikipedia.org/wiki/Automated_reasoning)
- [Automation](https://en.wikipedia.org/wiki/Automation)
- [Bio-inspired computing](https://en.wikipedia.org/wiki/Bio-inspired_computing)
- [Concept mining](https://en.wikipedia.org/wiki/Concept_mining)
- [Data mining](https://en.wikipedia.org/wiki/Data_mining)
- [Knowledge representation](https://en.wikipedia.org/wiki/Knowledge_representation)
- [Semantic Web](https://en.wikipedia.org/wiki/Semantic_Web)
- [Email spam](https://en.wikipedia.org/wiki/Email_spam) filtering
- [Robotics](https://en.wikipedia.org/wiki/Robot)
- [Behavior-based robotics](https://en.wikipedia.org/wiki/Behavior-based_robotics)
- [Cognitive](https://en.wikipedia.org/wiki/Cognitive)
- [Cybernetics](https://en.wikipedia.org/wiki/Cybernetics)
- [Developmental robotics](https://en.wikipedia.org/wiki/Developmental_robotics) (Epigenetic)
- [Evolutionary robotics](https://en.wikipedia.org/wiki/Evolutionary_robotics)
- [Hybrid intelligent system](https://en.wikipedia.org/wiki/Hybrid_intelligent_system)
- [Intelligent agent](https://en.wikipedia.org/wiki/Intelligent_agent)
- [Intelligent control](https://en.wikipedia.org/wiki/Intelligent_control)
- [Litigation](https://en.wikipedia.org/wiki/Litigation)




Applications of Deep learning: 

- Automatic speech recognition
- Image recognition
- Natural language processing
- Drug discovery and toxicology
- Dynamic Pricing
- Fraud Detection
- Chatbots





**Sectors:**

- E-commerce
- Personalized shopping experience
- Healthcare
- Finance
- Robotics
- Drones
- Smart cars
- Social Media
- IoT Security and surveillance
- Software Development and Design Marketing	



Reference:

https://en.wikipedia.org/wiki/Applications_of_artificial_intelligence

https://becominghuman.ai/10-powerful-examples-of-ai-applications-553f7f062d9f

https://www.dezyre.com/article/top-10-industrial-applications-of-machine-learning/364