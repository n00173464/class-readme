# class-readme
 
<h1> Unreal Blueprint Testing </h1>
<h2> Yue Lang </h2>

<h3> Variables: </h3>

<p>
This project demonstrates the use of variables through multiple formates including use of int, float, bool and string 

</p>
<img width="391" alt="variables" src="https://github.com/user-attachments/assets/57dd2880-eab7-43dc-97ec-226f74699d4a">

<p>Variables are properties that hold a value or reference an Object or Actor in the world.</p>

<ul>
  <li>In Unreal Engine Blueprints, INT are used to store whole numbers and integers.</li>
  <li>Float is a datatype in blueprints that allows you to store fraction or decimal values.</li>
  <li>Boolean data type allows you to store either True or False. These 2 values can also be represented using numbers 0 and 1 respectively.</li>
 <li>String datatype allows you to store any text, it can be a number, name, place, message, special symbols, etc. You cannot do any numerical operations on this datatype like Integer and Float if you decide to store numeric values in a string datatype.</li>
</ul>


<h3>Accessing Game Objects/Actors and Components</h3>

![outliner](https://github.com/user-attachments/assets/510322d2-03e2-4b41-ab6a-7f420dc17782)


<ul>
 <li>Actors represent objects in your game world, such as characters, enemies, props, lights, and cameras. They are the primary entities that exist in a level and can be manipulated, interacted with, and controlled through code.</li>
 <li> Components are modular units that provide specific behaviors and functionalities to Actors. They can handle tasks like rendering, physics, animation, collision detection, and more.</li>
</ul>
<p>
 The World Outliner in the Unreal Editor allows you to visualize and manage all actors in your scene. You can use it to select actors in the outliner and manipulate actors using the viewport tools to move, rotate, or scale them.
 You can access components attached to Actors using Blueprints.
</p>

![actor](https://github.com/user-attachments/assets/a52daa04-719c-4812-85e4-45c6199442ca)


<h3>Referencing Other Scripts/Blueprints</h3>

<p>
 In Unreal Engine, you often need to make Blueprints communicate and interact with each other. This involves referencing objects or components within one Blueprint from another. 
</p>

<ul>
 <li> Using Variables: The simplest method is to create a variable within one Blueprint that holds a reference to an instance of another Blueprint.</li>
 <li>Using Events: Events provide a mechanism for Blueprints to communicate with each other without requiring direct references or interfaces. They allow one Blueprint to send a message to another Blueprint, which can then respond accordingly.</ul>

