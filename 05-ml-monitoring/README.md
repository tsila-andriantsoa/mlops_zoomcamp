# create conda environment
conda create -n py11 python=3.11

# activate conda environment
conda activate py11

# install package
pip install -r requirements.txt

# create docker compose file

# build docker component (add --build for the first run)
docker-compose up --build 