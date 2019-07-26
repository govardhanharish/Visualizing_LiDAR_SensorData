# Visualizing_LiDAR_SensorData

1. Uber AVS Autonomous Visualization System (AVS) --- XVIZ (the data layer for AVS)
Quick start

You need Node.js and yarn to run the examples.

# Clone XVIZ
$ git clone https://github.com/uber/xviz.git
$ cd xviz

# Install dependencies
$ yarn bootstrap

Convert and serve KITTI example data:

# Download KITTI data
$ ./scripts/download-kitti-data.sh

# Convert KITTI data if necessary and run the XVIZ Server and Client
$ ./scripts/run-kitti-example.sh

2. KITTI Dataset Exploration
Dependencies

Apart from the common dependencies like numpy and matplotlib notebook requires pykitti. You can install pykitti via pip using:

pip install pykitti


I have used one of the raw datasets available on KITTI website : http://www.cvlibs.net/datasets/kitti/raw_data.php.

2011_09_26_drive_0005 (0.6 GB)

Length: 160 frames (00:16 minutes)

Image resolution: 1392 x 512 pixels

Labels: 9 Cars, 3 Vans, 0 Trucks, 2 Pedestrians, 0 Sitters, 1 Cyclists, 0 Trams, 0 Misc

Based on 

    Uber Xviz A protocol for real-time transfer and visualization of autonomy data - https://github.com/uber/xviz
    
    Referred from https://github.com/engineBozkurt/Visualizing-lidar-data
