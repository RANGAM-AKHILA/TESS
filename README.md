# TESS
implementation of multimodal for emotional recognition 
## environment setup
- Python ≥ 3.8
- PyTorch ≥ 1.12
- Transformers (HuggingFace), Scikit-learn
- NumPy, Pandas
- command:
- pip install torch torchaudio torchvision
- pip install transformers
- pip install scikit-learn
- pip install numpy pandas matplotlib seaborn
- pip install tqdm librosa
- for visulaize:pip install umap-learn
### Data Preparation
- Extract text features using a pre-trained language model BERT
- Extract speech features using a pre-trained language model HuBERT
