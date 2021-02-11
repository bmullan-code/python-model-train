# python-model-train
python-model-train

To run:

virtualenv -p /usr/bin/python2.7 venv

source ./venv/bin/activate

pip install -r requirements.txt

python custom_training_walkthrough.py


Build docker image:

docker build . -t repo/image-name

docker run -it repo/image-name:latest

