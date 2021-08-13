## User Interface
   Android User Interface is mostly defined inside and activity_----.xml file
- UI can be designed in 2 ways
    1. We can either code in xml
    2. Or we Can design it from Drag and Drop

### Design Tab
- It can be divided into four important parts
 1. Display/Output
 2. Pallet(Left Top)
 3. Component Tree(Left 2nd from Top)
 4. Attributes[also knowns as Property] (Right Top)

 ### ID
 - ID is used to connect the UI with the backend(kt/java file)
 - Each and every ID should be diffrent in a single form

 ### text
 - text is attribute which denotes the value inside a component

 ### hint
 - hint is a attribute which is only visible when text is empty


 ## Layout
 - An Android application can be executed on a TV 64' inch
 - An Android application can be executed on a 6' inch table
 - An Android application can be executed on a Smart Phone(Variable Size)
 - An Android application can be executed on a Samrt Watch
 - To maintain This desginig part on each type of screen there are mostly 4 types of layout used
    1. Constrained Layout
    2. Linear Layout
    3. Table Layout
    4. Frame Layout

#### Constraint Layout
- It will decide where our component should be with respect to top, left, right or bottom

#### Linear Layout
- This layout is second most commonly used layout
- In this layout components uses 100% width of screen.
- They are stacked from top to bottom or left to right according to the orientation given.