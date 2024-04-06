# conda-spark

conda create --name sp 
conda activate sp

conda install pip
pip install -q findspark
pip install pyarrow
pip install --disable-pip-version-check install tf-nightly
