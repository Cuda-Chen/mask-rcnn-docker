# mask-rcnn-docker
A project that houses a Dockerfile to get started with the [Matterport Mask R-CNN project](https://github.com/matterport/Mask_RCNN)
 and [my Mask R-CNN project](https://github.com/Cuda-Chen/Mask_RCNN).

# Usage
build the docker image
```
$ docker build -t cudachen/mask-rcnn-docker
```

 Run
```
$ docker run -it -p 8888:8888 -p 6006:6006 -v ~/:/host cudachen/mask-rcnn-docker
```

then import the relevant namespaces from mrcnn in your Python file
```python
import mrcnn.model
```

# Reference
- https://github.com/deontaljaard/mrcnn-docker
- https://github.com/waleedka/modern-deep-learning-docker

