# Frame Interpolation 

Frame interpolation is the process of synthesizing intermediate frames between two consecutive images or frames in a video sequence. This project leverages machine learning techniques to enhance the temporal resolution of videos by generating intermediate frames with high accuracy.

---

## Team Members

- **Gaurav Daultani**
- **Nandini Bansal**
- **Mohd Sahil**

---

## Dataset

**Vimeo90K**  
Introduced by Xue et al. in *Video Enhancement with Task-Oriented Flow*.  

The Vimeo-90K dataset is a large-scale, high-quality video dataset designed for lower-level video processing tasks. It includes:
- **Frame Interpolation**
- **Video Denoising/Deblocking**
- **Video Super-Resolution**

This dataset provides diverse and high-quality video sequences, making it ideal for training and testing frame interpolation models.

More about the dataset can be found in the original publication: [Video Enhancement with Task-Oriented Flow](https://paperswithcode.com/dataset/vimeo90k-1).

---

## Pre-trained Models

We provide pre-trained models to demonstrate the effectiveness of our approach. These models are trained on the Vimeo90K dataset and optimized for high-quality frame interpolation tasks.

- **Model 1**: [Download Link](#)  
- **Model 2**: [Download Link](#)

You can use these models for inference or fine-tune them for your own dataset.

---

## Running the Code

### 1. Clone the Repository
```bash
git clone https://github.com/gauravdaultani/frame-interpolation-main.git
cd frame-interpolation-main
```
## Running the Code

### 2. Download Pre-trained Models

Place the downloaded models in the `models/` directory.

### 3. Run Inference

To generate interpolated frames for a video:

```bash
python interpolate.py --input ./input_video.mp4 --output ./output_video.mp4 --model ./models/model.pth
```
### 4. Training the Model

To train a model on the Vimeo90K dataset:

```bash
python train.py --data_dir ./vimeo90k --epochs 50 --batch_size 16
```
## Applications

Frame interpolation can be applied in various fields, including:

- **Video editing and production**
- **Slow-motion video creation**
- **Enhancing video quality for low frame rate footage**
- **Virtual reality and gaming**

---

## Contribution Guidelines

We welcome contributions from the community. To contribute:

1. **Fork** the repository.
2. Create a **new branch** for your feature/bug fix.
3. Submit a **pull request** with a detailed description of the changes.


