# Face detection with Viola-Jones
### Using OpenCV

- To test on images:

```
python test_images.py --face cascades/haarcascade_frontalface_default.xml --image images/obama.png
```

- To test on a video file:

```
python test_video.py --face cascades/haarcascade_frontalface_default.xml --video video.mp4
```
> Where video.mp4 should be a video file in your disk.

- To test on a webcam:

```
python test_video.py --face cascades/haarcascade_frontalface_default.xml
```

## References
- Viola-Jones paper: https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf
- Haar wavelets (where Haar cascades get their name): https://en.wikipedia.org/wiki/Haar_wavelet
- Haar cascades (using AdaBoost): https://en.wikipedia.org/wiki/AdaBoost

---

saimj7/ 19-05-2021 © <a href="http://saimj7.github.io" target="_blank">Sai_Mj</a>.
