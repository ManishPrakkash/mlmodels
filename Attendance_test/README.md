python3 -m venv venv

source venv/bin/activate

python -m pip install --upgrade pip
sudo apt update
sudo apt install -y \
    python3-dev \
    build-essential \
    libatlas-base-dev \
    libhdf5-dev \
    libhdf5-serial-dev \
    libjpeg-dev \
    libtiff5-dev \
    libpng-dev \
    libgtk-3-dev \
    libavcodec-dev \
    libavformat-dev \
    libswscale-dev \
    libv4l-dev \
    libxvidcore-dev \
    libx264-dev \
    libopenblas-dev \
    liblapack-dev \
    gfortran \
    cmake \
    pkg-config

pip install tensorflow

pip install deepface

python attendance.py
