# Principles-of-Autonomy-and-Decision-Making
#Assignment-01
This assignment is graded and compulsory. Here, you build your custom environment using OpenAI gym as per the instructions provided in the practical sessions.

Grading (Total points = 20):
Completeness (10 points) - Your environment should have all the necessary components like .reset(), .step(), .render(), .close() methods along with observation, actions, rewards, info and so on.
Creativity (8 points) - You will be graded for your creativity. This can also include a theme, for example, Thanos (your agent) trying to get a Gauntlet (goal) by evading the Avengers (hell-states). Creatively describe your reward function, the architecture of your grid, rendering, colours, fonts and so on.
Clean code (2 points) - You will be graded based on the readability of your code such as a proper naming convention, doc strings, and comments wherever necessary. Stick to the PEP8 convention. 
Rules:
You have to submit the assignment before the deadline to get a grade. You can use your 2 days free pass.
If you are not using images: You should submit one .py file with the "env_<student user id>.py" naming convention. For example, "env_chk3541.py".
If you are using images: Please submit the assignment as one .zip file with the naming convention "env_<student user id>.zip"


#Assignment_2
Assignment 2 is a worksheet which is your math assignment. Please solve the worksheet to receive a grade for the assignment.

Total points = 10

Rules:

The document is a Word document where you can enter the results
Please use the "Equation" option in Word to write math equations
NOTE: 
Please take a pic of the calculations you have done and upload the pics along with the solved Worksheet. Please keep the format of the image as .png. When you upload your images please upload them as <student_id>_<image_no>.png for example, chk3541_1.png, chk3541_2.png and so on.
Please upload your solution as <student_id>.docx for example chk3541.docx.
NOTE: If the number of files exceeds 20 or if you are using Python files or Excel sheets to solve the assignment, then please submit your assignment as a <student_id>.zip file which includes everything that you used to solve the assignment.


#Assignment-03
This assignment is graded and compulsory. Here, you will build and train a Q-learning agent for the custom environment that you built in Assignment 1. 

Grading (15 points):
Building a Q-learning agent (10 points) - Here, you adapt the Q-learning agent to the custom environment you built in Assignment 1. You decide the state representation and design your Q-table. You code a logic for exploration vs. exploitation. 
Successfully training a Q-learning agent (5 points) - Here, you tune the hyperparameters and successfully train a Q-learning agent. You should save the trained Q-table as a NumPy array as "q_table.npy"


Rules:
You have to submit the assignment before the deadline to get a grade. You can use your 2 days free pass.
We expect you to submit a .zip file. As explained in the practical session, the .zip file must contain "main.py",  "padm_env.py", "q_learning.py" and "q_table.npy". Please add your custom environment in the "padm_env.py" module. Please keep the name of the .zip files as "q_learning_<student user id>.zip". If you have any doubts regarding the files, please refer to the Week 10 practicals on Moodle or contact us for clarification. 


#Assignment-04
This assignment is graded and optional. Here, you will adapt the DQN algorithm that you learnt in Week 11 practical session to the custom environment that you built for Assignment 1. You are allowed to make modifications to your environment and make it more challenging for the DQN agent.

Grading (5 points):
Adapt the DQN algorithm to your environment
Train the DQN agent, generate a training curve and save the model weights as a .pth file
Write a code to test your agent by loading the pre-trained weights


Rules:
You have to submit the assignment before the deadline to get a grade. You can use your 2 days free pass.
We expect you to submit a .zip file. As explained in the practical session, the .zip file must contain "main.py",  "padm_env.py", "DQN_model.py", "utils.py", "training_curve.png" and "dqn.pth". Please add your custom environment in the "padm_env.py" module. Please keep the name of the .zip files as "dqn_<student user id>.zip". If you have any doubts regarding the files, please refer to the Week 11 practicals code and Week 10 lecture slides on Moodle, or contact us for clarification. 
