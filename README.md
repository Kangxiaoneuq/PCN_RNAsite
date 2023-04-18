A deep convolutional neural network-based model by integrating local and global features, sequence and structure properties is constructed to predict RNA-ligand binding sites.

The benchmark datasets can be found in ./data_cache/, the codes for RLBind are available in ./src. And the results and model are saved in ./results. Furthermore, the demo and corresponding documentation files can be found in ./demo. See our paper for more details.


Requirements
python 3.8.8
numpy 1.23.5
scikit-learn 1.2.2
pandas 3.1.0

conda env create -f environment_gpu.yml
conda activate RLBind_env
Testing the model
cd ./src/
python predict.py
Re-training your own model for the new dataset
cd ./src/
python training.py
contact
Kang Xiao: xiaokangneuq@163.com
