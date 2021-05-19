

  <h3 align="center">Egoistic Utilitarianism Netlogo Code</h3>





## About The Project



Egoistic Utilitarianism is the unification of the principles underlying egoism with those of utilitarianism to allow for a way to analyze moral progress and changing conceptions of personhood throughout time. It primarily uses phenomenal intentionalism as the reductive basis for understanding the motivation for action as well as focusing on improving the ability for empathy to both imagine our own future emotional states as well as gain vicariously from the emotional states of others. 

This project is a netlogo simulation exploring the various aspects pertaining to egoistic utilitarianism and how changing the starting empathy of the agents, the radius of interaction, the conditions of their economic exchange, and more could elicit the benefits and problems of this theory. Future hopes for improving the code is by increasing the scope and complexity of the agent's economic interaction as well as potentially include other ethical theories to see how well it does in comparison. 

In order to run the code as is certain things need to be set up in the netlogo browser that primarily aid in extracting information on how the agents are interacting.

In particular:
* Make a plot named "moral progress" that has the Pen name "empathy"
* Make a plot named "phenomenal value" that has the Pen names "instrumental-gain" and "vicarious-gain"
* Make a button that runs the function "procreate"
* Make a button that runs the function "clear"
* Make a button that runs the function "go" while checking "forever" and "disable until ticks start"
* Set the simulation to run based off of ticks rather than continuously to monitor the interactions
* Make a switch containing the global variable "progress"
* Make a slider containing the variable "number-of-sheep"
* Make a slider containing the variable "new-empathy"
* Make a slider containing the variable "greed-maker" that can be set as low as 0.01
* Make a slider containing the variable "radi"
* After these preliminary steps all the basic necessitys will be covered and one can add monitors to track particular variables



### How does it work

Press clear to set up the patches the agents will be moving on. Put the slider "number-of-sheep" on the amount of agents one wants to have for their simulation. Change the "new-empathy" to the starting empathy value one wants these particular agents to have during the simulation. Press "procreate" to have these agents appear on the patches. If one wants agents with different empathy values running in one simulation then one just needs to repeat the last process until they have the number of agents they desire present. Finally press go for the simulation to run. 
