# stanford40_pose
Stanford40 Dataset with Pose annotations 

To Read the Pose Annotations You first need to import `pickle` to load these `.pkl` files, write like this:

```python
with open(path-to-pkl-file, 'rb') as f:
    pose = pkl.load(f)
```

Now you have pose coordiantes with shape (2, 17). i have used yolo for extact these keypoints.
