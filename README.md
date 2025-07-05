## Contextural Gesture [ACMMM 2025]:

For people who are requesting code:

Due to this is an internshop project i have finished last year at Flawless AI. I am not sure when i shall reach the aggrement with the company and if it is able to be released.
This is a two-stage generation framework which first generate 2D motion keypoints and then leverage 2D animation models to achieve audio-driven video generation. 

### Motion Generation
For the motion generation, I strongly suggest my recent work [Intentional-Gesture](https://github.com/andypinxinliu/Intentional-Gesture). The core idea of building semantic-aware motion representation is somehow similiar.

### Video Animation
If you are looking for Video animation part, I acknology the development for human video animation develops soooo quick and the performance from the baseline matters a lot.
If possible, we will recommend [MTVCtafter](https://dingyanb.github.io/MTVCtafter/) if you want to use 3D SMPL-X keypoints for control. 
If you want to use 2D keypoints, I will recommand the [UniAnimate-DiT](https://github.com/damo-cv/RealisDance) or [UniAnimate-DiT](https://github.com/ali-vilab/UniAnimate-DiT).
