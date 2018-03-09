# aind2-dl

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/aind2-dl.git
		cd aind2-dl
	```

2. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  
	
	For __Mac/OSX__:
	```
		conda env create -f requirements/aind-dl-mac.yml
		source activate aind-dl
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f requirements/aind-dl-windows.yml
		activate aind-dl
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
	```

	For __Linux__:
	```
		conda env create -f requirements/aind-dl-linux.yml
		source activate aind-dl
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```
	
3. Enjoy!

##### Note: You'll need to clone CLR into a directory in your your $PYTHONPATH variable:

```
git clone https://github.com/bckenstler/CLR

cd CLR
```

Then create an empty file named \__init\__.py in that directory.