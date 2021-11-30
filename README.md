# grid-centertrack

```
conda create --name CenterTrack python=3.8
conda activate CenterTrack
conda install pytorch torchvision -c pytorch
pip install cython; pip install -U 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'

CenterTrack_ROOT=~/CenterTrack
git clone --recursive https://github.com/xingyizhou/CenterTrack $CenterTrack_ROOT
pip install -r $CenterTrack_ROOT/requirements.txt

cd $CenterTrack_ROOT/src/lib/model/networks/
git clone https://github.com/CharlesShang/DCNv2
cd DCNv2
./make.sh


```
