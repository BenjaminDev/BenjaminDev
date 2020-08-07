#### :hammer: Under Construction :warning:
## Repositories :book:
I've organised some of my code into projects, templates, and infrastructure. They are all tagged and searchable. All these projects are my own. If you find bugs please feel free to open an issue. 
### Projects :hammer:

- [imse](https://github.com/BenjaminDev/imse) An image search tool aimed at the civil engineering and surveying industry. Search your images using query images and selected regions of interest.
- [zizu](https://github.com/zizu-research/zizu) A sports video analytics tool aimed at [speed climbing](). It processes a video of a speed climbing 'run' and  detects the climber(s) and their [keypoints](). It stitches the frames together to form a single image plane and then uses the known geometry of the wall to register this image with a real world model. The output is a `x,y` real world coordinate of each of the climbers keypoints. Using this position and time graphs can be derived and used to compare competiors and used as a training and performance monitoring tool. It is capable of processing panning footage captured by either a cellphone (instagram style clips) or a live stream system.  
- [Aircraft tracking]() This is a closed source project. It is a passive system that can detect and track multiple aircraft using a single camera. By using known landmarks in the scene the camera pose is estimated. Targets are tracked in a region of interest and due to a strong motion model (aircraft dynamics) the sysem can infer 3D world coordinates despite its single camera limitation. Published results can be seen [here](msc)  



### Templates :copy:
These templates were born out of doing the same setup too many times. Either for myself or for others.
- [python-only]() A template for pure python projects. It uses [poetry](), [pre-commit](), [docker]() for developement environment and [github actions] for CI/CD.
- [cpp-python]() A template for cmake based [cpp] projects that use [pybind11] to provide python bindings.
- [cpp-only]() A cmake template that uses [clang-formatter], [github actions] and builds both linux and windows binaries.

### Infrastructure :building:
I really dislike the [aws] console these repos make setting up a gpu instance for training an ML model super easy. Workflows for aws and colab are shown.
- [gpu-ami]() A Packer based ami for swift and cheap ami stroage.
- [minimal-aws-setup]() A terraformed setup that is useful for datascience and ML projects as well as a simple deployment usecase.

#### Notes: :pen:
If you are looking to hire in the areas of computer vision, machine learning or digital signal processing please don't hesitate to contact me via [linkedin]().

### 🏆 Github Status
![My Github Status](https://github-readme-stats.vercel.app/api?username=benjaminDev&show_icons=true&hide_border=true&count_private=true)
<!--
**BenjaminDev/BenjaminDev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
<img align='right' src='https://github.com/Rishit-dagli/Rishit-dagli/blob/master/images/octocat-anime.gif' width='150"'>
for adding a gif
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
