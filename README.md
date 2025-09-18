

# Profile Generator

A simple Python program that defines a personal profile using a class and displays key information such as favorite programming language, hobbies, tech stack, GitHub link, and fun facts.

## Features

- Create a profile with personal details.
- Introduce yourself with name, favorite language, and hobby.
- Display your tech stack.
- Show your GitHub profile link.
- Share fun facts about yourself.

## Code Overview

The project contains a Profile class with the following methods:

- __init__(self, name, favorite_language, hobby, tech_stack, github_username, fun_fact): Initializes the profile attributes.
- introduce(self): Prints a self-introduction with name, favorite language, and hobby.
- show_stack(self): Prints the tech stack as a comma-separated list.
- github_link(self): Returns the GitHub profile URL.

Example of creating and using a profile:

```python
if _name_ == "_main_":
    my_profile = Profile(
        name="Arineitwe Sonia",
        favorite_language="Python",
        hobby="Writting novels",
        tech_stack=["Python", "JavaScript", "Git", "MySQL"],
        github_username="soniatech-dev",
        fun_fact="i can turn challenges into books-am already an author"
    )

    my_profile.introduce()
    my_profile.show_stack()
    print("GitHub Profile:", my_profile.github_link())
    print("Fun Fact:", my_profile.fun_fact)

Output

Hi, I’m Arineitwe Sonia. I love Python and my hobby is Writting novels.
My Tech Stack includes: Python, JavaScript, Git, MySQL
GitHub Profile: https://github.com/soniatech-dev
Fun Fact: i can turn challenges into books-am already an author!

Requirements

Python 3.12


How to Run

1. Clone the repository:

git clone https://github.com/soniatech-dev/OOP-Profile-Assignment.git


2. Navigate to the project folder:

cd OOP-Profile-Assignment


3. Run the Python script:

python my_profile.py



Author

Arineitwe Sonia

GitHub:soniatech-dev

Fun Fact: I can run a race in 12 seconds!



