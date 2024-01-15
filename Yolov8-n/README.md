# Yolov8-n
- This section demonstrates how converting NEW smallest Yolov8 (Yolov8-n) to deployment friendly tflite model and ARM's vela compiler.
- The flow is in the `yolov8_export_tflite_vela.ipynb`

## Reference
- [Yolov8](https://github.com/ultralytics/ultralytics/tree/main): Please reference here for how to train or test.
- [onnx2tf](https://github.com/PINTO0309/onnx2tf): The step is pytorch -> onnx -> tflite (int8 or float)
- [vela](https://pypi.org/project/ethos-u-vela/)

## Training a new Yolov8-n model
- From [ultralytics](https://github.com/ultralytics/ultralytics/tree/main)'s framework. More detail is in the link. 
- User needs to install/update pyTorch basing on user's hardware. [get-started](https://pytorch.org/get-started/locally/)
- The flow is in the `yolov8_train_val.ipynb`
