<p align="center"><img src="https://socialify.git.ci/jeezusplays/slay-fake-news/image?description=1&amp;font=Inter&amp;forks=1&amp;issues=1&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Plus&amp;pulls=1&amp;stargazers=1&amp;theme=Dark" alt="project-image"></p>

<h1 align="center" id="title">IS460 - Machine Learning and Applications G2 Project: Emotional Speech Detection</h1>

## About the Project
This research project delves into the intricate domain of Speech Emotion Detection, aiming to unravel emotional cues from audio data. It explores various modeling techniques, encompassing deep learning, classical machine learning, and feature selection approaches, to construct robust emotion recognition systems.

Among the models developed, a baseline model using Support Vector Machines (SVM) serves as a comparison standard. SVM, a classical machine learning method, was implemented with a focus on distinctly classifying data points in a multidimensional space. Extensive experimentation was performed, including GridSearch with multiple kernel options. The SVM model was trained on the speech dataset, forming a benchmark for the subsequent models.

To address the challenge of high-dimensional feature space, the feasibility of Principal Component Analysis (PCA) for feature reduction was explored. PCA was applied to the standardized data, yielding a reduced set of principal components while maintaining a desired explained variance. However, subsequent evaluations revealed a slight decrease in model performance, prompting the decision to prioritize a more comprehensive feature set over processing time.

## Built With
- `ipykernel`: An IPython kernel for Jupyter used to run Python code cells within Jupyter notebooks.
- `librosa`: A Python library for audio and music analysis, which provides the building blocks needed to create music information retrieval systems.
- `pandas`: A powerful data structures and data analysis library for Python.
- `matplotlib`: A Python 2D plotting library which produces quality figures in a variety of hardcopy formats and interactive environments.
- `seaborn`: A Python data visualization library based on matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics.
- `resampy`: Efficient sample rate conversion in Python, which is probably being used to convert the sample rates of audio files.
- `tensorflow`: An end-to-end open source platform for machine learning, suggesting that machine learning models are part of this project.

## Getting Started
To get a local copy up and running, follow these simple steps.

**1. Create environment**  
```
python -m venv mla-env
```  

**2. Activate environment**  
- For Windows (Powershell), use: 
```
mla-env/Scripts/Activate.ps1
```  
- For Mac, use: 
```
source mla-env/bin/activate
``` 

**3. Install kernel in environment** 
``` 
pip install ipython  
pip install ipykernel  
ipython kernel install --user --name=mla-env
```

**4. To add new packages, add it in requirements and run**  
```
pip install -r requirements.txt
```  

**5. To run jupyter notebook, run**  
```
jupyter notebook
```  
- Note: Ensure that you are using the kernel `mla-env` by
clicking on `Kernel > Change kernel > mla-env`

## Contributing
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
**Don't forget to give the project a :star: star :star:!** Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b /newFeature`)
3. Commit your Changes (`git commit -m 'Add some newFeature'`)
4. Push to the Branch (`git push origin /newFeature`)
5. Open a Pull Request

## Team
Feel free to contact and connect!

|| Name | Github |
|-----------| ----------- | ----------- |
|<img src="https://avatars.githubusercontent.com/u/68149788?v=4" width="100"></img>| Joey |[![Joey](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/jeezusplays)|
|<img src="https://avatars.githubusercontent.com/u/60221049?v=4" width="100"></img>| Bodine | [![Bodine](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/bodinestubbe) |
|<img src="https://avatars.githubusercontent.com/u/41113285?v=4" width="100"></img> | Samuel | [![Samuel](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/samchung95) |
|<img src="https://avatars.githubusercontent.com/u/71541700?v=4" width="100"></img> | Shambhavi | [![Sham](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/po-the-panda-12) |
|<img src="https://avatars.githubusercontent.com/u/5838225?v=4" width="100"></img> | Darryl | [![Darryl](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/DarrylSSY) |
|<img src="https://avatars.githubusercontent.com/u/88470259?v=4" width="100"></img> | Elston | [![Elston](https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/Swagston20) |

