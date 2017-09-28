# Narrative that unfolds the “lives of data and materials” for the Amazon Echo: Tracking Ownership
#### Joyce Choi
#### 09/27/2017
 
(Sidenote: Matt’s writeup said a diagram or a narrative so I just chose to do the narrative.)
 
The Amazon Echo is collecting voice snippets and transcripts based on “hot words”. The Echo starts to record only upon hearing the “hot words” for a few seconds to hear a request. The data is being stored on Amazon’s servers. Although the data is stored on Amazon’s servers, the user has control over this data because through the app that is provided, the user can choose to delete certain voice snippets or all audio snippets all across Amazon’s servers. It’s also possible for the user to turn off the microphone manually. There’s a way for users to mute the mics temporarily for privacy as well. The Amazon Echo gives privacy by not listening and recording all conversations but rather only listens for possible commands when key words are called. The user also has complete control over the recording data. 
 
Most of what Amazon uses is all in-house services, meaning that from the hardware to the services that are run for Alexa, it’s all done through Amazon services. The sensors the Alexa has are a few microphones, a speaker, and a small computer. The hardware isn’t the most special part of Alexa but rather the processing it’s able to do through Amazon’s cloud computing services. The flow of the data starts with the user saying a wake word like “Alexa”. When the user finishes speaking, this device sends the recording over the Internet to Amazon’s servers. The Alexa needs to be connected to the Internet to be able to do the processing it needs to. To process this recording, Amazon goes through Amazon Voice Services. Amazon Voice Services has Natural Language Understanding and Automated Speech Recognition deep learning. When the voice snippet goes to Amazon’s Amazon Web Service (AWS) cloud storage, deep learning is enabled through three layers of the Artificial Intelligence (AI) stack: Frameworks and Infrastructure that have tools like Apache MXNet and TensorFlow, API driven services, and Machine Learning Platforms for data science analysis. The framework also has other tools like Caffe2 (and Caffe), Theano, Torch, Microsoft Cognitive Toolkit, and Keras for more deep learning tools and drivers. Beneath the Amazon EC2 instances, they run on powerful Nvidia graphics processing units (GPU) so that models can be trained faster. Amazon EC2 C4 compute-optimized and M4 general purpose instances for running inferences on the trained model. The results from the user’s request are computed in this AI environment and returned to the user as a result, like an Amazon Order in which case the data also gets sent to the user’s Amazon account or a simple AI aided internet search. If developers also wanted to access this data for an Amazon Alexa applications, if they obtain permission from the user, the developer can access the audio command data  that Alexa receives. 
 
#### Sources: 
https://phys.org/news/2016-12-amazon-echo.html
https://www.wired.com/2016/12/alexa-and-google-record-your-voice/
https://www.cnet.com/news/appliance-science-alexa-how-does-alexa-work-the-science-of-amazons-echo/
https://aws.amazon.com/amazon-ai/

#### Prototype: 
The modification I would make is having an LED light on with a sound so that the user knows exactly when the Amazon Echo starts listening and have another LED light turn on with a different sound so that the user knows exactly when it ends. This way, the user doesn’t have to consciously worry that some bits of a sensitive conversation was recorded.

##### Link to prototype:
https://www.tinkercad.com/things/iQioiTheEQf-funky-blad-curcan/editel?sharecode=j5QnspRC5ilrxNdyQL_Zf3GJ_EONHIwja2sGmdzrrRI=

