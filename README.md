# implement_MLP_with_Eigen

Implement MLP without torch, using eigen. To support DeepFlame You can use the model_print.py to convert .pt model to
.bin which can be read by C++.

load_model.h provied method to load bin model.

Run inference.cpp for model forward.

Please use .bin file in TGVbin.

inference.py for validation. Please check the result for your simd code with the standard result. If you got any problem
with the inference.py, please contact me.


