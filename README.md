# Robust Estimation of Similarity Transformation for Visual Object Tracking

This is our implementation of the Large Displacement Estimation of Similarity transformation (LDES) tracker. The main idea is to extend the CF-based tracker with similarity transformation (including position, scale, and rotation) in an efficient way. It can be used as a scale estimator with only sampling once in each frame. The code should be easy to follow and reuse. The details can be found in our AAAI-2019 paper.

Please cite our publication if you use the code
```
@InProceedings{Li2019ldes,
author = {Li, Yang and Zhu, Jianke and Hoi, Steven C.H. and Song, Wenjie and Wang, Zhefeng and Liu, Hantang},
title = {Robust Estimation of Similarity Transformation for Visual Object Tracking},
booktitle = {The Conference on Association for the Advancement of Artificial Intelligence (AAAI)},
month = {January},
year = {2019}
}
```
 
# Instruction
#### To just demo
* Modify the path in "demo.m" with your own setting. (optional)
* Run the "demo.m" script in MATLAB.

#### To run OTB-100 or OTB-2013
* Please indicate "run_ldes.m" as the entry point for OTB.

#### To run VOT evaluation
* Please integrate "run_vot.m" into the toolkit.

#### To run POT evaluation
* Modify the path in "run_pot.m" with your own setting.
* Run "run_pot.m" script in MATLAB.
* Use the result files in POT code to get benchmark results.


# Example
![tracking-example][logo]

[logo]: https://github.com/ihpdep/ihpdep.github.io/raw/master/files/example.gif "tracking-example"

# Contact 
* Yang Li, liyang89@zju.edu.cn, http://ihpdep.github.io
* Jianke Zhu, jkzhu@zju.edu.cn, http://jkzhu.github.io
* Steven C.H. Hoi, chhoi@smu.edu.sg, http://stevenhoi.org
