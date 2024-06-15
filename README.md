# AI Math Notes
![AI-Math-Notes](https://github.com/ayushpai/AI-Math-Notes/assets/43297680/b2a2b0ce-5d1b-4639-8549-4f2725eb4c28)

AI Math Notes is an interactive drawing application that allows users to draw mathematical equations on a canvas. Once an equation is drawn, the application uses a multimodal LLM to calculate and display the result next to the equals sign. The application is built using Python with the Tkinter library for the graphical user interface and PIL for image processing. Inspired by Apple's ["Math Notes" demo](https://www.youtube.com/live/RXeOiIDNNek?si=zsfLkfVtCoCqk1ie&t=2806) from WWDC 2024.


## Setup & Installation
- Install libraries: `pip install -r requirements.txt`
- Setup OpenAI API as enviorment variable


## Usage
- Run the application: `python main.py`
### Application Interface

The app works by placing the answer next to an equation that has not been solved (AKA an equals sign with nothing to the right of it). An equals sign must be the last thing you wrote before clicking calculate.

- Canvas: Draw equations using your mouse. The canvas background is black, and the drawing color is white.
- Clear Button: Clears the entire canvas.
- Undo Button (Ctrl/Cmd Z): Undoes the last drawing action
- Calculate Button (Enter/Return): Calculates the drawn equation and displays the result next to the equals sign.

### Example
- Draw an equation on the canvas, such as `5 + 3 =`
- Press Enter or click the Calculate button.
- The result (e.g., 8) will be displayed next to the equals sign in orange color.

## Future Improvements
- Auto-detect Equals Sign: Implement a computer vision model to detect the equals sign so that it doesn't have to be the last thing you drew. This will improve usability and accuracy in placing the answer.
- Any contributions are welcome!

## License 
This project is licensed under the MIT License.
