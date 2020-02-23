# SPDecolor
Semi-parametric decolorization with Laplacian-based perceptual quality metric

%SPDecolor - contrast preserving color to gray by Semi-Parametric optimization  
% S = SPDecolor(Im, sigma) performs contrast preserving decolorization   
% on color image Im, with controling parameter sigma   
%  
% Paras:   
% @Im : Input image (double), only color images are acceptable.   
% @sigma : Controlling parameter defined in [1]. 5e-3 by default.  
%  
% Example  
% ==========  
% Im = im2double(imread('5.png'));  
% gIm = SPDecolor(Im); % Default Parameters (sigma = 1e-2)  
% figure, imshow(Im), figure, imshow(gIm);  


## Demonstration of SPDecolor
![](./figs/DemonstrationSPDecolor2.png)  


## Other Related Projects
  * GcsDecolor: Gradient Correlation Similarity for Efficient Contrast Preserving Decolorization [<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/7088620)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/GcsDecolor)

  * Log-Euclidean Metrics for Contrast Preserving Decolorization
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/8016668)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/LeDecolor)

  * Variable augmented neural network for decolorization and multi-exposure fusion [<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/abs/pii/S1566253517305298)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/DecolorNet_FusionNet_code)
