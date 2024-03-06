# HomeReview
Participation à Hacklitycs 2024, Georgia Tech, Atlanta, USA
Hackaton renommé de Data Sciences et d'IA avec plus de 1100 participants et 300 projets.

Hacklytics 2024 Project <p>

We first chose to work on the NSA challenge but what we are delivering today is a mix between the Assurant challenge and the Healthcare track. <p>

Assurant x Healthcare

Crossing of the first Assurant challenge, the Healthcare track and the Finances track.

We chose to cross-reference risk data linked to the general condition of a home, associated with health risks due to pesticides in our geographical area, and the real estate situation in the neighborhood by assessing the property's land value.

We took the initiative of using real values in addition to those provided for image analysis. We have chosen to use French data, but the model is technically usable with the right dataset in any country.<p>

You will therefore have the choice of an address in France to use the model.

For the insurance part, we used the images supplied, which we had previously sorted into two categories: global building exterior image and image with interior or exterior details. We also used datasets recording earthquakes over 100 years, from which we developed a probabilistic model. <p>
For the health section, we used 20 years of pesticide air concentration data. <p>
For the financial part, the supervisor imports the expected price per square meter. Depending on the house's defects, the price per square meter is modified.

Our idea is to offer tailor-made insurance, including the general state of health of the home and associated risks. We will propose health recommendations based on the general state of health of the home.

First, we assess the home's geographical location: a seismic risk study of the area is carried out.<p>
Using data from the last 100 years, we study the likelihood of an earthquake in the next six months that could impact the home. With the age of the house entered by the supervisor, we calculate the number of earthquakes the house has experienced.<p>

In a second step, a random photo of the building's exterior is selected: the supervisor will have a list of visible potential defects to choose from. Then three photos of the details of the house will be shown: the supervisor will again have to choose the visible defects.

In the third stage, we looked at whether the house in which the people lived was located in a pesticide risk zone over a 20-year period.<p>
Combined with the fact that the general state of health of the house was poor.<p>
Assurant could therefore offer higher insurance prices.<p>

The application creates a PDF report ready to hand over to insurance specialists.<p>
For each visible problem detected by the supervisor in the photos, a personalized
recommendation is proposed. For example, if a large crack is visible, a call to an expert is strongly recommended.

Opening: <p>
If the hackaton had lasted longer, here's what we could also have implemented:<p>
Computer vision: so you don't need a supervisor<p>
Automatic calculation of price per square meter based on historical data, prices: to assess real estate tensions in the area <p>
Calculation of a health insurance price, based on the serious risks posed by the state of the home to its inhabitants: e.g., the presence of mold or traces of fire can have harmful effects on health. <p>
Use of a Web service to automate the writing of reports on all real estate advertisements posted on the Internet: enable faster customer relations, with a file prepared even before the customer has taken any action (advanced prospecting).
