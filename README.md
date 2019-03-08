# machineLearning Projects 

# Car Evaluation

**Data Set Information:**

Car Evaluation Database was derived from a simple hierarchical decision model originally developed for the demonstration of
DEX, M. Bohanec, V. Rajkovic: Expert system for decision making. Sistemica 1(1), pp. 145-157, 1990.)

The model evaluates cars according to the following concept structure: 


**Car Evaluation is based on parameters**

* **PRICE** overall price 
* **maint** price of the maintenance 
* **TECH** technical characteristics 
* **COMFORT** comfort 
* **Doors** number of doors 
* **persons** capacity in terms of persons to carry 
* **lug_boot** the size of luggage boot 
* **safety** estimated safety of the car 



**Attributes:**

* buying: vhigh, high, med, low. 
* maint: vhigh, high, med, low. 
* doors: 2, 3, 4, 5more. 
* persons: 2, 4, more. 
* lug_boot: small, med, big. 
* safety: low, med, high. 

**To predict the car evaluation I have used adaboost classifer which have given 93% accuracy.**
