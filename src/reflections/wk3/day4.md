# Day 4 - Working In MVC With Complex Data & Array Methods

## Daily Journal

Afternoon Challenge - https://alecvictory.github.io/darryl-store/

Read Advancing with JS > The Observer Pattern and answer the following questions.

What problems does the Observer Pattern seek to solve?

it updates parts of a page in response to certain events that the data provides. it uses push-pull in the code to keep everything in sync

What are the three mechanisms of the observer pattern?

Subscribe Method
Unsubscribe Method
Broadcast Method

Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

The proxy state uses the observer pattern by getting targets and properties then setting those targets and properties. These functions then return to update the DOM

