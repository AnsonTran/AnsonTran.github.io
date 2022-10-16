# Team Blue Yorkers

## Members
Anson Tran: trananso
Joe Liu: liuji112
Collin Chan: chancol7
Jiale (Leo) Yu : yujiale
Xuen Shen: shenxuen
Houde (Archie) Liu: liuhoude

## Links to Prototype
Link to Task #1: [Have saved locations for Origin and Destination](https://drive.google.com/file/d/1HQg7QQh92eCpPQ6xr8XvzgGyw4lav1wR/view?usp=sharing)
Link to Task #2: [Purchase Tickets Online (Desktop Interface)](https://drive.google.com/file/d/182zkfDRFtcggOBPCwuXzBaQuzX7bTzYI/view?usp=sharing) 
Link to Task #2: [Purchase Tickets Online (Phone Interface)](https://drive.google.com/file/d/1ImCs5o96-8TdOzbR9qcnz80yHlKarpY3/view?usp=sharing) 
Link to Task #3: [Review Bus Routes](https://balsamiq.cloud/sjadrse/p9n3ihp) 

## Task #1: Have saved locations for Origin and Destination
### Description
As outlined previously in the Phase 2 report, the ability to add and use saved locations is one of the main tasks. From our survey results in the previous phase, 80% of respondents were willing to register and save user information on their YRT account. On top of that, 60% of respondents agreed that they often found themselves inputting the same locations for either the Origin or Destination or both in the Trip Planner Tool. Currently, the YRT Trip Planner Tool only saves the recent locations the user has searched for using the respective browser’s session. This means that when a user restarts their browser or uses a different device, it does not save their recent searches and would have to re-enter the same address if needed. Therefore, this task allows for users to conveniently use previously saved locations or add new locations to reuse in the future. It also adheres to the rule of “Reducing short-term memory load” for the user, which is outlined in the Eight Golden Rules of Interface Design, as users who are not familiar with an address will not have to remember information from another display. Since the saved locations are only used in the Trip Planner Tool, the majority of the task is performed inside the Trip Planner Tool. Users will be able to access and save new locations when they access the dropdown menu in the “Enter Origin” and “Enter Destination” text input. 

### Step-By-Step Instructions
Use Previous Saved Locations on Trip Planner Tool
* Login/ Signup for an account online with YRT.ca
* Navigate to the Trip Planner component
* Click on either “Enter Origin” or “Enter Destination”
* Review and click on the saved locations prior to use it (if there exists any)  

Add Additional Location(s) on Trip Planner Tool
* Login/ Signup for an account online with YRT.ca
* Navigate to the Trip Planner component
* Click on either “Enter Origin” or “Enter Destination”
* Click on “+ Save Additional Location” button at the bottom of the dropdown menu
* Navigate to the “Save Additional Location” Popup at the center of the screen
* Select the location type of this new location
* Enter the address of the new location in the “Enter Location” text input
* Click on “+ Add” to save the new additional location

## Task #2: Purchase Tickets Online
### Description
As we discussed in our phase 2 report, 92%(56/61) of participants in our survey experienced forgetting their Presto card. Hence we decided to introduce a feature that allows users to purchase and access tickets through the YRT website. We’ve identified three locations where users may want to access the purchase ticket page, one on the trip planner, the main page, and on the itinerary details. We believe these pages to be the most frequently visited by our users, which we will evaluate in our next phase. This feature also serves to help users better understand the fare pricing of the YRT system, since they can purchase tickets for the whole family, and the page will calculate the total payment price.

The online ticket consists of a barcode, which users can use on PRESTO card readers on buses. This way, bus drivers do not have to be trained to read the online ticket. Users can view their tickets on their user profile page, and download the ticket for use when boarding. 

### Step-By-Step Instructions
* Navigate to the Trip Planner component
* Click the “buy ticket” button
* Select the number of tickets you want to buy
* Enter payment details and purchase the ticket
* Download the ticket
* When taking the bus, open it on your phone and tap it like a Presto card

## Task #3: Review Bus Routes
### Description
According to the results collected from the survey, 27% percent of respondents claim that they identify themselves as customers with disabilities, the elderly or pregnant women. Considering the rule of “Seek universal usability” which is outlined in the Eight Golden Rules of Interface Design, we provide help for them when designing the interface. In most cases, they need accessibility support such as Priority and Courtesy Seating and other accommodation because they have to travel with mobility aids, visual impairments or baby strollers. Our survey indicates that 70% and 65% of responses show the need for punctuality rate and congestion degree respectively. Currently, the YRT only supports searching information such as the schedule of a specific route. No more information is provided.

Therefore, this task allows users to post reviews regarding the crowdedness and punctuality of the routes and also get such information when planning their trip.

As this task involves reviews provided by the users. In order to keep the posts clean and prevent malicious and fake reviews, users have to login first.

### Step-By-Step Instructions
* Search for chosen bus
	* Click on search bar
	* Enter route number of chosen bus
	* Click on the search icon button
* See reviews and ratings from other riders
* Rate and write your own review
	* View the current info of the route
	* Rate the route in terms of crowdedness and punctuality
	* Give optional text review
	* Select the time when you take the route
	* Click on the Submit button to submit the review

## Evaluation of Prototype
### Evaluation of Task #1
We will evaluate a multitude of features that are a part of this task, those being the login/signup feature, using saved locations from the user profile, saving new locations to the profile, and some quality of life features such as the dark mode for the user profile. We will be evaluating based on several criteria including functionality, how user-friendly it is, and how self-explanatory it is.

The way that we will evaluate the task is by letting users try out our prototype in a controlled environment, where they will have the ability to click around the prototype and attempt to perform this task with all the included features. At first we will let them simply try out the prototype with 0 information given to them beforehand in order to evaluate how self-explanatory the prototype is, and then assist them if they get confused. We will also perform usability testing on this task such as Can-you-break-this tests, in order to evaluate it’s functionality and discover some issues that may occur during regular use.

### Evaluation of Task #2
Our team will conduct an evaluation of our prototype, by collecting a mixture of quantitative and qualitative data. Our data collection method will be through a semi-structured interview with 3-4 participants. This will provide us with detailed and rich data, but at the risk of high bias, variability, and less reproducibility of results. Additionally, we will conduct pre-interview and post-interview questions which will give us an idea about our sample. Given our target audience, we will aim to have users who have various levels of experience using the YRT website and/or Google Maps, and familiarity with the Presto system.

During the interview, users will be asked to perform a series of tasks, for a short timed period. Users will be asked to think aloud, sharing their thoughts of the prototype as they navigate through the system. Interviews will be taped, which will allow us to annotate the screen captures, and identify moments of breakdown in communication through communicability evaluation tags. Additionally, we can observe the number of errors made during each exercise for quantitative data across our sample. Post-interview questions will follow a general guideline, but focus on each user’s experience with using the prototype. 

For data analysis, we’ve chosen to follow the Grounded theory, making the use of coding in order to identify common categories that users brought up during the post-interview questions. 

### Evaluation of Task #3
We will start the evaluation by testing the interface in a controlled setting. The participants will be users who identify themselves as customers with disabilities, the elderly or pregnant women. Usability testing will be conducted along with videotaping participants performing tasks. Though some of the participants might not be technically advanced, they might get confused while trying to complete the task. We decided not to not interfere with the participants and ask them to provide detailed information of the problem or confusion they encountered during the following interview or survey. Next, a post-test interview will be conducted among all the participants. This includes survey and focus group discussions. We will then invite participants to think aloud about what they are doing as they are performing the task based on the interview results. Lastly, as more formal expert reviews have proven to be effective, our team will try to conduct Heuristic evaluation guided by the set of recognized usability principles if possible.