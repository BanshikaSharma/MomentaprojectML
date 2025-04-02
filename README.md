## 🎯 Assessment Overview
* Audio deepfakes pose an emerging threat to digital trust. At Momenta, we're developing robust detection systems to identify manipulated audio content across various contexts. Our interview process strays from whiteboard puzzles or DSA questions - we fundamentally believe in testing for skills that we expect will be needed.
* Your task involves exploring existing research, selecting promising approaches, and implementing a small version of your findings. This take-home task gives you the opportunity to demonstrate your strengths in an open-ended way. If we like your submission, we'll invite you for a technical interview where you'll present and discuss your work in detail.


## 📝 Instructions
#### Part 1: Research & Selection
* Review the following GitHub repository, which contains a curated collection of papers and resources on audio deepfake detection.
 * https://github.com/media-sec-lab/Audio-Deepfake-Detection​
* Identify 3 models/Forgery Detection approaches that you believe show the most promise for our use case:
* Detecting AI-generated human speech
* Potential for real-time or near real-time detection
* Analysis of real conversations
* For each identified approach, provide a brief summary that includes:
-> Key technical innovation
-> Reported performance metrics
-> Why you find this approach promising for our specific needs
-> Potential limitations or challenges
* You are welcome to keep this section concise (point-form and short blurb etc.) the key is the content and your thought process behind selection of models


#### Part 2: Implementation
* Select one of your three identified approaches to implement.
* If you've done previous work in this area, feel free to showcase it
* However, be sure to compare your implementation with the three approaches you selected and highlight the technical differences
* Find and use existing code for this approach if available (this is fully acceptable and encouraged).
* Preferably in a Jupyter notebook or similar format
* Select an appropriate dataset. Example:
* ASVspoof 5
* You are encouraged to find your own dataset as well!
* The shared repo contains additional audio deepfake datasets:
* GitHubGitHub - media-sec-lab/Audio-Deepfake-Detection: Research pr…​
* Perform light re-training/fine-tuning using the dataset.
* This step evaluates your ability to work with large datasets and implement model training
* Actual model performance is not a primary evaluation factor - our focus is on your approach and reasoning


#### Part 3: Documentation & Analysis


* Document your implementation process, including:


-> Any challenges encountered


-> How you addressed these challenges


-> Assumptions made


* Include an analysis section that addresses:


-> Why you selected this particular model for implementation


-> How the model works (high-level technical explanation)


-> Performance results on your chosen dataset


-> Observed strengths and weaknesses


-> Suggestions for future improvements


* Reflection questions to address:


-> What were the most significant challenges in implementing this model?


-> How might this approach perform in real-world conditions vs. research datasets?


-> What additional data or resources would improve performance?


-> How would you approach deploying this model in a production environment?
