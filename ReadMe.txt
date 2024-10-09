******
Global SMILE dataset is available at "https://www.kaggle.com/datasets/yuxiawhu/smile"


******
If you have used this dataset or code, please cite:
@ARTICLE{10401024, author={Xia, Yu and He, Wei and Huang, Qi and Chen, Hongyu and Huang, He and Zhang, Hongyan}, journal={IEEE Transactions on Geoscience and Remote Sensing}, title={SOSSF: Landsat-8 Image Synthesis on the Blending of Sentinel-1 and MODIS Data}, year={2024}, volume={62}, number={}, pages={1-19}, keywords={Remote sensing;Earth;Artificial satellites;European Space Agency;Satellite constellations;MODIS;Optical sensors;Attention-based network;spatial–spectral fusion;synthetic aperture radar (SAR)–optical data;worldwide dataset}, doi={10.1109/TGRS.2024.3352662}}

If you have any question and want raw data or extra data for spatiotemporal fusion (STF), you can contact the author's email address: whuxiayu@whu.edu.cn.

****Framenwork  and Enviroment: (Keras and Tensorflow)

*****
Python version=3.6.8
pip install -r requirements.txt

******
Training Process: bash train.sh
Training Process: bash test.sh
--use_gpu='GPU  number'
--modelname = 'model name'
--dataset_dir='dataset path'

