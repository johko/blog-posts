# Robot Holmes and the Vision-Language Murder Mysteries #1

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/yUdvvxZQPY7_O3eJuiH45.png)

This blog post is the first part of a little story that will introduce you to Vision-Language models and related tasks.
We will follow the detective Robot Holmes through a night full of murder, betrayal and envy in the bustling city of MLington.

## Intro
Our story begins on a typical MLington day - cold, gray, rainy. Luckily the sun was setting and taking its light of the misery of this city. Robot Holmes entered his office and found the chief of police already waiting for him.

That never is good news.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/Fw-D-aPntUjNpWpQN-acg.png)

*“Its [Old SAN](https://arxiv.org/pdf/1511.02274.pdf), he has been found dead inside his devastated workshop.”*
Old SAN - one of the people over in *Vision Language Village*. A reputable citizen - has been there for ages, basically started the whole part of town with some other guys. There were rumours of him being some sort of leader in the district’s community. Now he’s dead and he is not the first one in the Village recently.
*“There is something going on on the other side of the river Holmes”*, the chief proclaimed.
*“Almost every other week an established citizen is murdered. We have a Murder Series on our hands and no clue. I want you to find out what’s going on over there.”*
 
Holmes sighed heavily, put on his hat and stepped out into the dark city streets of MLington.

## MLington
You might have never heard of MLington, so let us take a little tour through Holmes' hometown:
![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/47dLSYSXnKlCpI5eqS33G.png)

**City of Science**
Right at the core of MLington, the *City of Science* is the place where the scientists live and where they build their cathedrals for Machine Learning. Legend has it, that when a team of scientist loves their research very much, a new Machine Learning model is born. Now and then there might be an Ivory Tower popping up in these parts of town and falling to rubbles again soon after.

The City of Science is separating two very old parts of the city.

**Visionsworth**
To the east you can find *Visionsworth*, the place where Computer Vision has its home. From the old days of hand crafted filters all the way to the modern Vision Transformers. This part of town is well established and strong in its foundation.

**Languageshire**
To the west of the City of Science you can find *Languageshire* - as you might guess this is the area where Natural Language Processing is at home. From the oldest symbolic NLP days to today’s Large Language Models, this part of town has stood the test of time and has been setting the trends in MLington recently.

**Vision-Language Village** (ViLaVi)
On the other side of the river we find a smaller settlement - Vision Language Village. Connected to both Languageshire and Visionsworth. This area has become a melting pot of ideas from Visionsworth and Languageshire. It has been growing at a tremendous speed in the last years and it seems like the influx of ever new citizens won’t stop that soon. This brings a lot of life to its streets but, unfortunately for Robot Holmes, also death.

## Vision-Language Tasks
Before Holmes delves deeper into the societal networks of the Village, he wants to know what is going on in its streets and which kind of tasks are performed there. So he decides to gather intel on some of the most popular services offered in ViLaVi:

**Image Captioning**

The first shop Holmes entered had high windows which let a lot of light into a rather small room with an unusually high ceiling. At the walls there were pictures of all sorts - painting, photographs, sketches, prints. Below every single one was a small white sheet with text written on it.

Holmes turned to the only person in the shop besides him - a woman standing on a sturdy ladder. She was in the process of exchanging one of the pictures on the wall and winced a little when Holmes began to speak.

"What service do you offer here?", he asked bluntly. "I'm an image captioner sir - I caption images. Some also call it Text-to-Image", she replied with a cheerful voice. "People bring me their images and I write down what can be seen on them. I inherited this shop from my father. You can still see some of his work over there. It was never picked up." Holmes looked around to where the woman pointed and saw some small images with even smaller notepads below. "Not a man of many words it seems", Holmes said. "Well, the old times sir. A few words were enough then, but nowadays the customers want more and more detailed descriptions."

"May I ask for your names and can you recommend some other good captioners?", Holmes inquired.
"Of course, I go by [LLaVA](https://huggingface.co/spaces/badayvedat/LLaVA) and one of my best colleagues is [InstructBLIP](https://huggingface.co/spaces/library-samples/InstructBLIP). Feel free to pay him a visit when you have some time."

Holmes thanked her, said his farewells and stepped back out into the dark city streets.


![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/mPzG7osMLjljZFyXxBnPI.png)

**Image-Text Retrieval**

Just around the corner Holmes enters another shop, filled with boxes of images. The boxes were everywhere, stacked all along the walls and even on the floor towers of boxes were leaning onto one another. Holmes carefully stepped around them, looking for the shop owner. He heard a mumbling from somewhere behind an exceptionally big cardboard box and found an old man deeply lost in thought looking at small images and muttering to himself.

"What service do you offer?", Holmes asked a little to loud and was expecting the shopkeeper to wince at this sudden intruder, like in the shop before.

The old man stopped mumbling. "Name an animal", he suddenly said in the direction of Holmes.
"Elephant", Holmes said, slightly bewildered and curious what would happen next. At lightning speed, the shopkeeper picks a bunch of images from the box and hands them to Holmes - all showing elephants.

"That is what I do", the vendor says, "I match images and text. Give me any prompt and a set of images and I will tell you how good the images fit your request. Image-Text Retrieval is what we call it in the business." The thing that Holmes found most interesting about this, was the speed at which the shopkeeper could pick the right images among hundreds, if not thousands of others.

"What is your name and are there others in your business?", Holmes asked him. "I go by the name of [ALBEF]()

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/5OJ8G40S3n8i7n7Tgsvt-.png)

**Visual Question Answering**
The task of Visual Question Answering (VQA) comes in two forms:
1. One-off Q&A - you ask one question, you get one answer, done
2. Continous Q&A - you ask one question, you get one answer, you ask another question which can build up on the first one and you get a fitting answer. Basically you can do this up to a certain context-length of the model.
One of the most powerful use cases for this service, can be to enable blind people to ask questions about scenes and get a VQA generated answer (turned into audio output).

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/sw0MFGUQcA-B_3FZPrf2Y.png)

**Visual Grounding**
Visual Grounding is, to be exact, not a single service or task. The term contains many sub-tasks, such as Open-Vocabulary Object Detection, 

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/13v6P9jWD4GYVygIqbQgR.png)

**Text to Image**
Maybe the most popular task in recent time in ViLaVi has been text-to-image. Given a text prompt, the models offering this service, create an image for you, that tries to depict your prompt description as good as possible
Actually models in MLington offering this service have started a whole new part of town, as they outgrew ViLaVi and started to become a whole ecosystem for themselves. They now reside in Diffuserton, which is a part of town for another story. Robot Holmes decided to set foot in there and instead focus on the current citizens populating the streets of MLington.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/4J6hdvBtSPLBAoEMFK4Ft.png)
