## TraDWin

### Dataset prep
- see `/data/README.md` for dataset sources

### Setup

- Environment:
    - Pyhon 3.10
    - create a virtual environment using `virtualenv`
    - `req.txt` for dependencies, install using `pip install -r req.txt`
- `data/` directory for dataset
- `process` for pre-processing scripts
- `sample` for sampling and generating data for each task
- `train` for model training script
- `vec-conversions` embedding gen using `Node2Vec`
- `TraDWin paper` and `TraDWin thesis` for paper and thesis
- `plots` for plots using matplotlib
- `draw.io diags` for diagrams made using draw.io
- `slides` for presentation slides
---
- Update the paths as per the dataset path in the scripts
- First run `process/` scripts to generate a combined dataframe
- Then `vec-conversions/Node2Vec` to generate embeddings
- Then sample data using `sample/` scripts
- Finally train models using `train/` scripts