# [2024 ICME Grand Challenge] Multi-Modal Video Reasoning and Analyzing Competition (MMVRAC) 

Given the enormous amount of multi-modal multi-media information that we encounter in our daily lives (including visuals, sounds, texts, and interactions with their surroundings), we humans process such information with great ease – we understand and analyze, think rationally and reason logically, and then predict and make sound judgments and informed decision based on various modalities of information available. 

For machines to assist us in holistic understanding and analysis of events, or even to achieve such sophistication of human intelligence (e.g., Artificial General Intelligence (AGI) or even Artificial Super Intelligence (ASI)), they need to process visual information from real-world videos, alongside complementary audio and textual data, about the events, scenes, objects, their attributes, actions, and interactions.

Hence, we hope to further advance such developments in multi-modal video reasoning and analyzing for different scenarios and real-world applications through this Grand Challenge using various challenging multi-modal datasets with different types of computer vision tasks (i.e., video grounding, spatiotemporal event grounding, video question answering, sound source localization, person reidentification, attribute recognition, pose estimation, skeleton-based action recognition, spatiotemporal action localization, behavioral graph analysis, animal pose estimation and action recognition) and multiple types of annotations (i.e., audio, visual, text). This Grand Challenge will culminate in the 2nd Workshop on Multi-Modal Video Reasoning and Analyzing Competition (MMVRAC). 

## CHALLENGE DETAILS

**Participants are required to register their interest to participate in the Challenge.**
**Please register for the competition here: [https://forms.office.com/r/yW5NWdWXxN](https://forms.office.com/r/yW5NWdWXxN)**

* Participants will take on any one of the tracks in [CHALLENGE TRACKS](#challenge-tracks). This means tackling any one of the tasks in the corresponding dataset (e.g., Spatiotemporal Action Localization using Chaotic World dataset). The models will be evaluated using the published test set and evaluation metrics found in each respective paper. Please see [CHALLENGE TRACKS](#challenge-tracks) section for more details on each task. 
  * The Grand Challenge is open to individuals from institutions of higher education, research institutes, enterprises, or other organizations.
    * Each team can consist of a maximum of 6 members. The team can comprise individuals from different institutions or organizations. 
    * Participants can also participate as individuals.
    * Participants / Each team can take part in more than one track. 
    * Participants are required to register their interest to participate in the Challenge here: [https://forms.office.com/r/yW5NWdWXxN](https://forms.office.com/r/yW5NWdWXxN)
  * Participants are required to submit their results and runnable codes by the [Challenge submission deadline](#challenge-timeline). 
    * Participants are to adhere to the terms and criteria stated in the [SUBMISSION GUIDELINES](#submission-guidelines). 
    * The methods and codes need to be open-source and reproducible. Please see [SUBMISSION GUIDELINES](#submission-guidelines) for more details.
    * Participants can utilize one or more modalities provided in the dataset for the task.
    * Participants can also use other datasets or pre-trained models etc to assist in the model development. 
  * All participants who successfully complete the Challenge by the Challenge deadline will receive a Certificate of Participation. 

* The top three teams of each track will have to present at the Grand Challenge workshop, either at the Winner’s Flash Talks (Oral) or poster and networking session. This is so that the workshop participants can learn about the various approaches that are useful in tackling the task at hand.
  * These top teams are also required to submit a paper submission (See [Challenge submission deadline](#challenge-timeline)). 
    * The Challenge results will be released on 28 March 2024. They will have to submit their papers on 06 April 2024 UTC 23:59:00. 
  * The top three teams will receive the Winners' Certificate and their work (and link to their code repository) will be featured on this website.

## CHALLENGE TRACKS

The video multi-modal datasets contain footages of different views and modalities such as ground camera views, top-down views from UAV, fisheye views, and night vision views; of different levels of object densities and occlusions (i.e., chaotic scenes); of differing tempos that may require split-second analysis (i.e., chaotic scenes, animal movements); and of various visual compositions (e.g., textures and camouflage, dynamic background, motion blur). The tasks range from traditional computer vision tasks (e.g., action recognition, pose estimation) to multi-modal tasks (e.g., sound source localization, video question-answering, spatiotemporal event grounding). These tasks shall be useful for both the community vision community (to develop more robust models) as well as the respective community (to design autonomous applications). 

The evaluation metric(s) for each task follow the metric(s) indicated in the original paper. In cases whereby there are more than one evaluation metric for the task in the paper, the combination of all metrics will be taken into consideration to evaluate the robustness of the model. 

The Challenge Tracks are based on the four video multi-modal datasets are as follows: 

[Chaotic World](https://github.com/sutdcv/Chaotic-World): This challenging multi-modal (video, audio, and text) video dataset that focuses on chaotic situations around the world comprises complex and dynamic scenes with severe occlusions and contains over 200,000 annotated instances for various tasks such as spatiotemporal action localization (i.e., spatially and temporally locate the action), behavioral graph analysis (i.e., analyze interactions between people), spatiotemporal event grounding (i.e., identifying relevant segments in long videos and localizing people, scene, and behavior-of-interest), and sound source localization (i.e., spatially locate the source of sound). This will promote deeper research into more robust models that capitalize various modalities and handle such complex human behaviors / interactions in dynamic and complex environments.

Track #1: Spatiotemporal Action Localization

Track #2: Behavioral Graph Analysis

Track #3: Spatiotemporal Event Grounding

Track #4: Sound Source Localization

[UAV-Human](https://github.com/sutdcv/UAV-Human): This human behavior analysis dataset contains more than 60,000 video samples (bird-eye views of people and actions taken from a UAV) for pose estimation (i.e., predicting the keypoints of the individual), skeleton-based action recognition (i.e. identifying the action of the individual based on keypoints), attribute recognition (i.e. identifying the features / characteristics of the individual), as well as person reidentification (i.e. matching a person's identity across various videos) tasks. This will facilitate human behavior analysis from different vantage points, and will be useful for the development and applications of UAVs. 
  
Track #5: Pose Estimation

Track #6: Skeleton-based Action Recognition

Track #7: Attribute Recognition

Track #8: Person Reidentification          

[SUTD-TrafficQA](https://github.com/sutdcv/SUTD-TrafficQA): This traffic event-based multi-modal video reasoning dataset about the traffic scenes contains over 10,000 RGB video samples and 60,000 questions and answers about the traffic scene for video question-answering (i.e., answer questions according to the given videos) task. This will encourage deeper research into more robust models with low latency that can analyze human and vehicle behaviors in dynamic split-seconds scenarios, and will be useful for development of safer autonomous vehicles. 

Track #9: Video Question-Answering for Setting 1/4

[Animal Kingdom](https://github.com/sutdcv/Animal-Kingdom): This animal behavioral analysis dataset comprises 50 hours of long videos with corresponding text descriptions of the scene, animal, and behaviors to localize the relevant temporal segments in long videos for video grounding (i.e., identifying relevant segments in long videos), 50 hours of annotated video sequences for animal action recognition (i.e. identifying the action of the animal), and 33,000 frames for animal pose estimation (i.e., predicting the keypoints of the animal) for a diversity of over 850 species. This will facilitate animal behavior analysis, which is especially important for wildlife surveillance and conservation.  

Track #10: Video Grounding

Track #11: Animal Action Recognition

Track #12: Animal Pose Estimation for Protocol 1 (All animals)

## CHALLENGE TIMELINE  
Date                          | Event

----------------------------- | -------------------------------------------

05 February 2024 UTC 00:00:00 | Challenge starts                         
**25 March 2024 UTC 23:59:00**| **Deadline for [Challenge submission](#challenge-submission-link)**
28 March 2024                 | Release of Challenge results
06 April 2024 UTC 23:59:00    | Deadline for submitting invited papers
11 April 2024 UTC 23:59:00    | Notification of paper acceptance
01 May 2024                   | Deadline for camera-ready submission of accepted paper
01 May 2024                   | Author Full Conference Registration


## SUBMISSION GUIDELINES 
### Code submission 
* Participants can utilize one or more modalities provided in the dataset for the task.
* Participants can also use other datasets or pre-trained models etc to assist in the model development. 

* Participants should submit the link to their code repository.
  * Participants can upload their project (codes and models) to GitHub, Google Drive or any other online storage providers.
  * Participants are required to provide **runnable and reproducible codes**, and in particular, **(1) easy means to read in the data** directly by simply replacing the test data directory _DIR_DATA_TEST_ and **(2) easy means to seamlessly run the inference code with trained model**.
    * The codes should be in the form of notebook (Jupyter Notebook) or Python files (.py files).
    * The methods and codes need to be open-source and reproducible by others.
    * This includes simple instructions to run the evaluation code, list of Python libraries / dependencies / pre-trained models that are required to be installed for the codes to run, and other relevant information / instructions / pre-trained models / codes etc to ensure the seamless execution of the codes.
    * The model should not be trained on any data from the test set. 
  * In cases whereby there are multiple submissions for the same task, only the last submission will be considered.
  * In the event of same results for the same task, the team with the earlier upload date and time will be considered as the winner. 
    
### Paper submission for the top submission of each track
* The paper submission will follow [ICME 2024 guidelines](https://2024.ieeeicme.org/author-information-and-submission-instructions)
* The top three teams of each track will be notified by 28 March 2024 as stated in [Challenge submission deadline](#challenge-timeline).
  * These teams will need to submit the paper by 06 April 2024 as stated in [Challenge submission deadline](#challenge-timeline), submit the camera-ready paper by the author deadline, register for the conference (01 May 2024), and present at the conference; otherwise they will not be included in IEEE Xplore.
    * Length: Papers must be no longer than 6 pages, including all text, figures, and references. Submissions may be accompanied by up to 20 MB of supplemental material following the same guidelines as regular and special session papers.
    * Format: Workshop papers have the same format as regular papers. 
  * A Grand Challenge paper is covered by a full-conference registration only.
  
## CHALLENGE SUBMISSION LINK
**Please submit your results here: [https://forms.office.com/r/DAULcDhhYY](https://forms.office.com/r/DAULcDhhYY)**

## ORGANIZERS 
* Jun Liu, Singapore University of Technology and Design
* Bingquan Shen, DSO National Laboratories and National University of Singapore
* Ping Hu, Boston University
* Kian Eng Ong, Singapore University of Technology and Design
* Haoxuan Qu, Singapore University of Technology and Design
* Duo Peng, Singapore University of Technology and Design
* Xun Long Ng, Singapore University of Technology and Design

## CONTACT 
Please email kianeng_ong [AT] mymail.sutd.edu.sg for any enquiry.

## PAST ITERATION OF CHALLENGE
Information and results of the previous iteration of the Challenge (i.e., 1st Multi-modal Video Reasoning and Analyzing Competition at 2021 ICCV) can be found here: [https://sutdcv.github.io/multi-modal-video-reasoning](https://sutdcv.github.io/multi-modal-video-reasoning)
