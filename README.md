# Automatic-Number-Plate-Recognition-YOLOv8

- Run this code to use this dependency

- First go into the sort folder and run

```python
python sort.py
```

- Install the project dependencies using the following command in the root folder

```bash
pip install -r requirements.txt
```

- Run main.py with the sample video file to generate the test.csv file

```python
python main.py
```

- Run the add_missing_data.py file for interpolation of values to match up for the missing frames and smooth output.

```python
python add_missing_data.py
```

- Finally run the visualize.py passing in the interpolated csv files and hence obtaining a smooth output for license plate detection.

```python
python visualize.py
```

For the input video as example the name is sample1.mp4
At last the final output is saved with the name of out.mp4
