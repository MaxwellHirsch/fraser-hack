# SMS Symptom Analyzer - Fraser Hackathon
## Inspiration
Our app is targeted at the “Patient Centered Service” challenge of the Fraser Health Hackathon. We want to increase accessibility and the ability for communities to identify care that they may need and where to get it.

We wanted to create a medical diagnoses app that was accessible by everyone with a phone, and everyone within cellphone towers.

## What it does
Through our service, anyone with a cell phone can initiate an adaptive conversation around symptoms they are observing. The service follows-up with questions based on probability of a particular condition and once a likely condition is determined, provides that information and offers a nearby location for follow-up.

 ## How we built it
In order to implement our service, we leveraged the following services:
* __Twilio__ API for all SMS communication
* __Intermedica__ API for symptom analysis and interview protocol
* __Azuqua__ for all logic and integration between the services

## Challenges and what we learned
Coming into the hackathon, our goal was to create a connected patient experience by addressing the gaps resulting from disparate data sources that house patient information. After speaking with resources available at the hackathon, it became clear that the possibility of connected systems, even with the introduction of new standards such as FHIR, were a far-off dream.

## Accomplishments we are proud of:
* __Accessibility__ - Our service is available to anyone with a mobile phone can use our service, regardless of whether or not they have internet access.
* __No Written Code__ - We did not write a single line of code for this service. By leveraging other commercially available APIs and platforms, we have no infrastructure 

## What’s next for text based medical diagnoses
* __Increased Accessibility__ - We want to include additional language support, such as Chinese or French, as well as having voice automated response for those who are visually impaired.
* __Additional Inputs__ - We want to increase the range of inputs that could be directed at our service. This includes devices such as the Amazon Echo, Google Home, etc.
* __Better Location Recommendation__ - Integrate with clinic, hospital, and other medical service data to better target recommended providers.
