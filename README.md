# Start with this



```bash
python -m venv myvirtualenvironment

source myvirtualenvironment/bin/activate

pip install -r requirements.txt
```


go to training.ipynb and on the upper right, click select kernel, then select python environments, then select myvirtualenvironment


next, make sure to configure the path to the detection.yaml file. the path directive should point to the path of the root folder for thedataset. In this case, it should point to the kitkat_dataset.

If you are on vscode, just right click the folder, copy path, and then paste the copied path to the detection.yaml. make sure to remove unnecessary suffixes on the path. The final path should end with /kitkat_dataset/ or else the training wont work. But if it still doesnt work, please do read the warning/error on the training.ipynb

