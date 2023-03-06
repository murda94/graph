sudo docker build --tag graph -f Dockerfile_dev .
sudo docker run --rm -ti --gpus all -d -p 8889:8889 -v /media/archive1/graph/:/temp graph