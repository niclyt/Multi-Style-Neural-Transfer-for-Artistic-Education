# Multi-Style-Neural-Transfer-for-Artistic-Education
CM3070 Final Project: Template 3.1 Project Idea 1 - Neural Style Transfer

## Project Overview
This project demonstrates multi-style neural style transfer (NST) as an educational tool.
It blends different artistic styles (e.g., Monet + Van Gogh) into a single image and provides both:

- A **technical learning experience** of convolutional neural networks and Gram matrices.
- An **interactive visual interface** (Chapter 8) that allows users to explore blends with sliders and dropdowns.

## Repository Contents

- `Multi-Style_NST_Portfolio.ipynb`: Main Jupyter Notebook portfolio with interactive interface (Chapter 8).
- `interactive_exports/`: This folder is used for *Chapter 8.4 Save and Compare*, where users get to compare the images and save the results into here. 2 example images have been include for reference.
- `content_images/`: Contain image I used for this project. *You can replace it with your own preferred image.*
- `outputs/`: Folder containing generated blended images. *You can delete these images and have your own generated images in them*
- `previews/`: Folder to save preview versions of the images in Chapter 2.3, to verify that the images have loaded correctly without crashing the notebook.
- `style_images/`: Folder containing our Monet and Vincent Van Gogh paintings. Feel free to replace it with your preferred art styles images and make the following code changes in the `Multi-Style_NST_Portfolio.ipynb` Jupyter Notebook.
- `All_15_Pairwise_Final_Losses.csv`: Final loss dataset for all pairwise style combinations.
- `Multi-Style_NST_Portfolio.html`: This is static web-readable version. Take note that the interactive interface in Chapter 8 will not work in this html.
- `README.md`: This file.


## How to Use: Cloning and Running This Project Locally
If you are new to GitHub or Jupyter, here are step-by-step instructions:

1. Install Prerequisites
  - (Recommended) Anaconda: https://www.anaconda.com/download
  OR Python 3.10+

  - Git: https://git-scm.com/downloads
 (for cloning the repository)

2. Clone the Repository
  Open a terminal (Anaconda Prompt, PowerShell, or Git Bash) and run:

```bash
git clone https://github.com/niclyt/Multi-Style-Neural-Transfer-for-Artistic-Education.git
```

3. Navigate to the cloned repository
  ```bash
  cd Multi-Style-NST-Portfolio
  ```
  This creates a local copy of the project folder on your computer.

4. Create a Conda Environment
  ```bash
  conda create -n nst-env python=3.10
  conda activate nst-env
  ```

5. Install Required Libraries
  ```bash
  pip install torch torchvision ipywidgets matplotlib seaborn pandas pillow
  ```

6. Launch Jupyter Notebook
```bash
python -m jupyter notebook
``` 
  This opens Jupyter in your browser.

7. For Full Interactivity
  - Open `Multi-Style_NST_Portfolio.ipynb` in Jupyter Notebook.
  - Feel free to Run the whole notebook and read through findings thats been made.
  - **For Interactivity**
    - Navigate to Chapter 8: Interactive Blender.
    - Select Chapter 8.1-8.4's code and run them in accordance. (Press `ctrl` + `shift` button)
    - Use the dropdown, slider, and play controls to explore blended images dynamically.
    - Ensure you have

**Note**: Interactive widgets (sliders, dropdowns, play button) do not function in PDF or HTML exports. They only work when running the notebook live.

8. For Static Reading
  - Head to Static_Reading folder
  - Open the .pdf or .html export for a polished, static view of our main Jupyter Notebook.
  - These contain all results, figures, and explanations except interface interactivity in Chapter 8.

Enjoy!!
