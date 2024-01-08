# Yolov8-n
- This section demonstrates how converting NEW smallest yolov8 (Yolov8-n) to deployment friendly tflite model and ARM's vela compiler.
- The flow is show in `yolov8_export_tflite_vela.ipynb`

## Reference
- [Yolov8](https://github.com/ultralytics/ultralytics/tree/main): Please reference here for how to train or test.
- [onnx2tf](https://github.com/PINTO0309/onnx2tf): The step is pytorch -> onnx -> tflite (int8 or float)
- [vela](https://pypi.org/project/ethos-u-vela/) 
