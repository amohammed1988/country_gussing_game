# Creating a Region Riddle game using Python.
# Put Your Geographical Knowledge to test.
Step (1): Three variables are defined to store the name of the country, its capital, and its region:

 A.  country_name.
 
 B.	country_capital.
 
 C.	country_region.

Step (2): Several variables are initialized:
# guess to store the user's input.

 
 
 A.	guess_count: to keep track of how many guesses the user has made.
 
 B.	guess_limit: is set to 4, which means the user has a maximum of 4 attempts for each question.
 
 C.	out_of_guesses: is initially set to False to indicate that the user has not run out of guesses.
 
 D.	guess_score:  to keep track of the user's score, which is initially set to 0. 

# The code uses loops to guide the user through the game for each of the three questions (country name, capital, and region):


Step (3): Country Name Guessing:  A while loop checks if the user's guess (guess) is not equal to the country_name, and if the user hasn't exceeded the guess limit.
The code checks if the entered guess is equal to the country_name. If it is, the user is rewarded with a score increase of 100, and a message is printed to inform them that they guessed correctly. Otherwise, a message is printed to ask the user to try again.
The guess_count is incremented to keep track of the number of guesses.
If the guess_count reaches the guess_limit, the out_of_guesses flag is set to True, and a message is printed to indicate that the user is incorrect, followed by another question.



Step (4): Country Capital Guessing: A new loop starts for guessing the country capital, following a similar structure to the previous section. This time, if the user reaches the guess limit, a message is printed to inform the user that they didn't guess the capital correctly.
Country Region Guessing: Another loop is used to handle guessing the country region, similar to the previous sections. If the user reaches the guess limit here, a message is printed indicating that they didn't guess the region correctly. After all three questions, there is a final check to see if the user ran out of guesses (out_of_guesses is True). If so, an insulting message is printed to chastise the user.


Step (5): Finally, based on whether the user has won or lost, a message is printed to display the correct answers and the user's score. 
The code structure is mostly the same for each of the three questions, with minor variations in the messages and what's being guessed. 
The user is given multiple chances to guess the correct answers before losing the game. The code also keeps track of the user's score throughout the game.




# To host your Region Riddle game project on GitHub, you can follow these steps:

# Step (1): Create a GitHub Account:
If you don't have a GitHub account, create one at GitHub.

#Step (2): Install Git:
If you haven't already, you'll need to install Git on your local machine. You can download it from git-scm.com.

# Step (3): Create a New Repository:
Log in to your GitHub account.
Click on the "+" sign in the upper-right corner and select "New repository."
Fill in the repository name, a description, choose visibility (public or private), and select options as needed.
Click "Create repository."


# Step (4): Set Up Git:
Open a terminal on your local machine and configure Git with your name and email:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your@email.com"


# Step (5): Clone the Repository:
To work with the repository on your local machine, you need to clone it. Use the "Code" button on your GitHub repository to get the clone URL, then execute the following command in your terminal:
bash
Copy code
git clone https://github.com/yourusername/repositoryname.git


# Step (6): Add Your Project Files:
Copy your Python code files into the cloned repository folder on your local machine.


# Step (7): Create a README:
Create a README.md file in the repository directory to provide information about your project, its usage, and any other details. You can use Markdown formatting to structure your README.


# Step (8): Add and Commit Your Changes:
In your terminal, navigate to your repository folder and use the following commands to add and commit your changes:
bash
Copy code
git add .
git commit -m "Initial commit"


# Step (9): Push Your Code:
Push your code to the GitHub repository:
bash
Copy code
git push origin main
Replace main with the appropriate branch name if you are using a different branch.


# Step (10): GitHub Settings:
In the GitHub repository settings, you can configure additional options, such as branch protection rules, collaborators, and more.


#Step (11): Publish Your Repository:
Once you've added your code and configured your repository settings, it's ready to be published. People can now access and clone your project from GitHub.

# Step (12): Keep Your Repository Updated:
As you make changes to your project, remember to add, commit, and push those changes to keep your GitHub repository up to date.

Now your guessing game project is hosted on GitHub, and you can share it with others. You can also use GitHub to collaborate with others, manage issues, and track changes to your code over time.
