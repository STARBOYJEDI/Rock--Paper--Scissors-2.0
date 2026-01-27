# First and foremost, how does rock, paper scissors work.
1. Two players each choose one of rock, paper or scissors simultaneously.
2. Rock beats scissors, scissors beats paper, and paper beats rock.

## Steps to take when generating the code:
### 1. HTML section
1. Create a button class in the html file that lists the options that the user can choose from.
    - Add a result div class that can be called in the js file.
    - Add emojis for each option to make it visually presentable.

### 2. CSS section
1. Create styling code to make the results and elements appear in the center of the page.

### JS section
1. Create an array that lists the options between rock, scissors, and paper.
    - The code can list which option beats the other option and vice versa.
2. Add a Button selection class so that the user can select whichever option between rock, scissors and paper.
3. Create a list of constant variables for the button, column for the results, the computer score and user score.
4. Create a function that will immediately display a result the moment that the user selects whichever option.
5. Continue to display a score whenever an option is chosen from the user and computer.
6. Create a winner condition based on the win condition rule set in the array (rock beats scissors, scissors beats paper, paper beats rock)
7. Create a random selection function for the computer to choose whichever option the moment that the user chooses an option.