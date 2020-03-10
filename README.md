# Privacy-Preserving Robot Vision with Anonymized Faces by Extreme Low Resolution (ORB-SLAM2), IROS'19

By Myeung-Un Kim, Harim Lee, Hyun Jong Yang and Michael S. Ryoo.

## Abstract 

Our proposed camera system detects privacy-sensitive blocks, i.e., human face, from extreme low resolution (LR) images, and then dynamically enhances the resolution of only privacy-insensitive blocks, e.g., backgrounds. Keeping all the face blocks to be extreme LR of 15x15 pixels, we can guarantee that human faces are never at high resolution (HR) in any of processing or memory, thus yielding strong privacy protection even from cracking or backdoors.  

Our camera system produces an image on a real-time basis, the human faces of which are in extreme LR while the backgrounds are in HR. We experimentally confirm that our proposed face detection camera system outperforms the state-of-the-art small face detection algorithm, while the robot performs ORB-SLAM2 well even with videos of extreme LR faces. Therefore, with the proposed system, we do not too much sacrifice robot perception performance to protect privacy.

[[Paper]](https://ieeexplore.ieee.org/document/8967681)

If you find our work useful in your research, please consider cite:
```bibtex
@inproceedings{kim-iros2019,
  title = {Privacy-Preserving Robot Vision with Anonymized Faces by Extreme Low Resolution},
  author = {Myeung Un Kim and Harim Lee and Hyun Jong Yang and Micheal S. Ryoo},
  booktitle = {IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year = {2019}
}
```
Feel free to contact Myeung Un Kim (grownmu@unist.ac.kr) if you have any questions!

## Some Results

![image](https://user-images.githubusercontent.com/26617052/76276344-ed27a100-62c8-11ea-82fe-0337c6a25aba.png)

#### Result of ORB-SLAM2 using high resolution video (top) and our privacy-preserving face detection video (bottom)  
As shown in the results on the right, we can extract enough features for ORB-SLAM2 in privacy-preserving face detection video. Full video is available at the following link. [[Youtube]](https://youtu.be/_W6e6xPRsM0)

## How to use it
### Preparation
First of all, clone the code

```
git clone https://github.com/myeungun/ORB-SLAM2.git
```
