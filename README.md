## Publishing

Example command to publish pitch angles by hand

```
ros2 topic pub -1 /vpp/pitch_angle std_msgs/Float32MultiArray "layout:
   dim: []
   data_offset: 2
data: [9.1, 9.2, 9.3, 9.4]"
```

Where requested pitch angles are `[9.1, 9.2, 9.3, 9.4]`. It is possible to specify as many pitch angles as there are motors in `.sdf` model file of drone.
