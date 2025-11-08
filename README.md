# mastersThesisTUM
**TOPIC:** Evaluating the Efficiency of Human-AI Interaction in Virtual Reality Using Foundation Models

<img src="/images/outside.png" width="200" height="auto"><img src="/images/inside.PNG" width="200" height="auto"><img src="/images/X.png" width="200" height="auto">


![Detailed Quest Desing](/images/QuestFlowDetailed.png "Detailed Quest Flow Diagram")

**ABOUT:** A VR experience where the user interacts with LLM powered NPCs using gestures

**Motivation:** 

- Test Gestures as a viable input method
- Test image recognition capabilities of LLMs out-of-the-box
- Underresearched topic

**KEYWORDS:** LLM, NPC, Gesture Recognition, VR

**RESEARCH QUESTIONS**

- RQ1:  How accurately can the model identify the user’s gesture?
- RQ2: How quickly can the model read the user’s gesture?
- RQ3: How does the model impact the user experience in a given scenario? (uniqueness of responses)

**STUDY:** 

- 2 Part experiment: Gesture Recognition and Speech To Text 
- 4 Curated questionnaires
- Post-study discussion
- Total Study time (~ 45 mins)

**SCENE DEVELOPMENT**

_Design Principles:_ 

- Minimalistic: Low cost on performance, minimal UI, out-of-the-box performance testing
- Accessible: Widely Available and cheap/free hardware/software, ease of use for all demographic
- Immersive: Realistic scenario setup, animated avatars

_Tools:_

- **Meshes/Textures/Illustrations**: Blender, Substance Painter, Photoshop, Illustrator
- **Characters**: Adobe Mixamo
- **Audio**: Pixabay, Elevenlabs
- **Input Type Handling**: OpenAI GPT-4o Chat Completions, Open AI Whisper STT
- **VR Scene Setup**: Unity, Meta Quest 2 VR
- **Scripting and Data Visalisation**: C#, Python

_Quest Design:_

1. Calibration
2. Open Interpretation
3. Task Completion

**RESULTS:**

_Gesture Recognition_

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

