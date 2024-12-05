# DIEM25/MERA25 Statistics Generation Scripts (diem25-stats)

This repository contains Python notebooks and scripts designed to generate statistics for internal and external communication by **DIEM25** and **MERA25**. The primary focus is on creating clear, accurate, and reproducible visualizations of key statistical data.

## Overview

The scripts in this repository:

- Process datasets from reliable sources like Eurostat and others.
- Generate professional plots and visualizations in both raster (PNG) and vector (SVG/PDF) formats.
- Highlight trends and comparisons across various economic, social, and political indices.

### Example Use Case

An example notebook demonstrates:

1. Filtering datasets to focus on specific indices (e.g., Food Price Index).
2. Cleaning and transforming data for consistency.
3. Generating plots to visualize trends over time for regions like Germany, Greece, and the EU.

These visualizations are used in presentations, reports, and public communication to ensure transparency and trust.

## Structure

- **Notebooks**: Jupyter notebooks (\*.ipynb) that walk through data processing and visualization step-by-step.
- **Scripts**: Reusable Python scripts for common tasks like data cleaning and plotting.
- **Data**: Example datasets or links to public sources.
- **Outputs**: Plots and figures generated from the notebooks.

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-repo/diem25-statistics.git
```

2. Create a virtual environment:

```bash
python3 -m venv venv
```

3. Activate the virtual environment:

- On Linux/Mac:

```bash
source venv/bin/activate
```

- On Windows:

```bash
venv\Scripts\activate
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

### Running the Notebooks

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the desired notebook file (`*.ipynb`) and execute the cells.

## License

This repository is licensed under the Creative Commons Zero (CC0) 1.0 Universal License.

For more information, see the full license text in the [LICENSE](LICENSE) file.

We believe transparency is critical, and making these scripts public aligns with our commitment to accountability.

## Contribution Guidelines

Contributions to improve these scripts or expand their capabilities are welcome. Please submit issues or pull requests via GitHub.

To maintain a clean and professional repository, please follow these guidelines when contributing:

### 1. **Notebooks**

- **Clear Outputs**: Ensure all notebooks (*.ipynb) have their outputs cleared before committing. This minimizes file sizes and avoids unnecessary clutter.
  - Clear outputs in Jupyter Notebook:
    ```bash
    jupyter nbconvert --clear-output --inplace notebook.ipynb
    ```
- **Descriptive Titles**: Use meaningful and concise notebook filenames.
- **Document Your Work**: Include comments and markdown cells to explain your workflow, assumptions, and findings.

### 2. **Data**

- **Avoid Binary Data**: Do not commit large binary datasets (e.g., CSV, Excel, or other raw data files) to the repository.
  - If datasets are necessary, use a link to an external source or repository (e.g., public datasets on Eurostat or other platforms).
- **Small Examples Only**: If required, include small sample datasets for demonstration purposes only.

### 3. **Plots and Outputs**

- **Clean Output Directory**: Save plots and figures in a designated `output/` directory and ensure they are relevant to the notebooks/scripts.
- **Avoid Committing Outputs**: Generally, avoid committing generated plots and outputs unless explicitly required for documentation.

### 4. **Dependencies**

- **Use Virtual Environments**: Always use a virtual environment when developing or testing scripts. Keep dependencies in `requirements.txt`.
- **Freeze Dependencies**: If you add or update a dependency, regenerate the `requirements.txt` file:
  ```bash
  pip freeze > requirements.txt
  ```

### 5. **Code Quality**

- **Adopt Consistent Styling**: Follow PEP8 for Python scripts. Use tools like `black` or `flake8` to format your code.
- **Use Modular Code**: Break down complex logic into functions or reusable modules where appropriate.

### 6. **Licensing and Attribution**

- **Respect Data Licenses**: Ensure that all data and scripts comply with applicable licenses.
- **Acknowledge Sources**: Provide links to data sources or references in your notebook markdown cells.

### 7. **Transparency**

- **Provide Context**: Include sufficient documentation in notebooks and scripts to ensure that the methodology is clear to external audiences.
- **Commit Messages**: Use clear and descriptive commit messages to document changes.
