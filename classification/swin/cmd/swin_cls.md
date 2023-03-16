<a id="virtualen_v_"></a>
# virtualenv
python3 -m pip install virtualenv virtualenvwrapper

mkvirtualenv swin_c
workon swin_c

nano ~/.bashrc
alias swc='workon swin_c'
source ~/.bashrc

<a id="windows___virtualenv_"></a>
## windows       @ virtualenv-->swin_cls
virtualenv swin_c
swin_c\Scripts\activate.bat

# install

## torch       @ install-->swin_cls
python -m pip install torch==1.9.0+cu111 torchvision==0.10.0+cu111 torchaudio===0.9.0 -f https://download.pytorch.org/whl/torch_stable.html

python -m pip install tensorboardX
python -m pip install tqdm
python -m pip install timm==0.4.12
python -m pip install opencv-python==4.4.0.46 termcolor==1.1.0 yacs==0.1.8 pyyaml scipy

cd kernels/window_process
python setup.py install

python -m pip install tensorflow tensorboard

# ext_reorg_roi_g2_0_37
## v1-base-224-1k       @ ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 128 --output log/ext_reorg_roi_g2_0_37-v1-base-224-1k  --pretrained pretrained/swin_base_patch4_window7_224_22k.pth --use-checkpoint

### eval       @ v1-base-224-1k/ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 24 --output log/ext_reorg_roi_g2_0_37-v1-base-224-1k --resume log/ext_reorg_roi_g2_0_37-v1-base-224-1k/ckpt_epoch_796.pth

## v1-large-224-22k       @ ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swin/swin_large_patch4_window7_224_22k_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 64 --output log/ext_reorg_roi_g2_0_37-v1-large-224-22k  --pretrained pretrained/swin_large_patch4_window7_224_22k.pth --use-checkpoint

## v1-large-384-22k       @ ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swin/swin_large_patch4_window12_384_22kto1k_finetune_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 12 --output log/ext_reorg_roi_g2_0_37-v1-large-384-22k  --pretrained pretrained/swin_large_patch4_window12_384_22k.pth --use-checkpoint

### eval       @ v1-large-384-22k/ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swin/swin_large_patch4_window12_384_22kto1k_finetune_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 24 --output log/ext_reorg_roi_g2_0_37-v1-large-384-22k --resume log/ext_reorg_roi_g2_0_37-v1-large-384-22k/ckpt_epoch_00999.pth

## v2-base-256-1k       @ ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swinv2/swinv2_base_patch4_window16_256_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 48 --output log/ext_reorg_roi_g2_0_37-v2-base-256-1k --pretrained pretrained/swinv2_base_patch4_window16_256.pth --use-checkpoint

### eval       @ v2-base-256-1k/ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swinv2/swinv2_base_patch4_window16_256_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 24 --output log/ext_reorg_roi_g2_0_37-v2-base-256-1k --resume log/ext_reorg_roi_g2_0_37-v2-base-256-1k/ckpt_epoch_00999.pth

## v2-large-192-22k       @ ext_reorg_roi_g2_0_37-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swinv2/swinv2_large_patch4_window12_192_22k_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37 --batch-size 48 --output log/ext_reorg_roi_g2_0_37-v2-large-192-22k --pretrained pretrained/swinv2_large_patch4_window12_192_22k.pth --use-checkpoint

# ext_reorg_roi_g2_0_37_masked
## v1-base-224-1k       @ ext_reorg_roi_g2_0_37_masked-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37_masked --batch-size 128 --output log/ext_reorg_roi_g2_0_37_masked-v1-base-224-1k  --pretrained pretrained/swin_base_patch4_window7_224_22k.pth --use-checkpoint

### eval       @ v1-base-224-1k/ext_reorg_roi_g2_0_37_masked-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_0_37_masked --batch-size 24 --output log/ext_reorg_roi_g2_0_37_masked-v1-base-224-1k --resume log/ext_reorg_roi_g2_0_37_masked-v1-base-224-1k/ckpt_epoch_00999.pth

# ext_reorg_roi_g2_16_53
## v1-base-224-1k       @ ext_reorg_roi_g2_16_53-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_16_53 --batch-size 128 --output log/ext_reorg_roi_g2_16_53-v1-base-224-1k  --pretrained pretrained/swin_base_patch4_window7_224_22k.pth --use-checkpoint

### eval       @ v1-base-224-1k/ext_reorg_roi_g2_16_53-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_16_53 --batch-size 24 --output log/ext_reorg_roi_g2_16_53-v1-base-224-1k --resume log/ext_reorg_roi_g2_16_53-v1-base-224-1k/ckpt_epoch_00999.pth

# ext_reorg_roi_g2_16_53_masked
## v1-base-224-1k       @ ext_reorg_roi_g2_16_53_masked-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_16_53_masked --batch-size 128 --output log/ext_reorg_roi_g2_16_53_masked-v1-base-224-1k  --pretrained pretrained/swin_base_patch4_window7_224_22k.pth --use-checkpoint

### eval       @ v1-base-224-1k/ext_reorg_roi_g2_16_53_masked-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_16_53_masked --batch-size 24 --output log/ext_reorg_roi_g2_16_53_masked-v1-base-224-1k --resume log/ext_reorg_roi_g2_16_53_masked-v1-base-224-1k/ckpt_epoch_00999.pth

# ext_reorg_roi_g2_54_126
## v1-base-224-1k       @ ext_reorg_roi_g2_54_126-->swin_cls
python -m torch.distributed.launch --nproc_per_node 3 --master_port 12345  main.py --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_54_126 --batch-size 128 --output log/ext_reorg_roi_g2_54_126-v1-base-224-1k  --pretrained pretrained/swin_base_patch4_window7_224_22k.pth --use-checkpoint --resume log/ext_reorg_roi_g2_54_126-v1-base-224-1k/ckpt_epoch_00999.pth

### eval       @ v1-base-224-1k/ext_reorg_roi_g2_54_126-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_54_126 --batch-size 24 --output log/ext_reorg_roi_g2_54_126-v1-base-224-1k --resume log/ext_reorg_roi_g2_54_126-v1-base-224-1k/ckpt_epoch_00999.pth
### on-g2_0_15       @ v1-base-224-1k/ext_reorg_roi_g2_54_126-->swin_cls
python -m torch.distributed.launch --nproc_per_node 1 --master_port 12345  main.py --eval --cfg configs/swin/swin_base_patch4_window7_224_ipsc2class.yaml --data-path /data/ipsc/well3/all_frames_roi/swc/ext_reorg_roi_g2_16_53 --batch-size 24 --output log/ext_reorg_roi_g2_54_126-v1-base-224-1k --resume log/ext_reorg_roi_g2_54_126-v1-base-224-1k/ckpt_epoch_00999.pth





