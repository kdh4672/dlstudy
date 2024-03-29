# Deep leraning implementation study (2020/07/12~)

# Project List

## Weak 1. (VAE)
- TODO : Training VAE by my face dataset to see distribution of face dataset.
- Implementation Complemented! [[Face_VAE_Code](https://github.com/kdh4672/Face_VAE/blob/master/VAE/VAE_Face.py)]
- VAE_Paper :  [[VAE_Paper link](https://arxiv.org/pdf/1312.6114.pdf?source=post_page---------------------------)]
- VAE_Review : [[VAE_Review link](https://github.com/kdh4672/DH_Lab/blob/master/Paper_Review/VAE.pdf)]
- Face_VAE_Repository : [[Repository_link](https://github.com/kdh4672/Face_VAE/tree/master/VAE)]
## Model Architecture
![VAE](https://user-images.githubusercontent.com/54311546/87496168-ffa65280-c68d-11ea-82c6-1cabbb0ecd4e.jpg)

## Training VAE gif
![faces_n1](https://user-images.githubusercontent.com/54311546/87400438-c6b99f80-c5f3-11ea-8ef4-52d0881840cd.gif)

## Training VAE result (Sampled at z_mean -3~3)
![VAE_result](https://user-images.githubusercontent.com/54311546/87406921-667b2b80-c5fc-11ea-8a5c-e666ef6583bb.png)


[[VAE_발표용.pptx](https://github.com/kdh4672/dlstudy/files/4942047/VAE_.pptx) 다운로드]
## Plan (Weak 2~)
- Plan for Face Recognition [[Plan.pdf](https://github.com/kdh4672/dlstudy/files/4943848/default.pdf)]

## Weak 2.
- TODO : GAN Tutorial
- Tutorial Link: [[GAN_Tutorial](https://dreamgonfly.github.io/blog/gan-explained/)]
- GAN_Paper :  [[GAN_Paper link](https://github.com/kdh4672/DH_Lab/blob/master/Interesting_Papers/GAN.pdf)]
- Implementation Complemented! [[GAN Tutorial_Code](https://github.com/kdh4672/DH_Lab/blob/master/Deeplearning_Basic/GAN_Tutorial_Mnist.ipynb)]
- Code Review : [[GAN - Jupyter Notebook.pdf](https://github.com/kdh4672/DH_Lab/blob/master/Deeplearning_Basic/GAN%20-%20Jupyter%20Notebook.pdf)]
- Result: lfw crop images #13000

![epoch99](https://user-images.githubusercontent.com/54311546/88498013-ee016b00-cffc-11ea-95b9-b8115824de47.png)
## Weak 3
- TODO : Face Alignment
- What are Used : dlib,opencv
- Impelementation Code : [[Dlib Code](https://github.com/kdh4672/DH_Lab/tree/master/Deeplearning_Basic/Dlib)]

- Face Detection Video (click photo to enter youtube link)
[![omygirl_screenshot](https://user-images.githubusercontent.com/54311546/88782755-eb537100-d1c8-11ea-9201-a6b832aae33c.png)](https://www.youtube.com/watch?v=0F1oqP9ooMA&feature=youtu.be)

<!-- ## Weak 4
- TODO : ArcFace Loss implementation
- Code Reference: [[Repo1](https://github.com/TreB1eN/InsightFace_Pytorch)], [[Repo2](https://github.com/ronghuaiyang/arcface-pytorch)] ,*[[Repo3](https://github.com/wujiyang/Face_Pytorch)]
- ArcFace Paper Review : [[ArcFace](https://github.com/kdh4672/DH_Lab/blob/master/Paper_Review/Arcface.pdf)]
- Presentation File : [[Arcface.pptx](https://github.com/kdh4672/dlstudy/files/5078083/Arcface.pptx)]
- Test1 : Center is Kong,  Not perfect but almost
![result](https://user-images.githubusercontent.com/54311546/90228642-89923880-de51-11ea-9c1c-af1dea9c4466.gif)
- Test2 : Added Confidential Score

![confidence](https://user-images.githubusercontent.com/54311546/90315291-3bfef400-df55-11ea-9d35-2819bf5dec30.gif)

 -->
<!-- ## Weak 5
- TODO : Upgrade Face recognition performance
- What's New : Extract Featrues'degree Compared to Center, and the second nearest degree, Apply Thresh Hold at degree 30
- Model is Trained with Three class people
- Kong Result: 

![Kong_Output](https://user-images.githubusercontent.com/54311546/90952351-e61ed480-e49d-11ea-8619-442ba044466b.gif)
- June Result:

![June_Output](https://user-images.githubusercontent.com/54311546/90952358-f6cf4a80-e49d-11ea-8ec7-8deacfdae78a.gif)
- Sim Result:

![output_sim](https://user-images.githubusercontent.com/54311546/92383637-aa486800-f149-11ea-9c24-0bb817e408c4.gif)
 -->

- Three People:

![output](https://user-images.githubusercontent.com/54311546/92383726-d19f3500-f149-11ea-886c-e5c305c9fad6.gif)


