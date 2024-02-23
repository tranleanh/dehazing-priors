# Single Image Dehazing Priors

This repo contains the Python implementations of various single image dehazing priors.

## Supported Priors

- Dark Channel Prior (DCP)
- Color Attenuation Prior (CAP)
- Boundary Constrained & Context Regularization (BCCR)\
- Non-Local Image Dehazing (NLID)
- Color Lines (CL)

## Usage

#### Install packages

```
pip install -r requirements.txt
```

#### Perform dehazing

Choose one method and run the command:

```
python dehaze.py --img_path tiananmen1.jpg --prior dcp
```

## Citation

Please cite our works if you use the data in this repo. 

```bibtex
@misc{tran2024dehazingpriors,
  author = {Tran, Le-Anh},
  title = {Prior-based Single Image Dehazing Toolkit},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository}
}
```

## References

This repo is built based on various sources:

- https://github.com/Utkarsh-Deshmukh/Single-Image-Dehazing-Python
- https://github.com/Joey777210/Non-Local-Dehazing-Python

LA Tran
