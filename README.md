#Description:
The application enables users to enter inputs into a inquirer prompt in order to generate a logo "logo.svg" file which contains the users desired results as an SVG image.

#The Challenge:
Build a Node.js command-line application that takes in user inputs to generates a SVG logo and saves it as "logo.svg" file. In addition, create a walkthrough video that demonstrates its functionality and the passing of all of the tests.

#User Story
AS a freelance web developer
I WANT to generate a simple logo for my projects
SO THAT I don't have to pay a graphic designer

#Acceptance Criteria
GIVEN a command-line application that accepts user input
WHEN I am prompted for text
THEN I can enter up to three characters
WHEN I am prompted for the text color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I am prompted for a shape
THEN I am presented with a list of shapes to choose from: circle, triangle, and square
WHEN I am prompted for the shape's color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I have entered input for all the prompts
THEN an SVG file is created named `logo.svg`
AND the output text "Generated logo.svg" is printed in the command line
WHEN I open the `logo.svg` file in a browser
THEN I am shown a 300x200 pixel image that matches the criteria I entered

#Generated LOGO
<svg version="1.1" xmlns="http://www.w3.org/2000/svg" width="300" height="200"><circle cx="50%" cy="50%" r="100" height="100%" width="100%" fill="WHITE"><text x="150" y="125" font-size="60" text-anchor="middle" fill="GREEN">RED</text></svg>


#Video DEMO
https://drive.google.com/file/d/1EuyJQM6dCWVIulW83PlTfGTy014b3rpp/view

#Usage Instructions
Open the cloned repository in any source code editor e.g. Visual Studio Code.
Open integrated terminal on index.js
Enter “node index.js” in the command line
Through sequential order within the command line interface - the user will be presented with npm inquirer questions - the user will provide a response to each question and proceed.
Once completed a SVG file named "logo.svg" will be created.
At your discretion, you may rename the "logo.svg" file to the file name of your choice.
(Optional) Regarding future use, you may alter the prompted questions within the index.js to best suit your needs.
(Optional) The SVG Logo Maker serves as a foundation so you are not limited to altering the files (as you have my permission) to create the best possible "logo.svg" file.
