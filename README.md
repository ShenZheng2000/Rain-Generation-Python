# Rain-Generation-Python
This is a repository that shows how to generate rain for massive amount of images and with custom setting.

# Run
To execute the code for rain generation, run in terminal:

```python main.py --input_dir path/to/original_dataset/*.png --output_dir path/to/output_dataset```

For example.

```python main.py --input_dir C:/Users/Lebron/Desktop/CUSTOM_IMAGE/CityScape150/*.png --output_dir D:/Code/AAAI_2022/results/CityScape150_rain```

# Hyperparameters
You are welcome to adjust the hyperparameters to generate diverse kinds of rain streaks. Here is an unexhausted list
- noise
- rain_len
- rain_angle
- rain_thickness
- alpha

For example. 

```python main.py --noise 500 --rain_len 50 --rain_angle -30 --rain_thickness 3 --alpha 0.7```

