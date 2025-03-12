![title.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/4j6OJMJEg6rjq3p8/img/666040a8-4ec1-474f-840e-f039539d7d08.png)

# 🔥 Updates

*   \[3/2024\] **VMBench** evaluation code & prompt set released!
    

# 📣 Overview

![overview.png](https://alidocs.oss-cn-zhangjiakou.aliyuncs.com/res/4j6OJMJEg6rjq3p8/img/27919c5f-fcea-4f50-8ed8-835ede58b392.png)

Video generation has advanced rapidly, improving evaluation methods, yet assessing video's motion remains a major challenge. Specifically, there are two key issues: 1) current motion metrics do not fully align with human perceptions; 2) the existing motion prompts are limited. Based on these findings, we introduce **VMBench**---a comprehensive **V**ideo **M**otion **Bench**mark that has perception-aligned motion metrics and features the most diverse types of motion. VMBench has several appealing properties: (1) **Perception-Driven Motion Evaluation Metrics**, we identify five dimensions based on human perception in motion video assessment and develop fine-grained evaluation metrics, providing deeper insights into models' strengths and weaknesses in motion quality. (2) **Meta-Guided Motion Prompt Generation**, a structured method that extracts meta-information, generates diverse motion prompts with LLMs, and refines them through human-AI validation, resulting in a multi-level prompt library covering six key dynamic scene dimensions. (3) **Human-Aligned Validation Mechanism**, we provide human preference annotations to validate our benchmarks, with our metrics achieving an average 35.3% improvement in Spearman’s correlation over baseline methods. This is the first time that the quality of motion in videos has been evaluated from the perspective of human perception alignment. Additionally, we will soon release VMBench as an open-source benchmark, setting a new standard for evaluating and advancing motion generation models.

# 📊Evaluation Results

## Gallery

**Prompt:** A tourist joyfully splashes water in an outdoor swimming pool, their arms and legs moving energetically as they playfully splash around.
<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/74a0f3b0-6a39-42fe-98de-4a18d4130837" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/7437404c-d732-4e57-9b74-bf1977bc5bfc" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/fbce3824-2cab-426f-a684-ba020366fea2" width="100%" controls autoplay loop></video>
     </td>
  </tr>
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/adf91760-ee43-4dae-8675-d6be9584ef98" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/095d2455-2456-4fdf-a36f-1eee7d3485df" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/14b8787b-1fe0-4c75-9c93-0107198a436f" width="100%" controls autoplay loop></video>
     </td>
  </tr>
</table>

**Prompt:** Three books are thrown into the air, their pages fluttering as they soar over the soccer field, landing in a scattered pattern.

<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/5e5432c0-4eb1-40cb-b38d-cb179763d3f8" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/dba7d40c-de5e-4f58-aa2c-4359daa0b358" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/6d3fd125-52e9-482a-b298-a457b5dcf0c9" width="100%" controls autoplay loop></video>
     </td>
  </tr>
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/114c250c-02b1-4755-8f5a-7ab0c2531c6f" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/e4bd1e41-6fc4-48ab-87a1-cb50788a8041" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/ab7e94d4-69c0-47bf-9868-fbd5bcad9b1c" width="100%" controls autoplay loop></video>
     </td>
  </tr>
</table>










**Prompt:** Four flickering candles cast shadows as they burn steadily on the balcony, their flames dancing with the gentle breeze.

<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/74a0f3b0-6a39-42fe-98de-4a18d4130837" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/7437404c-d732-4e57-9b74-bf1977bc5bfc" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/fbce3824-2cab-426f-a684-ba020366fea2" width="100%" controls autoplay loop></video>
     </td>
  </tr>
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/adf91760-ee43-4dae-8675-d6be9584ef98" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/095d2455-2456-4fdf-a36f-1eee7d3485df" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/14b8787b-1fe0-4c75-9c93-0107198a436f" width="100%" controls autoplay loop></video>
     </td>
  </tr>
</table>

**Prompt:** Two penguins waddle along the beach, occasionally stopping to preen their feathers before continuing their journey across the ocean shore.

<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/74a0f3b0-6a39-42fe-98de-4a18d4130837" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/7437404c-d732-4e57-9b74-bf1977bc5bfc" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/fbce3824-2cab-426f-a684-ba020366fea2" width="100%" controls autoplay loop></video>
     </td>
  </tr>
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/adf91760-ee43-4dae-8675-d6be9584ef98" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/095d2455-2456-4fdf-a36f-1eee7d3485df" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/14b8787b-1fe0-4c75-9c93-0107198a436f" width="100%" controls autoplay loop></video>
     </td>
  </tr>
</table>

**Prompt:** In the bustling street, two kids run towards a small dog, bending down to carefully comb its fur, their hands moving swiftly.

<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/74a0f3b0-6a39-42fe-98de-4a18d4130837" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/7437404c-d732-4e57-9b74-bf1977bc5bfc" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/fbce3824-2cab-426f-a684-ba020366fea2" width="100%" controls autoplay loop></video>
     </td>
  </tr>
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/adf91760-ee43-4dae-8675-d6be9584ef98" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/095d2455-2456-4fdf-a36f-1eee7d3485df" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/14b8787b-1fe0-4c75-9c93-0107198a436f" width="100%" controls autoplay loop></video>
     </td>
  </tr>
</table>

**Prompt:** In the garage, a young girl twirls gracefully, her arms outstretched, perfectly matching the lively country line dance beat.

<table border="0" style="width: 100%; text-align: left; margin-top: 20px;">
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/74a0f3b0-6a39-42fe-98de-4a18d4130837" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/7437404c-d732-4e57-9b74-bf1977bc5bfc" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/fbce3824-2cab-426f-a684-ba020366fea2" width="100%" controls autoplay loop></video>
     </td>
  </tr>
  <tr>
      <td>
          <video src="https://github.com/user-attachments/assets/adf91760-ee43-4dae-8675-d6be9584ef98" width="100%" controls autoplay loop></video>
      </td>
      <td>
          <video src="https://github.com/user-attachments/assets/095d2455-2456-4fdf-a36f-1eee7d3485df" width="100%" controls autoplay loop></video>
      </td>
       <td>
          <video src="https://github.com/user-attachments/assets/14b8787b-1fe0-4c75-9c93-0107198a436f" width="100%" controls autoplay loop></video>
     </td>
  </tr>
</table>

## Quantitative Results

*   [ ] 模型表现的五边形图
    

### VMBench Leaderboard

# 🔨 Installation

## Create Environment

```shell
git clone https://github.com/Ran0618/VMBench.git
cd VMBench

# create conda environment
conda create -n VMBench python=3.10
pip install torch torchvision

# Install Grounded-Segment-Anything module
cd Grounded-Segment-Anything
python -m pip install -e segment_anything
pip install --no-build-isolation -e GroundingDINO
pip install -r requirements.txt

# Install Groudned-SAM-2 module
cd Grounded-SAM-2
pip install -e .

# Install Q-Align module
cd Q-Align
pip install -e .

# Install VideoMAEv2 module
cd VideoMAEv2
pip install -r requirements.txt
```

## Download checkpoints
Place the pre-trained checkpoint files in the `.cache` directory at the root of the repository.
Our model's checkpoints are provided on HuggingFace.

```shell
mkdir .cache
cd .cache

huggingface-cli download [your-org]/[your-model] --local-dir .cache/
```
Please organize the pretrained models in this structure:
```shell
VMBench/.cache
├── baseline_offline.pth
├── baseline_online.pth
├── groundingdino_swinb_cogcoor.pth
├── groundingdino_swint_ogc.pth
├── sam2.1_hiera_large.pt
├── sam_vit_h_4b8939.pth
├── scaled_offline.pth
├── scaled_online.pth
└── vit_g_vmbench.pt
```

# 🔧Usage

## Videos Preparation

Generate videos of your model using the 1050 prompts provided in `prompts/prompts.txt` or `prompts/prompts.json` and organize them in the following structure:

```shell
VMBench/eval_results/videos
├── 0001.mp4
├── 0002.mp4
├── 0003.mp4
├── 0004.mp4
...
└── 1050.mp4
```

**Note:** Ensure that you maintain the correspondence between prompts and video sequence numbers. The index for each prompt can be found in the `prompts/prompts.json` file.

 <!-- Please follow our `sample_demo.py`to create videos.  -->
 You can follow us `sample_video_demo.py` to generate videos.
 Or you can put the results video named index into your own folder.
    

## Evaluation on the VMBench

`bash evaluate.sh your_videos_folder`

# ❤️Acknowledgement

# 📜License
The VMBench is licensed under [Apache-2.0 license](http://www.apache.org/licenses/LICENSE-2.0). You are free to use our codes for research purpose.

# ✏️Citation
