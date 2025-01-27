### **State Review Activity: Favorite Color**

**Objective:** Review how to initialize and update state in a React component, with a bonus option to explore in-line styles.

---

#### **Instructions:**

1. **Create a New React App**
   Start by creating a new React app. Open the `App.jsx` file.

2. **Your Goal**
   - Display the text **"My favorite color is: [color]"**.
   - Add three buttons: one to change the color to **purple**, one to **red**, and one to **yellow**.
   - Update the displayed text dynamically based on the chosen color.

3. **Starter Code**
   Replace the contents of `App.jsx` with the following starter code, then complete the missing parts:

   ```jsx
   import './App.css'
   import { useState } from 'react'

   const App = () => {
     // Step 1: Initialize state for the favorite color
   

     const handleChangeColor = (newColor) => {
       // Step 2: Update the state with the new color
    
     }

     return (
       <>
         {/* Step 3: Display the favorite color */}
         <h1>
           My favorite color is: 
         </h1>
         {/* Step 4: Add buttons to change the color */}
         <button onClick={}>
           Change Color to Purple
         </button>
         <button onClick={}>
           Change Color to Red
         </button>
         <button onClick={}>
           Change Color to Yellow
         </button>
       </>
     )
   }

   export default App
   ```


#### **Bonus Challenges:**
1. Add an in-line style to the `<h1>` tag to dynamically change the color of the text to match the current favorite color.
   - Example:
     ```jsx
     <h1 style={{ color: color }}>
       My favorite color is: {color}
     </h1>
     ```
2. Instead of hardcoding the colors into the buttons, use an array of colors and `.map()` to generate buttons dynamically.
3. Add a new button that resets the favorite color to the default (e.g., "blue").
