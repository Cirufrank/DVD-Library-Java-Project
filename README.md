# DVD Library Console App

![](https://media.giphy.com/media/l3vReTmBHnPsC4oHS/giphy.gif)

DVDs.. a thing of the past... a forgotten piece of technology that's soon to fade into the digital ether. Is what they all said. But you.. you're not them... NO... you're a blue ray connoisseur. You enjoy the classics and respect the intiricacies of the digital versatile disc. This application was made for you! You have a beautiful collection of DVDs, but alas, you've been craving a console application to help you keep track of them, to share with, to write about the DVDs that made you laugh, cry, see the world in a new light. Well look no further my friend. The DVD library CRUD app is here.

## How It's Made:
Using Java, the MVC architectural paridigm, and file storage for data persistence, I created a CRUD app that allows users to create, read, update, and delete textual DVD information.

## Lessons Learned:
<ul>
  <li>Maintaining loose coupling through applications through the use of dependency injection helps ensure our application's services do not rely so healivy on each other that if one service goes down the other is completely inoperable</li>
  <li>Separating concerns within classes and keeping our classes cohesive and responsible for one major task is an important step to ensuring code is maintainable, cohesive, and organized</li>
  <li>Java interfaces help us declare the methods that we'd like to be implemented in order to accomplish a task such as recieving input and dispalying output to a user, and this allows us the freedom to implement these interfaces in multiple different ways, thus making our applications felixble and ale to interface more cohesively with other systems</li>
  <li>Java's strong typing helps shield developers from error by throwing compile errors whenever a variable is assigned an unexepcted value or a method returns an unexpected data type
  </li>
</ul>

## To be implemented:
<ul>
  <li>Add a service layer responsible for the application's business logic so that the controller no longer accesses the data access object directly.</li>
  <li>Add JUnit tests to the application to help avoid and reveal errors while ensuring the the code is well enough to test easily.</li>
  <li>Include other data storage implementations and user interface</li>
</ul>
