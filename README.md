# Proposal Animation

## **Overview**
This Python script utilizes the Turtle graphics library to create a simple animated drawing that represents the phrase "I Love U" along with stick figures for a male and female character. The animation is interactive and will display until the user clicks to exit.

## **Requirements**
- Python 3.x
- Turtle graphics library (usually included with Python installations)

## **Installation**
1. Ensure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).
2. Save the provided script as `proposal_animation.py`.

## **Usage**
1. Open a terminal or command prompt.
2. Navigate to the directory where `proposal_animation.py` is saved.
3. Run the script using the command:
   ```bash
   python proposal_animation.py
   ```
4. A Turtle graphics window will open displaying the animation.

## **Functionality**
- **draw_i()**: Draws the letter "I".
- **love(fill='pink')**: Draws a heart shape filled with the specified color.
- **draw_u()**: Draws the letter "U".
- **stickman(gender='m')**: Draws a stick figure. The gender can be specified as 'm' for male or 'f' for female.

## **Animation Steps**
1. The letter "I" is drawn.
2. A red heart is drawn to represent love.
3. The letter "U" is drawn.
4. A male stick figure is drawn.
5. A female stick figure is drawn.
6. A pink heart is drawn.
7. A message placeholder is displayed for the user's favorite person's name.

## **Customization**
- You can change the fill color of the hearts by modifying the `love()` function's `fill` parameter.
- To change the name displayed at the end, modify the string in the `pen.write()` function.

## **Exiting the Animation**
- Click anywhere on the Turtle graphics window to exit the animation.

## **License**
This project is open-source and available for personal use. Feel free to modify and distribute as needed.


