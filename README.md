# User Guide

## Running the Application via Binder

1. Go to: [https://mybinder.org/](https://mybinder.org/)
2. Click on the dropdown and choose “Git Repository”.
3. Paste: `https://github.com/tark-hunt/f1` into the text field next to the dropdown.
4. Click the orange button “Launch”.
5. This may take some time. Binder may need to download/analyze the Git repository.
6. If it fails to launch, see “Other ways to Run” below.
7. Open the file: “Capstone.ipynb” (Double-clicking will open it).
8. Next to “Code” in the toolbar, there will be a button with the description: “Render with Voila” when you hover over it. Click on it.
9. A dashboard will then appear. This is where you can predict finishing positions for each driver depending on the weather and circuit.

10. **To make a prediction:**
    * Move the sliders to the desired number.
    * Select the circuit and the driver from the dropdowns.
    * The predicted finishing position for that driver will be displayed.

11. **To see the force plot of the prediction:** Click “Generate Force Plot”.  *Note: If a change is made using the weather sliders, the button will need to be clicked again.*

12. **To see a scatter plot with all predicted finishing positions for every driver on the selected circuit and weather:** Click “Generate Scatter Plot”. You will then be able to hover over each dot on the graph and see each prediction. *Note: If a change is made using the weather sliders, the button will need to be clicked again.*

13. **To see how the model was trained (Accuracy and Feature Importance):** Click on “Show Test Results”.


## Other Ways to Run

1. Go to [https://github.com/tark-hunt/f1](https://github.com/tark-hunt/f1)
2. Download the Repository as a `.zip` file.
3. On your computer, unzip and open `Capstone.ipynb` using Jupyter Notebook.
4. Click on “Run” -> “Run all cells”.
5. Scroll to the bottom of the notebook; the UI will appear.
6. Follow steps 7-13 from the "Running the Application via Binder" section above.
