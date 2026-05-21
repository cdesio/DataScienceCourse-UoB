# DataScienceCourse-UoB

Teaching material for two University of Bristol data science courses.

- **Beginners Data Science Course** introduces Python programming, Jupyter notebooks, NumPy, pandas, visualisation, and first machine learning ideas.
- **Advanced Machine Learning** covers statistical foundations, model fitting and validation, supervised and unsupervised learning, neural networks, convolutional networks, tensors, and PyTorch.

The material was designed for live coding sessions. Most sessions include blank notebooks for learners and completed notebooks in `solutions/`. Local recordings are organised separately by course in `recordings/`.

## Repository Layout

```text
beginners/
  Session_*/
    *.ipynb
    solutions/
    data/
    figures/
    utilities/

advanced-ml/
  Session*/
    *.ipynb
    solutions/
    data/
    figures/
    utilities/

recordings/
  beginners/
  advanced-ml/
```

Not every session uses every folder. The session folder itself remains the main working location so notebook paths stay easy to follow.

## Folder Conventions

- `solutions/`: completed versions of notebooks and exercise workbooks.
- `recordings/`: local video recordings, split by course. Video files are ignored by Git; each course recording folder has a README for OneDrive links.
- `data/`: small datasets used directly by notebooks.
- `figures/`: images, diagrams, and other visual teaching material.
- `utilities/`: helper Python modules and reusable support code.

Large local files such as recordings, downloaded datasets, generated caches, and trained model checkpoints are ignored by Git by default. They can stay in the working folder without being committed to GitHub accidentally.

## Courses

### Beginners Data Science Course

| Session | Topic |
| --- | --- |
| Session 1 | Introduction to Python programming and Jupyter notebooks |
| Session 2 | Basic Python: data types, variables, operations, lists, and tuples |
| Session 3 | Basic Python: loops, conditionals, and dictionaries |
| Session 4 | Basic Python: recap, dictionaries, files, and string formatting |
| Session 5 | Basic Python: built-in functions and custom functions |
| Session 6 | NumPy arrays and array operations |
| Session 7 | NumPy multidimensional arrays, filtering, and combining arrays |
| Session 8 | Data analysis and visualisation with pandas |
| Session 9 | Introduction to machine learning |

### Advanced Machine Learning

| Session | Topic |
| --- | --- |
| Introduction | Course introduction |
| Session 1 | Statistics and machine learning |
| Session 2 | Statistics, part 2 |
| Session 3 | Fitting, correlation, and model validation |
| Sessions 4-5 | Machine learning in Python and supervised learning |
| Session 6 | Unsupervised learning |
| Session 7 | Artificial neural networks from the ground up |
| Session 8 | Convolution and convolutional neural networks |
| Session 9 | Tensors and PyTorch |

## Setup

Create a Python environment with Jupyter and the scientific Python stack used in the notebooks. At minimum, most sessions expect:

```bash
pip install jupyter numpy pandas matplotlib seaborn scikit-learn scipy
```

Some advanced sessions also use PyTorch.
