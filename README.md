# Pixel Square AI (Genetic Algorithm)

AI Assignment (Genetic Algorithm)

REPORT (2023-24)

QUESTION
Task 1 
You are required to implement a program that takes an image as its input and generates the same image using N number of squares. You need to implement this using Genetic Algorithm. 
Step 1: Generate a canvas (or pixel array) which have the same dimensions as your input image. Let h and w be the height and width of the input image respectively. 
Step 2 (Generate Population): Generate N random squares in the square. Each square is defined by its position in the canvas, its RGB value, and its opacity. All these values should be initialized randomly.
Step 3 (Perform Crossover): In this step, you will combine two or more squares in your population set to generate new children (squares). You can perform crossover however you want. It is recommended to try different techniques and mention the result in the report. 
Step 4 (Mutation): You can try variable strategies for mutation. For example, Squares with high objective function values will be more likely to be mutated. If mutation makes the square a lot worse compared to current then you may ignore the mutation. 
Step 5 (Selection): In this step, you will select N-squares for your next population. Selection can be done in many ways. 
1.	You can select N-best squares from the new generation.
2.	You can select N-best squares from the new and previous generations. 
3.	You can select N-best squared from the new and previous generations based on their probability (lower objective function value should have a high probably of being selected). 
4.	You can add some constraints on selection to avoid picking all squares from the same patch.
