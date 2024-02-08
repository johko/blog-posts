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

"What service do you offer here?", he asked bluntly. "I'm an image captioner sir - I caption images. Some also call it **Text-to-Image**", she replied with a cheerful voice. "People bring me their images and I write down what can be seen on them. I inherited this shop from my father. You can still see some of his work over there. It was never picked up." Holmes looked around to where the woman pointed and saw some small images with even smaller notepads below. "Not a man of many words it seems", Holmes said. "Well, the old times sir. A few words were enough then, but nowadays the customers want more and more detailed descriptions."

"May I ask for your names and can you recommend some other good captioners?", Holmes inquired.
"Of course, I go by [LLaVA](https://huggingface.co/spaces/badayvedat/LLaVA) and one of my best colleagues is [InstructBLIP](https://huggingface.co/spaces/library-samples/InstructBLIP). Feel free to pay him a visit when you have some time."

Holmes thanked her, said his farewells and stepped back out into the dark city streets.


![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/mPzG7osMLjljZFyXxBnPI.png)

**Image-Text Retrieval**

Just around the corner Holmes enters another shop, filled with boxes of images. The boxes were everywhere, stacked all along the walls and even on the floor towers of boxes were leaning onto one another. Holmes carefully stepped around them, looking for the shop owner. He heard a mumbling from somewhere behind an exceptionally big cardboard box and found an old man deeply lost in thought looking at small images and muttering to himself.

"What service do you offer?", Holmes asked a little to loud and was expecting the shopkeeper to wince at this sudden intruder, like in the shop before.

The old man stopped mumbling. "Name an animal", he suddenly said in the direction of Holmes.
"Elephant", Holmes said, slightly bewildered and curious what would happen next. At lightning speed, the shopkeeper picks a bunch of images from the box and hands them to Holmes - all showing elephants.

"That is what I do", the vendor says, "I match images and text. Give me any prompt and a set of images and I will tell you how good the images fit your request. **Image-Text Retrieval** (ITR) is what we call it in the business." The thing that Holmes found most interesting about this, was the speed at which the shopkeeper could pick the right images among hundreds, if not thousands of others.

"What is your name and are there others in your business?", Holmes asked him. "I go by the name of [ALIGN](https://huggingface.co/docs/transformers/model_doc/align). And there are others of course, many of us actually learned multiple trades and offer ITR among them, like my colleague [FLAVA](https://huggingface.co/docs/transformers/model_doc/flava)."

Holmes thanked the man and was on his way again.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/5OJ8G40S3n8i7n7Tgsvt-.png)

**Visual Question Answering**
AS Holmes walked on through the dark city streets, a big wooden sign caught his eyes. It was shaped like a big red question mark and hung directly in front of one of the shops. 'Intriguing enough', he thought and opened the door of the shop.

"Yes, please, what do you want to know sir?", a high and nervous voice asked quickly even before Holmes' foot was inside of the shop.

"I'm just having a look", he answered, standing in the doorframe and trying to hide his bafflement at the sudden approach.
"There is no 'Having a look' here sir. People come with an image or a document, ask me questions about it, I answer them, they leave sir. The only one having a look is me sir. So what is your question?"

Now Holmes could see a very slim figure standing behind a big counter, nervously rubbing his hands and impatiently waiting for an answer.

"What do you call that service and yourself?", Holmes asked calmly.
"My name is [LLaVa](https://huggingface.co/docs/transformers/model_doc/llava) and the service is **Visual Question Answering** sir. And please sir, if you don't have any image or questions about it, could you step out again? I'm quite busy today sir."

"Is any of your colleagues maybe not that busy?", Holmes asked in a slightly sarcastic tone, given that the shop seemed completely empty, apart from him.
"You can try over at  [ViLT](https://huggingface.co/docs/transformers/model_doc/vilt#vilt)'s sir. Goodbye, sir."

"Have a good night", Holmes muttered and turned around, stepping out of the doorframe he was still standing in.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/sw0MFGUQcA-B_3FZPrf2Y.png)

**Visual Grounding**
Robot Holmes was getting to terms with the face that the inhabitatns of Vision-Language Village all seemed to be quite special characters. He had the feeling everyone here could be a murderer or no one. At the same time he sensed a strong bond in the local community.

As he was giving this some thought, he came to halt in front of a shop window, with a puzzled look on his face. There were empty frames in all kinds of colors hanging, standing and laying in the shop window.

He left out a heavy sigh, knowing that he had to go in and find out what this was all about. "Here we go again", he quietly said to himself and stepped inside the shop.

This time he was not greeted directly, a woman was bent over a big workbench with some kind of magnifying goggles sitting on her nose.

Holmes let his gaze roam around the shop and saw what seemed like a million compartments stretching along the wall with the empty frames he also saw in the window.

"Perfect", he heard the woman say. Happily she reached for a big bottle which must contain glue of some kind he thought, as she was using it to fixate the frame on an underlying image.

"Good evening. What are you doing there?", Holmes asked her when it seemed like she was done.
"Oh, hello there. I just marked this little street lamp here with this neat frame. Isn't it beautiful?", she answered, showing of her work with a certain glee.
"Well, yes", Holmes agreed, "but why are you doing this?"

"Because it is my job! My name is [KOSMOS-2](https://huggingface.co/docs/transformers/model_doc/kosmos-2). People give me a list of things I should mark for them and one or more images. Then I take my neat little frames here and apply them to the images. **Visual Grounding** is what we call it in our business."

"Interesting and are you the only one offering this service around here?", Holmes asked in an investigative manner.

"I wish", she said, "then business would be thriving. But there are many colleagues, more by the day I fear.
Visual Grounding is, to be exact, not a single service or task. The term contains many sub-tasks. Take [CLIPSeg](https://huggingface.co/docs/transformers/model_doc/clipseg) e.g., she does work with frames, but gives you masks you can lay over the image and mark the object you asked her to find."

Holmes was impressed, thanked her, took his notes and once again stepped back into the damp city streets.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/13v6P9jWD4GYVygIqbQgR.png)

**Text to Image**
He felt like he had a good grasps of some popular service offered in these streets now, but he already knew that the most popular task in recent time in ViLaVi has been text-to-image. Given a text prompt, the models offering this service create an image for you, that tries to depict your prompt description as good as possible
Actually models in MLington offering this service have started a whole new part of town, as they outgrew ViLaVi and started to become a whole ecosystem for themselves. They now reside in *Diffuserton*, which is a part of town for another story. Robot Holmes decided to not set foot in there and instead focus on the current citizens populating the streets of MLington.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/607feb037c746d01ecb19180/4J6hdvBtSPLBAoEMFK4Ft.png)


## The First Clue

Being a seasoned detective, Holmes knew that the first place you investigate is the murder scene. So he went to the workshop of Old SAN, which he found in a devastated state. Papers and images were scattered everywhere. It seemed like Old SAN did not go down without a fight.

Usually these crime scenes are rather hard for finding traces, as you never know what could be a clue and what is just a random arrangement of accidentally scattered material.

SAN operated an Image Question Answering service, that is what Holmes read in the case record. He had a set of glasses, indispensable at his age, which were broken and scattered all over the floor.

After some time, Holmes came to the conclusion that there was nothing helpful inside this shop that could give him a first lead. He faced the open door, to leave, when he suddenly saw something stuck to the underside of the door - a piece of red garment. Holmes crouched and picked it up.

Now, a piece of red garment might not look like much, but it is better then nothing. And as it happens Holmes earlier heard about one particular resident of ViLaVi who is infamous for her taste in red clothes. Holmes set off to see her and ask her some uncomfortable questions.


*Thank you for reading. This is where the first part of the story ends. The next one will be released soon.*