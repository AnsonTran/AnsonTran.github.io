# Team Blue Yorkers Proposal

## Members
Anson Tran: trananso
Joe Liu: liuji112
Collin Chan: chancol7
Jiale (Leo) Yu : yujiale
Xuen Shen: shenxuen
Houde (Archie) Liu: liuhoude

## Team Expectation Agreement
Methods of communication (email, phone, texts, ....)
* Discord
Communication response times (email, phone, texts, ....)
- Members are expected to respond within a day 
Regular Meetings (frequency of meetings, whether all meetings are mandatory,...)
- Once a week (meeting time to be determined during each week)
Running meetings (when, where, face to face vs. online, who takes minutes, ...)
- Face to face after tutorials, online otherwise
- Each member takes turns with meeting notes and minutes 
Meeting preparations (whether preparation is needed, what to prepare,...)
- Members are expected to be able to provide an update on their developments along with reasonable estimation on whether or not they will be able to complete their assigned tasks
Division of work (how to divide work, who will decide who does what, ...)
- Delegate work during meetings on first-come-first-serve basis
Submitting work (when to submit, who will submit, who will review the submission,...)
- When to submit: latest 1 hour before submission is due
- Who will submit: Collin
- Who will review: Anson, Houde (Archie), Joe, Jiale (Leo), Xuen
Contingency  planning  (what  if  a  team  member  drops  out,  what  if  a  team  member  is sick for a significant  period  of  time,  what  if  a  team  member  consistently  misses  meetings, what  if  a  team member is academically dishonest, ...) We suggest that in these cases, a team promptly seeks help from the TA.
- Member drops out: Inform the TA and reassign outstanding tasks during meeting
- Team member is sick: Inform rest of team and help divide his work
- Consistently misses meetings: Inform the TA
- Academically dishonest: Inform the TA, review their work next time

We accept these guidelines and intend to fulfill them (sign below):
* Anson Tran: trananso
* Joe Liu: liuji112
* Collin Chan: chancol7
* Jiale (Leo) Yu : yujiale
* Xuen Shen: shenxuen
* Houde (Archie) Liu: liuhoude

## Purpose
Public transit is a big part of many people’s everyday lives, with York Region being the home to over 1.1 million people. Aside from answering FAQs and the background of YRT, the York Region Transit website ([https://www.yrt.ca](https://www.yrt.ca/en/index.aspx)), provides a tool to help users plan their trips with YRT. The trip planner tool helps users navigate around the region using the YRT transit services. In addition, public transport has been faced with more emerging competitors (ie. Uber) which provides a much better experience. Therefore, it is essential to have an easy-to-use system to maintain and even increase the level of usage. 

## Description
First of all, there is no clear indication of a Trip Planner component and it is not user intuitive. Instead of positioning the tool in the center, it is accessed through a cramped box on the left. The input of origin and destination is also designed so that the origin has to be inputted before the destination without any notice to users. Moreover, the time and date input components are not dynamically sized, making certain buttons unresponsive and rendering the function useless.

Second of all, once the user finishes planning the trip, the Itinerary component is also riddled with poor design choices. Each route is not separated clearly, making it difficult for the user to distinguish the respective button for each route at first glance. Many transit applications (ie. Google Maps, Transit Now …etc) have a feature that you can tap on the route to get more detailed route information, but this component only allows tapping on the "details'' button and “down arrow” button to retrieve information. The YRT transit is not built on standardization.

The "down arrow" is approximately 7mm in mobile devices which is insufficient. As recommended by Parhi (2006), "target sizes should be at least 9.2 mm for single-target tasks and 9.6 mm for multi-target tasks in order to keep the dimensions of the targets as small as possible without decreasing performance and user preference". On top of that, when the user double taps the itinerary component, it will disappear entirely. This is not generally intuitive and causes more unnecessary time and effort from the user, ruining the user experience.

Third of all, the Map component is not user intuitive. Since routes are marked with their respective bus route color, there are largely varying colors for all bus routes, making it difficult for users with color vision deficiencies to spot each route. On top of that, once the user clicks on the fullscreen button to enlarge the screen, all the other components with more detailed information disappear. This is very inconvenient for users without the best vision, especially more senior users, who often have the need to use public transit. 

## Target Audience
The York Region Transit (YRT) website is targeted to a wide spectrum of the population that use the YRT transit services across the York region.

The website provides necessary transit information serviced by YRT to get from one destination to another, this includes the fares, travel times and routes, along with other filters including wheelchair options, walking distances and number of transfers, which is beneficial for seniors and people with disabilities. 

The intended target users of this website are mainly tourists and new residents in the York region since they are considered new visitors and need assistance on commuting. For instance, employees that move to the region want to know the best transportation method to get to their workplace, they will have to look up the information on the website. While residents in this area and frequent commuters, such as 9-5 workers and students, are likely familiar with the routes for their daily commute, they could also be potential users. This website would be useful for when they want to travel to a specific destination for other purposes such as entertaining, friends visiting or reunion, etc. 

## Proposed Solution/Meeting needs
From the Trip Planner component to the Map component, the YRT website has presented a variety of visibility and usability concerns for users. 

### Trip Planner Component
1.  The website is inconsistent when it comes to different devices due to their differing screen sizes. This can be solved by changing the website’s css to use the user’s current window size instead of a fixed value, allowing the site to dynamically adjust all the margins and constraints based on their screen sizes.
2.  The fonts are not big enough for senior citizens. Population aging is a worldwide phenomenon that results from longer life expectancy and low fertility rate. It will be the same for the audience of the users of YRT. There will be a significant number of users with vision problems when they get older. It is important to take their user experience into account. As Jayroe (2012) stated, with the perceived ease of use of tablets among older users,  they are more likely to access online health information resources as tablets provide them with a more friendly interface (bigger font size and the accessibility of interactions). A solution to this problem would be to add a special switch version button which switches the current interface to a bigger font version.
3.  There are two buttons within the component, one is “Plan My Trip”, and the other one is “More options”, which have exactly the same color and style. (See appendix 1.2) This makes it hard for the user to distinguish which one is the primary action button. For better usability, more important UI components should have more visual weight than less important ones, according to Schlatter (2013). In this specific case, “Plan My Trip” button needs higher prominence in order to attract users’ attention, as it is being used more often than the other one. A possible solution would be to change the “More options” button into a different style with lower visual weight.

### Itinerary Component
1.  Closing the Itinerary component by double clicking. Doubling clicking on an area to close the entire component is not a common practice with user interfaces. This could result in additional unnecessary action required by the user to get back to their previous progress with the component and can easily be done by accident. This can be solved by completely removing this functionality.
2.  The target size of the “down arrow” is not big enough, it would increase user error rate on operations, one way to solve it would be to follow the other transit application, which is allowing users to tap on the route to get detailed information.

### Map Component
1.  High contrast colors and Indicators (refer to Appendix 1.1) - According to the National Eye Institute (2019), color blindness affects 1 in 12 men, and “may get worse as you get older - often because of cataracts”. The current colors used in the app make it hard to distinguish between current routes and alternative routes, which is best showcased when viewing the website in monochrome. Directional arrows on the routes are coloured in white, which makes it difficult to see on the light coloured map. According to guidelines set by the W3C Web Accessibility Initiative (2018), adjacent non-text colors should have a contrast ratio of at least 3:1. Additionally, the guidelines mention that color should not be the only means of conveying information. 
2.  The Map component hides all other supporting components when fullscreen mode is activated. According to the report “The cost of vision loss and blindness in Canada”, over 3.1 million Ontarians are living with severe blinding diseases. (Canadian Council of the Blind, 2021) This equates to roughly 20% of the population of Ontario, which means a significant amount of the population is struggling from issues with their vision. On top of that, the map might not be able to provide a clear view of the entire route if it is very long. As a result, this can be solved by retaining all the other components containing detailed information back to the Map component. (ie. Itinerary component, Search component, Bus Stop component, Service Advisories component)

## Literature Review

### Inconsistency with Different Device Screen Sizes
This citation primarily focuses on talking about different screen resolutions and page layouts, in order to maximize the initial visibility, readability, and aesthetics. It supports our solution because it talks about the different screen resolutions/sizes that web pages should be designed for, and to “not design solely for a specific monitor size because screen sizes vary among users”. One of the pieces of advice given in the article is what we are basing our solution for this problem off of, which is to “use a liquid layout that stretches to the current user's window size (that is, avoid frozen layouts that are always the same size)”.
    
Nielsen, J. (2006, July 30). Screen resolution and Page Layout. Nielsen Norman Group. Retrieved May 30, 2022, from [https://www.nngroup.com/articles/screen-resolution-and-page-layout/](https://www.nngroup.com/articles/screen-resolution-and-page-layout/) 

### High Contrast Colors
This citation offers guidelines to follow in order to support people with vision impairments. Specifically, it is concerned with graphical components adjacent to each other. As a minimum threshold, these should have a contrast ratio of 3:1. Elements rendered on the map need to communicate information about the bus route, and on a light coloured background, light colors should not be used.
    
National Eye Institute. (2019, July 3). Color Blindness. Retrieved May 30, 2022, from [https://www.nei.nih.gov/learn-about-eye-health/eye-conditions-and-diseases/color-blindness](https://www.nei.nih.gov/learn-about-eye-health/eye-conditions-and-diseases/color-blindness)

W3C Web Accessibility Initiative. (2018, June). Web Content Accessibility Guidelines 2.1 (1.4.11). https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html

### Bigger Fonts
The problem and solution proposed are mainly targeted at senior citizens. By providing a comparison of senior technology users’ interaction with the interface of iPad tablets and desktop computers. People can better understand how they interact with each technology. Therefore, designers can take the advantage of the 2 kinds of interfaces to provide better human-computer interaction. And among them, one of the improvements is that the font size is more friendly for old adults to interact with on tablets.

Jayroe, T. J., & Wolfram, D. (2012). Internet searching, tablet technology and older adults. Proceedings of the American Society for Information Science and Technology, 49(1), 1–3. [https://doi.org/10.1002/meet.14504901236](https://doi.org/10.1002/meet.14504901236)

### Statistics of Ontarians with Severe Blinding Diseases
The main issue proposed for the full-screen functionality has to do mainly with the visual aspect of the user experience. This does not necessarily mean only senior users are affected as the source suggests. Therefore, by allowing the ability to continue using the Map component along with other supporting components, users with visual impairments could benefit from the experience.

Canadian Council of the Blind. (2021). (rep.). The cost of vision loss and blindness in Canada. Deloitte Access Economics. Retrieved May 30, 2022, from [https://www.fightingblindness.ca/wp-content/uploads/2021/05/Deloitte-Final-Acc-of-VL-and-Blindness-in-Canada-May-2021.pdf](https://www.fightingblindness.ca/wp-content/uploads/2021/05/Deloitte-Final-Acc-of-VL-and-Blindness-in-Canada-May-2021.pdf).

### Primary Button Style
In this book, the author introduces the principles and practices of visual usability for apps and websites. The book offers guidelines and design patterns to improve visual usability in real practices in UI design. As suggested by the author, UI components with higher usage rate should have higher visual weight than the others.

Schlatter, T., & Levinson, D. A. (2013, October). Visual usability principles and practices for designing Digital Applications. Morgan Kaufmann Publishers.

### Down Arrow Target Size
The article talks about an experiment on the error rate and speed related to a target size on mobile. It stated that the target size for a single target pointing task should be at least 9.2mm without decreasing performance and user preference. Selecting a route is an essential task in a transit application and it's also a single target pointing task. The result supports our proposal on changing the "down arrow" target size. 

Parhi, Karlson, A., & Bederson, B. (2006). Target size study for one-handed thumb use on small touchscreen devices. ACM International Conference Proceeding Series; Vol. 159: Proceedings of the 8th Conference on Human-Computer Interaction with Mobile Devices and Services; 12-15 Sept. 2006, 203–210. [https://doi.org/10.1145/1152215.1152260](https://doi.org/10.1145/1152215.1152260)
## Appendix

![](https://lh6.googleusercontent.com/P7-f3s-e7hw_NK4_Qyuj7z-e8q3GDVVYL5PNU5IJeiQnnwT4LtGML3jQWeQF-wCp2DshDD0X2yEJ_oAeXKThbPzetdxv-c2VTPsuuFXf7iVBxENn6VK4dEWBKdHGlhwcjJW00O69UTpJYg_6BHIfiA)
> (Appendix 1.1: Contrast between colors makes it difficult to determine the current route)

![](https://lh5.googleusercontent.com/4flq_4Cxyl22BrlHIzNcxzyKT0MXaWOqB_MDA6PC-ovKqjzaxmMSCvd_fD73KfRw0mN5_MV7kFU90SrJkJhGbp6OhOEKhkA2V0j9PWk2IbzcWR5IUNkoby_CJS_P2qqSgIPK7jH8PyoPFUFv7b4hhg)
> (Appendix 1.2: Two buttons with same color and style make it hard to differentiate)