<h2 font-size:40px align="center">Image Generation by using a Text Prompt (VQGAN + CLIP + ESRGAN implementation)</h2>

<h3 align="center">By Siddhant Bikram Shah</h3>
<br>

<p align="center">
  <img src="https://github.com/SiddhantBikram/ImageGeneration/blob/main/Outputs/Nepal%20Himalayas%20Clouds%20Sky%20Heavenly%20ESRGAN.png" height = 300 width="300" title="hover text">
</p>

<h6 align="center">Prompt: Nepal, Himalayas, Clouds, Sky, Heavenly</h6>
<br>

<b>Colab Link: https://colab.research.google.com/drive/1Fg1O_joen0CY56hTO5UBNuoyjFewPEh2</b>

<b>Instructions for use of VQGAN+CLIP+ESRGAN_Implementation.ipynb:</b>

1. The file is meant to be run on Google Colab.
2. A text prompt should be given in the parameter section. The default text prompt is 'Hogwarts Castle of Witchcraft and Wizardry Pencil Sketch'.
3. An image is given as output every 50 iterations when VQGAN+CLIP is run.
4. The code will run for ~20 minutes before reaching 500 iterations based on the GPU allotted by Google Colab.
5. After 500 iterations, ESRGAN will process the image automatically and the super-resolution image thus generated can be found at content/ESRGAN/results/500.png

Thank you! If you have any questions, please feel free to reach out to siddhantshah3000@gmail.com
<br>
<br>

<b>References:</b>

1. Esser, Patrick, Robin Rombach, and Bjorn Ommer. "Taming transformers for high-resolution image synthesis." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2021.
2. Li, Yangguang, et al. "Supervision exists everywhere: A data efficient contrastive language-image pre-training paradigm." arXiv preprint arXiv:2110.05208 (2021).
3. Wang, Xintao, et al. "Esrgan: Enhanced super-resolution generative adversarial networks." Proceedings of the European conference on computer vision (ECCV) workshops. 2018.
