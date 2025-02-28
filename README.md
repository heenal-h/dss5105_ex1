## Checkerboard Pattern Generator 

This is a simple Python script that generates a checkerboard pattern using Matplotlib.

### Features:
- Generates a customizable checkerboard pattern
- Supports different color maps (e.g., gray, viridis, plasma)

### Installation & Setup

1. Clone the Repository: </br>
Open your terminal and run: </br>
git clone https://github.com/your-username/repository-name.git </br>
cd repository-name

3. Create a Virtual Environment (Optional): </br>
It’s recommended to use a virtual environment: </br>
python -m venv venv </br>
source venv/bin/activate  # macOS/Linux </br>
venv\Scripts\activate     # Windows 

3. Install Dependencies: </br>
Install manually: </br>
pip install numpy matplotlib 

### Usage

Run the script to generate a checkerboard pattern: </br>
python checkerboard.py

Modify the color map inside checkerboard.py: </br>
plt.imshow(checkerboard, cmap="viridis")  # Try other colormaps like "plasma" or "magma"

### Contributing
Want to improve this project? Follow these steps: </br>
Fork the repository on GitHub. 

Create a new branch:
git checkout -b feature-name

Make your changes and commit:
git add . </br>
git commit -m "Added new feature"

Push your changes and create a Pull Request:
git push origin feature-name

### License

This project is open-source.
