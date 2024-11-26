# PixelPalette 🎨  

PixelPalette is a virtual color whiteboard that allows you to draw and paint dynamically using color markers detected through a webcam. With intuitive controls and real-time color tracking, you can unleash your creativity digitally.  

## Features  
- **Color Detection**: Adjust marker color settings using HSV values.  
- **Multi-Color Drawing**: Choose from Blue, Green, Red, and Yellow markers.  
- **Clear Functionality**: Reset the canvas with a simple click.  
- **Customizable Controls**: Adjust marker sensitivity using trackbars.  
- **Live Feedback**: See your drawing process in real-time across multiple windows.  

---

## Installation  
1. Clone the repository or download the code files.  
2. Ensure you have Python installed on your system.  
3. Install the required libraries:  
   ```bash
   pip install numpy opencv-python
   ```  

---

## Usage  
1. **Run the program**:  
   ```bash
   python pixel_palette.py
   ```  
2. **Control Panel**:  
   - Use the **Color detectors** window to adjust HSV values for precise color detection.  
3. **Color Selection**:  
   - Click on the color buttons (Blue, Green, Red, Yellow) to switch marker colors.  
4. **Clear Canvas**:  
   - Click the "CLEAR ALL" button to reset the canvas.  
5. **Quit the Application**:  
   - Press the `q` key to exit the program.  

---

## How It Works  
1. The program uses a webcam to detect markers based on HSV (Hue, Saturation, Value) color ranges.  
2. Detected marker positions are drawn on a virtual canvas in the selected color.  
3. Trackbars allow dynamic adjustment of HSV ranges for better color detection.  
4. Buttons on the top of the frame provide color selection and canvas clearing options.  

---

## File Structure  
- `pixel_palette.py`: Main script containing the application logic.  

---

## Prerequisites  
- Python 3.6 or higher  
- Webcam for real-time video input  

---

## Demonstration  

### Color Detection Example:  
![](https://via.placeholder.com/600x300?text=Demo+Image+Placeholder)  
*Draw on the virtual canvas by moving the marker.*  

---

## Future Enhancements  
- Add support for saving the canvas as an image.  
- Introduce more marker colors and brush sizes.  
- Enhance color detection for low-light environments.  
- Enable gesture-based controls for improved user interaction.  

---

## License  
This project is open-source and available under the MIT License.  

---

## Contribute  
Feel free to fork this repository, submit issues, or contribute via pull requests. Let's make **PixelPalette** even better!  

Happy drawing! 🎉  
