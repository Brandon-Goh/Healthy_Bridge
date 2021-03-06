# Healthy Bridge
### Hack The North 2018 Indico API Prize Winner
*Bridging the gap between doctors and patients in order to combat mental illness' and save lives.*

![Healthy Bridge logo](https://brandongoh.me/static/img/healthy.png)

Healthy Bridge is a web based application that scans information from the clients social media accounts (i.e facebook), searching for certain keywords, explicit objects in photographs, filters, and analyzes the overall tone of their page. After all this information is extracted, key information or outliers, is displayed on the website accessible to the doctor. University of Waterloo’s Hack The North Indico API Prize Winner 2018

## What I did:

 - Created a website from clients’ social media accounts to analyze information that warns their doctor if the patient is likely struggling with a mental illness using Node.js, HTML, CSS and various APIs

 - Developed reusable backend components using Python and machine learning algorithms to determine illnesses

- APIs Used: Facebook Graph Explorer, Colorgram, Indico, Clarifai

## Inspiration
The inspiration behind our revolutionary hack was the increased negligence of mental health in our society today. Mental health is an extremely important part in attaining an excellent quality of life. Rates of depression have risen by more than 18% since 2005, and a lack of a strong support system for individuals with mental illness, means many do not get the treatment they need to live healthy, productive lives. We decided to tackle this issue by creating a website that will alert doctors of their patients mental condition in advance, so they are able to give them the support they need to recover.

## What it does
Our hack is presented in the form of a website, to connect a doctor and their patient. Our website scans information from the clients social media accounts (i.e facebook), searching for certain keywords, explicit objects in photographs, filters, and analyzes the overall tone of their page. After all this information is extracted, key information or outliers, is displayed on the website accessible to the doctor. This development greatly speeds up the process of the doctor/therapist asking initial questions to feel out the patient. Now, the doctor is able to get a feel for the patient and have information if a patient is at risk for depression or mental illness, therefore he/she is more prepared to deal with this sensitive case. All in all, our website aims to bridge the gap between doctors and their patients, in order to provide patients with the care that they need as soon as possible.

## How we built it
Starting with the backend, we used python and several of it’s machine learning frameworks that allowed us to predict possible dangerous topics related to each post. The posts were extracted using a Facebook API (graph explorer) and analysed using several functions made by us. By using other python frameworks we were able to get the prominent colours and saturation of pictures posted by the patient. This information can then be processed by estimating if a patient’s pictures indicates them struggling through a mental illness such as depression. The frameworks used include: Colorgram for colours, Indicoio for text and machine learning, and Clarifai for object detection. For example we used Clarifai’s API to detect objects that are considered to be unsafe or unnatural such as knives, guns and other weapons. By highlighting these objects, it is to be noted that they may be suffering from suicidal thoughts, severe anxiety and violent or addictive behaviour. Finally, the doctor can help the patient according to their professional judgement and the information given by the website.

## Challenges we ran into
The challenges our group encountered were mainly in extracting the data from Facebook and finding a way to gather the information all in one place. We were using different languages for different aspects of our data, therefore it made it difficult to transfer files and assemble the information in one place. Finding the perfect API to execute our ideas proved to be difficult, as each API did things slightly different. Our group also had member with little or no hackathon experience, so it was a new learning experience for our team. This meant the initial preparation and programming proved a bit more challenging than we imagined. Overall, we managed to persevere and overcome all our challenges because we worked effectively together as a team, communicating and dividing the workload.

## Accomplishments that we're proud of
We are really proud that our group was able to come together and work so well together to make such a beneficial app. It was a huge accomplishment that we were able to plan and execute an idea we were all passionate about. It was exceptional that we were all able to get along and build such a polished product as a team for the first time. Overall, we are very grateful to attend such a huge and excellent hackathon and create something that we can be proud of.

## What we learned
By attending Hack the North we were able to learn a lot more about the world of programming, business, and technology. We especially enjoyed talking to all the sponsors, as we believe they helped expand our knowledge on different job industries and different job expectations. Another highlight was interacting with other eager hackers at the event. We were able to learn a lot more about the school and social life at Waterloo by talking to UW students. We made it our goal to socialize and talk to as many people as we could to really absorb as much information as we could at Hack the North. At the hackathon, we learned a great deal about the business and technology industries, programs and applying to university, and also improved my programming skills, learning from my teammates and other hackers competing.

## What's next for Health App
The next step for Healthy Bridge is to market our website to a larger demographic, specifically targeting it towards the municipal healthcare system. Our website is universal in its application, therefore many different organizations can take advantage of our service. We would also have to further develop our business plan to realistically reach out to the municipal, provincial, and national government to see our website in full effect. There is also room for improvement regarding our website and its functionality. We will continue to add new features and improve the existing mechanics. Though the system has its imperfections, t could be beneficial for bridging the gap between patients and doctors which can intern save many lives. Overall, Hack the North was just the start of our innovation to help social justice. We plan to devote more time into making our website a reality and have it become the standard mental healthcare service across Canada. 


## Devpost:
https://devpost.com/software/healthapp-pb3umv



## Created by:

Brandon Goh:

- Linkedin: https://www.linkedin.com/in/brandon-goh/

Jordan Chow:

- Linkedin: https://www.linkedin.com/in/jordanchow905/

Amir Braham:

- Devpost: https://devpost.com/AmirBraham

Nima Sadri:

- Devpost: https://devpost.com/nimasadri11