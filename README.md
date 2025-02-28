## Checkerboard Pattern Generator 

This is a simple Python script that generates a checkerboard pattern using Matplotlib.

### Features:
- Generates a customizable checkerboard pattern
- Supports different color maps (e.g., gray, viridis, plasma)

### Installation & Setup

1. Clone the Repository: </br>
Open your terminal and run: </br>
```bash
git clone https://github.com/heenal-h/dss5105_ex1.git 
cd repository-name
```

3. Create a Virtual Environment (Optional): </br>
It’s recommended to use a virtual environment: </br>
```bash
python -m venv venv 
source venv/bin/activate  # macOS/Linux 
venv\Scripts\activate     # Windows
```

3. Install Dependencies:
Install manually: 
```bash
pip install numpy matplotlib
```

### Usage

Run the script to generate a checkerboard pattern: </br>
```bash
python checkerboard.py
```

Modify the color map inside checkerboard.py: </br>
```bash
plt.imshow(checkerboard, cmap="viridis")  # Try other colormaps like "plasma" or "magma"
```

### Contributing
Want to improve this project? Follow these steps: </br>
Fork the repository on GitHub. 

Create a new branch:
```bash
git checkout -b feature-name
```
Make your changes and commit:
```bash
git add . 
git commit -m "Added new feature"
```

Push your changes and create a Pull Request:
```bash
git push origin feature-name
```
### License

This project is open-source.
