# Day 1: what are intelligent agents and algorithms
PEAS, what does this vegtable have to do with Data and AI?
<image src="images/peas.jpg">
*Performance measures, Environment, Actuators, and Sensors.*

* **Performance measures:** These are the parameters used to measure the performance of the agent. How well the agent is carrying out a particular assigned task.

* **Environment**: It is the task environment of the agent. The agent interacts with its environment. It takes perceptual input from the environment and acts on the environment using actuators.
* **Actuators:** These are the means of performing calculated actions on the environment. For a human agent; hands and legs are the actuators.
* **Sensors:** These are the means of taking the input from the environment. For a human agent; ears, eyes, and nose are the sensors.

## 1.1 What is an intelligent agent?
**Specifying the task environment:**

    Performance measure: Wining the game of chess
    Environment: Fully obseravble and predictable
    Actuators: Deep blue and Gary Kasparov
    Sensors: Sight of chess board or input by human

**Properties of the task environment:**

    1) Fully observable, This is because all the posiable actions that can happen during the game are there and everything that can be accesed and used can be seen.
    2) Deterministic, All actions go towards the goal of wining and there are no random elements.
    3) sequential, Every player does their turn and so forth untill the goal of one player is reached or a tie.
    4) Dynamic, The oponent and you change the dynamicof the game.
    5) continuous, a sequence of actions untill the goal of winining has been reached
    6) Single agent, This is used because there is only one agent making decision
    7) 
**1.1D** Provide an example of an intelligent agent, and give a PEAS description of the task environment, and characterize it in terms of the task properties listed in Section 2.3.2 (p. 61) in AIMA.

Lets use a translation agent, The problem is that I want something in a differnt langauge and dont have the knowledge. Then if we give the information to lets say Google translate than the operater will follow a set of possible actions to find its goal. In this process it will try to reduce the path cost to get the awnser optimaly.

**1.1e** Compare and contrast the following agent types:

* Simple reflex: This is the simplest of the bunch, it gets an imput from a sensor and give a written down response. For example if it is cold in your house your thermostat can heat up the house.
* Model-based reflex: Follows it's internal represntation of the world to make a desiscion.
* Goal-based:This is an agent that will undertake actions to get to its goal and achieve it. If the agent needs to get an item than it will take the steps to get that item.
* Utility-based: is an agent that wants to get to its goal but also does it in the best way possible,

## 1.2 Conversational AI
**1.2A** Cant watch.

**1.2B** Provide three examples of a chatbot, which you might encounter in your everyday life. Write your answer down.

1. Using NS klanten service to get to a real human but already give information that is neaded.
2. Using a webshop and having a qeustion which most likely can be awnser by an chatbot because the qeustion appears often
3. Talking to anyone on the internet because of [The dead internet theory](https://www.theatlantic.com/technology/archive/2021/08/dead-internet-theory-wrong-but-feels-true/619937/) which basicly theorizes that most of the "human interactions" we have online are all just bots.

**1.2c** Read the article What are Chatbots, which elaborates on the different types of chatbots, - i.e., their architectures, and how they work.

**1.2d** List, and describe the advantages and disadvantages of using the following response generation chatbot types:


 * rule-based:
  This type of a chatbot is very simple and consists of If this than that statements. For example if I ask "What i your name" it could reply with a predetirment "My name is eliza"

| Pros | Cons |
|------|------|
|*Eazy to produce.<br>*doesn't require machine learning or ai     |*Can only reply to written dow replies<br>*has only limted capabilty to awnser qeuston because it can only grab from its database.       |
  * retrieval-based:This form of chatbots use Machine learning models such as NLP to make conversation.

  | Pros | Cons |
|------|------|
|*Can awnser more qeustions than rule based.<br>*Given eneugh data it can reply to almost everything and also procceses more then words like grammer     |*Takes more storage and energy<br>*Cant awnser qeustions by combining information.    |
  * generative:
