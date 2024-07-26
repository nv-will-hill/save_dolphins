# save_dolphins

### progress

##### compile / optimize
* [ ] Circularnet --> ONNX
* [X] TensorFlow --> ONNX
* [X] ONNX --> Nsight DL Designer
* [X] Nsight DL DesignerLD (DLD) --> TensorRT
* [ ] TensorFlow --> ONNX --> TensorRT
* [ ] Circularnet (TF) --> ONNX --> TensorRT
* [ ] Circularnet (TF) --> ONNX --> (DLD) --> TensorRT

##### deploy
* [X] TensorRT --> Infer
* [ ] TensorRT --> Jetson (sim)
* [ ] TensorRT --> Jetson
* [ ] Jetson --> Infer
* [ ] Jetson --> Infer (LA)

---

##### Table
| task                                                     | status  |
| --------                                                 | ------- |
| TF** --> ONNX                                            |  [X]    |
| CrcNet*  --> ONNX                                        |  [ ]    |
| ONNX --> DLD***                                          |  [X]    |
| DLD --> TRT****                                          |  [X]    |
| TRT --> Infer                                            |  [X]    |
| TensorFlow --> ONNX --> TensorRT                         |  [ ]    |
| TensorFlow --> ONNX --> TensorRT --> Infer               |  [ ]    |
| TRT --> Jetson                                           |  [ ]    |
| Jetson (Sim) --> Infer                                   |  [ ]    |
| Jetson --> Infer                                         |  [ ]    |
| Jetson --> Infer (LA)                                    |  [ ]    |



*CrcNet  
**TensorFlow  
***Nsight DL Designers  
****TensorRT  
