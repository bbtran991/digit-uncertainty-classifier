pip install -r requirements.txt
python train.py --epochs 5
python evaluate.py --checkpoint checkpoints/model.pt --auto-threshold
python demo.py --checkpoint checkpoints/model.pt --sample noise
