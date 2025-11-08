# [Evaluating the Efficiency of Human-AI Interaction in Virtual Reality Using Foundation Models](/MastersThesis-CIT-VR-03737381.pdf) 

<img src="/images/outside.png" width="400" height="auto"><img src="/images/inside.PNG" width="400" height="auto">


### ABOUT
A VR experience where the user interacts with LLM powered NPCs using gestures

<img src="/images/GRM_Pose2.png" width="250" height="auto"><img src="/images/GRM_Think.png" width="250" height="auto"><img src="/images/GRM_Answer.png" width="250" height="auto">

1. The avatar asks a one handed/two handed gesture question
2. The user provides the pose
3. After holding the pose for x seconds the screenshot is taken and sent to the GPT-4o API
4. The API takes the image and prompt for context and returns a response
5. Additionally the user gets to interact with a shopping environment where they meet more such npcs
6. The user's shopping task involves collecting items from a generated shopping list based on the items in the shop

### MOTIVATION 

- Test Gestures as a viable input method
- Test image recognition capabilities of LLMs out-of-the-box
- Underresearched topic

**Keywords:** _LLM, NPC, Gesture Recognition, VR_

### RESEARCH QUESTIONS

- RQ1:  How accurately can the model identify the user’s gesture?
- RQ2: How quickly can the model read the user’s gesture?
- RQ3: How does the model impact the user experience in a given scenario? (uniqueness of responses)

### STUDY
- 2 Part experiment: Gesture Recognition and Speech To Text 
- 4 Curated questionnaires
- Post-study discussion
- Total Study time (~ 45 mins)

### SCENE DEVELOPMENT
_Design Principles:_ 

- **Minimalistic:** Low cost on performance, minimal UI, out-of-the-box performance testing
- **Accessible:** Widely Available and cheap/free hardware/software, ease of use for all demographic
- **Immersive:** Realistic scenario setup, animated avatars

_Tools:_

<img src="/images/itemsmodeltexture.png" width="400" height="auto"><img src="/images/itemlabels.PNG" width="400" height="auto">

- **Meshes/Textures/Illustrations**: Blender, Substance Painter, Photoshop, Illustrator
- **Characters**: Adobe Mixamo
- **Audio**: Pixabay, Elevenlabs
- **Input Type Handling**: OpenAI GPT-4o Chat Completions, Open AI Whisper STT
- **VR Scene Setup**: Unity, Meta Quest 2 VR
- **Scripting and Data Visalisation**: C#, Python

_Quest Design:_

![Detailed Quest Desing](/images/QuestFlowDetailed.png "Detailed Quest Flow Diagram")

1. Calibration
2. Open Interpretation
3. Task Completion


### RESULTS -  Gesture Recognition

- High average response time per pose: 6.83s
- Moderate response accuracy: 73.6%
- Low response uniqueness (unique questions asked by the LLM): 15.1%

_Learning Outcomes:_
-Models are still very slow at image recognition for lifelike NPCs (6.83s)
- Foundation models provide acceptable GR results (73.6%)
- Subsequent runs leads to repetition of content from the LLM
- Good UX design is important to mitigate certain issues
  - Motion sickness concerns for new users
  - Mask lengthy waiting times

