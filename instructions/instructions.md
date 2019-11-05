## Log in with your Amazon Developer Account

Go to [developer.amazon.com](https://developer.amazon.com/) and click "Developer Console" on the upper right:

![](https://github.com/suma-gitrep/alexa-08-02/blob/master/images/developer.png)

Now either sign in with your Amazon Developer account or create a new one.

![](https://github.com/suma-gitrep/alexa-08-02/blob/master/images/amazonsignin.jpg)

Great! You should now have access to your account. This is what your dashboard of the Amazon Developer Console looks like:

![](https://github.com/suma-gitrep/alexa-08-02/blob/master/images/console.jpg)

##Create a new Skill

Now it's time to create a new project on the developer console. Click on the "Alexa" menu item in the navigation bar and choose "Alexa Skill Kit" to access your Alexa Skills:

![](https://github.com/suma-gitrep/alexa-08-02/blob/master/images/alexaskill.jpg)

Let's create a new Skill by clicking on the blue button to the upper right:

![](https://github.com/suma-gitrep/alexa-08-02/blob/master/images/newskill.jpg)

The next step is to give the Skill a name:

![](https://github.com/suma-gitrep/alexa-08-02/blob/master/images/createnewalexaskill.jpg)

## An Introduction to Alexa Interaction Models
Choose an Invocation Name
Create a HelloWorldIntent
After successfully creating the Skill, the screen looks like this:

![](https://github.com/suma-gitrep/alexa-08-02/blob/master/images/skillbuilder.jpg)
As you can see in the left sidebar, an Interaction Model consists of an Invocation, Intents, and Slot Types.

But first, let's take a look at how natural language understanding (NLU) with Alexa works.

## An Introduction to Alexa Interaction Models
Alexa helps you with several steps in processing input. First, it takes a user's speech and transforms it into written text (speech to text). Afterward, it uses a language model to make sense out of what the user means (natural language understanding).

A simple interaction model for Alexa consists of the following elements: Invocation, intents, utterances, and slots.

## Invocation
The Invocation Name is the one that is used by your users to access your Skill:


## Intents
An intent is something a user wants to achieve while talking to your product. It is the basic meaning that can be stripped away from the sentence or phrase the user is telling you. And there can be several ways to end up at that specific intent.


## Utterances
An utterance (sometimes called user expression) is the actual sentence a user is saying. There are often a large variety of utterances that fit into the same intent. And sometimes it can even be a little more variable. This is when slots come into play:

## Slots
No matter if I'm looking for a super cheap place, a pizza spot that serves Pabst Blue Ribbon, or a dinner restaurant to bring a date, generally speaking it serves one purpose (user intent): to find a restaurant. However, the user is passing some more specific information that can be used for a better user experience. These are called slots:
