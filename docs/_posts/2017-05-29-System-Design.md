---
layout: post
title: "System Design"
date: 2017-05-29
---

# System Design

Hello Everyone! :)
Welcome to our third blog, hope you enjoyed our second blog!!    Over the past few weeks we have been working out on our project with respect to the System Design. With respect to all the user stories which we have mentioned in our previous blog, we have come up with the following Interaction Diagrams and Class Diagrams which would help you all understand our project in a better way. We Shall be discussing about the Development strategies as well.

## Interaction Diagrams

The purpose of the Interaction Diagram is 
1. To capture the dynamic behaviour of the system
2. To describe the message flow in the system
3. To describe the structural organization of the objects 
4. To describe the interaction among objects

Keeping all the above points into consideration, we have come up with the below Sequence Diagrams for two of the user stories.

<p align="center">
Sequence Interaction Diagram for Login Activity
</p>

![InteractionDiagram1]({{site.baseurl}}/InteractionDiagram/Interaction_Diagram_for_Login_Activity.pdf "InteractionDiagram1")

<p align="center">
Sequence Interaction Diagram for Income Transaction
</p>

![InteractionDiagram2]({{site.baseurl}}/InteractionDiagram/InteractionDiagram_for_Income_transaction.pdf "InteractionDiagram2")

## Development strategies

According to the SCRUM’s founder “the team is utterly self-managing”.
The process of Development involves the below Work Flow.

![workflow]({{site.baseurl}}/images/Workflow1.png "workflow")
			[Reference:https://www.google.de/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&ved=0ahUKEwjtwu6vmY7UAhVEfywKHRGQBt8QjRwIBw&url=https%3A%2F%2Fkrify.co%2Fsteps-to-follow-to-avoid-mistakes-during-mobile-app-development%2F&psig=AFQjCNEU3uAQWGVe1Am3uHx6GdKA4ZgWag&ust=1495909804752959]

This will have to be monitored in number of ways where in each person in the team makes sure that he/she completes their task which has been assigned to them and also makes sure that they continuously monitor the team’s overall performance. This makes sure that there would be no discrepancies in the later stages and also would help maintain clean SCRUM methodology. 

To Keep a Track of all the work which has already been completed, those which are in progress and also which are yet to be implemented we use **ZENHUB** dashboard. This is more sufficient way to know the progress of the project.

![zenhub]({{site.baseurl}}/images/Zenhub.png "zenhub")
            [Reference: https://github.com/DBSE-teaching/isee2017-hackslash#boards?repos=87943612]  
			
## Summary of Changes 

We have been following our initial plan to make sure that we accomplish  all the user requirements which we proposed. We met the customer in person and discussed about our implementation plans and also our initial step towards developing the application.
After he reviewed our application, he provided us his feedback and asked us to make few changes which are listed below:

1. The filter options would be rather be in "Settings" than in the "Menu"" since this would again depend on the customer. This can be used only if he wants to filter the expense/income accordingly with respect to different categories or the date or might be with respect to the income type. An additional field should also be mentioned in the filter option so that it would be helpful for him if he has to retrieve information of his choice.
2. The Amount that the user enters as his income/expense should set to a default currency type and should also be displayed as Three letter word and not the currency symbol.i.e. for EURO we would have to give it as EUR. This will also be more easy to understand since the users might not be aware of all the currency notations.
3. The notes section would rather be a text field which should be able to take maximum characters. This would again be user friendly.
4. An overview of the past data should also be a part of the home screen. This would help the user to track  his recent expenses.

We are now more inclined towards making our final product a successful one and also would consider the above feed back and would work on it accordingly.

That is all for now !:)

<p align="center">
Thank You for visiting our Third blog!! Stay tuned for our next blog. 
</p>




