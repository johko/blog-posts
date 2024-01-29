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
Before Holmes sets foot into the Village, he wants to know what is going on in its streets and which kind of tasks are performed there. So he decides to gather intel on some of the most popular services offered in ViLaVi:

**Image Captioning**

Some of the oldest workshops in the village offer a service called *Image Captioning*. Some people also refer to is as *image-to-text*. In essence the task is the same - given an image, the model is supposed to come up with a descriptive text for it. The quality of this service has long been not much more than okay, but with recent newcomers like [LLaVA](https://huggingface.co/spaces/badayvedat/LLaVA) and [InstructBLIP](https://huggingface.co/spaces/library-samples/InstructBLIP), the image captions have reached a new level of detail.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/mPzG7osMLjljZFyXxBnPI.png)

**Image-Text Retrieval**

Holmes stumbles upon another Shop, filled with boxes of images. Asking the shopkeeper what kind of services he offers, he Given a set of images and a text (prompt), find the best matching image for the prompt from the given set. At first glance this task does not seem to be very helpful, but it is worth giving it a second glance. E.g. Image-Text Retrieval can be a very powerful tool for multimodal searches. If you have a big amount of images and want to filter them with a free text prompt, this is one way to do it.

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
