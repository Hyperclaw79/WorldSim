# 🎯 Goal - Build a World Simulation Model
The goal of this project is to build a world simulation model that will be used to simulate the outcome of human actions on the world.

What would be the effect of a giving free will to an AI?

Will it lead to a constructive change in the world or destory it?


# ⚠️ Disclaimer
This is a very vague and abstract simulation model.
It's more of a fictional take at the world rather than a real simulation.
Hence, there might be many biased or incorrect technicalities.

💡 Hope the contributors with more experience can improve the models.


# ⚒️ Basic Layout
The main aspect here is the effect of different professions from people of different morality.
Upon convergence, what will happen to the world?
Thus, the modelling will majorily focus only on the humans and actions.
For this reason, need to keep the project at a pretty barebones level immediately.

This leads to 3 major Models:
1. **Resources** - Land, Food, Water and Money
2. **Humans** - People of different professions and morality.
3. **Actions** - Actions that humans can take.


# 💥 Chaos is the Key
Freewill can also be termed as entropy, or chaos, since there are no dedicated laws.
And the very basic unit of such a world would be a *random event*.
Hence, all the actions, moralities, and professions will be **randomly** assigned.

The most naturally existing random function is a Gaussian distribution.
We will be using this function throughout the project.

For trivial assignments, we will just use the out of the box random function.


# 🟢 The Starting Point
Humans have evolved over a long period of time.
Since the project is meant to be a barebones one, we need to limit a lot of things.

Getting the simulation to go from apes evolving to 21st century would be impractical.
Hence, we start with a modern society but from scratch.

Which means, all the humans would start at the same piece of land and without a profession.


# 🏁 End Goal
We will run the simulation for a few epochs and see how many humans are alive, how the resources are distributed, etc.
We need to make sure that the thought process and morality of the humans play a role to achieve the end goal.

We can break the simulation and consider it a destruction if we run out of either resources or humans.
Let's hope this doesn't happen before 5 epochs haha.
(💀 But knowing humans, I won't be surprised if it does...)

# 📦 Resources
Every human needs to consume resources to stay alive.
But if the resources are only consumable, the world will perish in no time.
Hence, we will need to add the possibility of resources replenishing.

We will also add Professions like Farming, which will be able to produce resources.

The simulation shall start with an abundance of resources.


# 🪪 Professions
For the sake of the project, Professions can be divided into 2 main categories:
* **Constructive** - These professions will help the world.
* **Destructive** - These professions will harm the world.
We can also categorized them wrt to resources - producers vs neutral vs consumers.

However, since we are focusing on a modern world, we will have more of the consumers than the producers.
The profession which gets assigned depends on the morality of the human.

> ##  🏢 Organisations
> Since humans, like any species, don't work alone, we need to create organisations.
For the sake of the project, we will determine the heirarchy based on the money they posses.


# 🧍Humans
Humans are the most complex Model in this project.
Since the world outcome depends on the actions they take and the actions depend on the morality of the human, we need to have an elaborate model.

The following need to be considered:
* **Health**
* **Wealth**
* **Morality**
* **Profession**
* **Age**
* **Relations**

They will also have additional fields (mock for a memory)
* **Action List**
* **Event List**


# 🎲 Events & Actions
The driving force of progression in the world are events. 

Each event can either be random or triggered by the action of a human.

Similary, actions can be random or a response to an event.

Examples of events:

1. **Natural Event** - A new food resource is found.
2. **Action Event** - Food resource is consumed as a result of a human's professional task.

Examples of actions:
1. **Natural Action** - A human consumes food.
2. **Event Action** - Humans abandon a land after resource exhaustion.
