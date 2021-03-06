# Blockle
Blockle is the new amazing software that utilizes of kids insatiable curiosity and their propensity for learning with touch to help them learn how to code.

Inspiration:
We were inspired by the experiences many of us had volunteering to teach young children. A lot of kids learn better when more of their senses are involved. Therefore, they are able to understand concepts better when they have a physical representation. We decided to take the idea of block coding and bring it into real life.

What it does:
Our project uses "physical blocks" that resemble those in block coding. Each block has a QR code and the student must put them together to create a solution to get through a maze. They can then take a picture and upload it, and our program reads the QR codes to make a block move through the maze. This allows the student to both physically put together their code and see the output of their work.

How we built it:
Each of the mazes were created using HTML, JavaScript, and CSS and we used Flask as our back end framework. There is a form on each page to upload images and we used OpenCV to read the QR codes from the image. The data from OpenCV was passed to our HTML file. It was outputted as a list of steps on a screen and used by our JavaScript code to make the block move through the maze accordingly.

What's next for Blockle:
For this hackathon, we just used QR codes on a piece of paper instead of creating actual 3D blocks. For our next step, we would want to create those blocks and test them. In addition, we would want to add more puzzles and possibly randomly generate puzzles in the future. Lastly, we would want to deploy the app.

Built With:
- CSS
- Flask
- HTML
- JavaScript
- OpenCV
- Python
