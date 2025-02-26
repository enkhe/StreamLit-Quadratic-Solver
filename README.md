# StreamLit-Quadratic-Solver

StreamLit Quadratic Solver

## Description

This project is a simple web application to solve quadratic equations using Streamlit. It allows users to input the coefficients of a quadratic equation and displays the solutions along with a plot of the quadratic function.

## Requirements

- Python 3.9+
- Streamlit
- Sympy
- Numpy
- Matplotlib

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/StreamLit-Quadratic-Solver.git
    cd StreamLit-Quadratic-Solver
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

To run the Streamlit application, use the following command:
```bash
streamlit run app.py
```
This will start a local web server. Open your web browser and navigate to http://localhost:8501 to view the application.

## Usage

1. Enter the coefficients `a`, `b`, and `c` of the quadratic equation `ax^2 + bx + c = 0`.
2. Click the "Solve" button.
3. The solutions to the quadratic equation will be displayed along with a plot of the quadratic function.

## License
This project is licensed under the MIT License.

