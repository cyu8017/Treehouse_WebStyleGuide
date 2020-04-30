### Instructions

In this project, we've provided complted index.html and styles.css files. You will be resonsible for converting the CSS into Sass by splitting the code into several Sass partial files. You will also look for repeated values (length units, colors, etc.) throughout the CSS and store them in Sass variables. After completing the project, you'll have a useful Sass micro-framework to quickly prototype other websites. 

### Befor you start

### Project Instructions 

To complete this project, follow the instructions below:

- Structure your folders: 
    - Start by creating a scss folder inside of your project's root folder. All of your Sass files, including sub-folders to      organize them will go in here. 
    - Create sub-filders inside of the scss folder for your base, components, and utilities partials. 
    - Create a css folder inside of the project's root folder. This is where your output css will be generated. 

- Create the file structure: 
    - Change the normalize.css file into a Sass partial and save it to the base folder.
    - Create a typography partial and save it to the base folder. 
    - Create at least 4 different component partials that group together the major sections of the site. For example: navigation, grid, and button partials. 
    - Inside of the utilities folder, create variables and mixins partials. 
    - In each of your scss sub-folders, create an _index.scss file. These files will be used to import individual partials from each subfolder. 

- Setup Sass to watch for changes: 
    - From the terminal, navigate to your project's root folder. 
    - Run the command sass -- watch scss:css so that Sass will continuously update your output CSS as you make changes to your Sass. 
    
- Create your variables: 
    - Looking through the resources/css/styles.css file, identify common colors and sizes that can be converted to variables. 
        - Create at least 5 color variables. 
        - Create a variable that stores the size of the media query breakpoint. 

- Add styles to the typography partial: 
    - Scan the resources/css/styles.css for styles related to font family, size and weight. 
    - Pay particular attention to those that are targeting tag names like a, h1, body, or the universal selector *. 
    - Add these styles into the typogrphy partial. 

- Move styles into components: 
    - Transfer the remaining CSS into their respective components. For example, any class selectors that begin with grid, column, or rows could go in the grid component. 
    - Be sure to update any styles that use color with the Sass variables you created in the previous step.  
