# Optimal_PreProcessing_for_CV_based_spectrum_sensing
This repository contains links to all batches of datasets used in our paper "Optimal Preprocessing for Joint Detection and Classification of Wireless Communication Signals in Congested Spectrum Using Computer Vision Methods"
## Initial Coarse Search
W64F256: https://universe.roboflow.com/stevenkang7/w64f256/dataset/1  <br />
W64F1024: https://universe.roboflow.com/stevenkang7/w64f1024/dataset/1  <br />
W64F4096: https://universe.roboflow.com/stevenkang7/w64f4096/dataset/1  <br />
W64F16384: https://universe.roboflow.com/stevenkang7/w64f16384/dataset/2  <br />
W256F1024: https://universe.roboflow.com/stevenkang7/w256f1024/dataset/1 <br />
W256F4096: https://universe.roboflow.com/stevenkang7/w256f4096/dataset/2 <br />
W256F16384: https://universe.roboflow.com/stevenkang7/w256f16384/dataset/1 <br />
W256F65536: https://universe.roboflow.com/stevenkang7/w256f65536/dataset/1 <br />
W1024F4096: https://universe.roboflow.com/xiwen-additional-space/w1024f4096/dataset/1 <br />
W1024F16384: https://universe.roboflow.com/xiwen-additional-space/w1024f16384/dataset/1 <br />
W1024F65536: https://universe.roboflow.com/xiwen-additional-space/w1024f65536/dataset/1 <br />
Same formats for the other 5 datasets in this batch (under the xiwen-additional-space directory). <br />

## Fine Search for Optimal Window Length
W8F8: https://universe.roboflow.com/additionalwindowsize/w8f8/dataset/1 <br />
W16F16: https://universe.roboflow.com/additionalwindowsize/w16f16/dataset/1 <br />
W32F32: https://universe.roboflow.com/additionalwindowsize/w32f32/dataset/1 <br />
W128F128: https://universe.roboflow.com/additionalwindowsize/w128f128/dataset/1 <br />

W64F64: https://universe.roboflow.com/addtionalfft/w64f64/dataset/1 <br />
W256F256: https://universe.roboflow.com/addtionalfft/w256f256/dataset/1 <br />
W1024F1024: https://universe.roboflow.com/addtionalfft/w1024f1024/dataset/1 <br />
W4096F4096: https://universe.roboflow.com/addtionalfft/w4096f4096/dataset/1 <br />

## Fine Search for Optimal Window Type
Hann Window: https://universe.roboflow.com/windowtype/1_window_w128f128/dataset/1 <br />
Gaussian Window: https://universe.roboflow.com/windowtype/2_window_w128f128/dataset/1 <br />
Hamming Window: https://universe.roboflow.com/windowtype/3_window_w128f128/dataset/1 <br />
Blackman Window: https://universe.roboflow.com/windowtype/4_window_w128f128/dataset/1 <br />
Same formats for the other 5 datasets in this batch (under the windowtype directory, see the mapping from our paper, Table IV. The indexing rules are 1 to 3 for the first row (i.e., the Hann, Gaussian and Hamming Window), 4-6 for the second row, and 7-9 for the last row.). <br />


## Fine Search for Optimal Overlap Factor
10% overlap: https://universe.roboflow.com/additionaloverlap/1_overlap_w128f128/dataset/1 <br />
20% overlao: https://universe.roboflow.com/additionaloverlap/2_overlap_w128f128/dataset/1 <br />
Same formats for the other 7 datasets in this batch (under the additionaloverlap directory). <br />
