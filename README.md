## installation
1. diffusers install
* PyTorch
  
  With pip (official package):
  ```bash
  pip install --upgrade diffusers[torch]
  ```
  With conda (maintained by the community):
  ```bash
  conda install -c conda-forge diffusers
  ```
2. TIFA install
   
  Clone and build the repo:
  ```bash
  git clone https://github.com/Yushi-Hu/tifa.git
  cd tifa
  pip install -r requirements.txt
  pip install -e .
  ```
3. ddpo-pytorch install

Requires Python 3.10 or newer.
```bash
git clone https://github.com/zihos/sketcher.git
cd sketcher
pip install -e.
```

## usage
```bash
python scripts/train.py --config config/base.py
```
