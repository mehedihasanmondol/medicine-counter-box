without gpu only run this app using python 3.8 
updated tensorflow required of gpu driver setup.

tested on 
-Ubuntu 22.04.5 LTS
-os type : 64-bit
-gnome version : 42.9
-windowing system: Wayland

How to install Python 3.8 on newer Ubuntu versions
Step 1: Add the deadsnakes PPA

bash

sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update

sudo apt install python3.8 python3.8-venv python3.8-dev

python3.8 --version


step 2: 

python3.8 -m venv venv
source venv/bin/activate

step 3: train model

https://teachablemachine.withgoogle.com/
create example folder example
model
	--dataset
		--napa	
			1.jpg
			2.jpg
			3.jpg
			...
		--renitidine
			...
		--seclo
			...
		--sefixime
		...
	model.h5
	labels.txt


create: from starterkit
pip install tensorflow==2.4.0 keras==2.4.3 pillow numpy
python your_prediction_script.py

install: from requirements

pip install -r requirements.txt





