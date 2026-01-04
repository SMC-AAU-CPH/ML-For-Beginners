# Machine Learning for Beginners - A Curriculum

> 🌍 Travel around the world as we explore Machine Learning by means of world cultures 🌍

Aalborg University and Microsoft are pleased to offer a curriculum about **Machine Learning**. In this curriculum, you will learn about what is sometimes called **classic machine learning**, using primarily Scikit-learn as a library.

Travel with us around the world as we apply these classic techniques to data from many areas of the world. Each lesson includes pre- and post-lesson quizzes, written instructions to complete the lesson, a solution, an assignment, and more. Our project-based pedagogy allows you to learn while building, a proven way for new skills to 'stick'.

---

# Getting Started

**Experimental:** To use this curriculum out of the box, log in with your github account to this repo, press comma `,` or go directly to [https://github.com/codespaces/new/SMC-AAU-CPH/ML-For-Beginners?resume=1](https://github.com/codespaces/new/SMC-AAU-CPH/ML-For-Beginners?resume=1 "If this is not working, try creating a new one") This is the github codespaces magic:  [https://github.com/features/codespaces](https://github.com/features/codespaces):

Codespaces is **available for free to students** as part of the GitHub Student Developer Pack. Learn more about how to sign up and start using Codespaces and other GitHub products [https://education.github.com/pack](https://education.github.com/pack)

**Safer:** Complete the exercises on your own or with a group on **[Google Colab](https://colab.research.google.com/github/SMC-AAU-CPH/ML-For-Beginners/blob/main/ "Repo on Google Colab")**.

**Safest:** *Fork* or clone (with --depth=1) the entire repo and complete the exercises on your own or with a group locally on VS Code. You must have Visual Studio Code, python, and git installed. If not, we *recommend* package managers: On macOS [homebrew](https://brew.sh), on Linux [apt](https://linuxize.com/post/how-to-use-apt-command), and on Windows [winget](https://learn.microsoft.com/en-us/windows/package-manager/).

```
git clone --depth=1 https://github.com/SMC-AAU-CPH/ML-For-Beginners.git
cd ML-For-Beginners
```

After this `pip install -r requirements.txt `would install all the packages and you'd be up and running.

***Recommendation***: use [uv](https://docs.astral.sh/uv/ "uv docs") for package / dependency / tool management instead. We now provide a [pyproject.toml ](./pyproject.toml)to get you started:

**On macOS/Linux (via shell):**

```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

  or if you use hombrew (also on Linux)

`brew install uv`

**On Windows (via PowerShell):**

```powershell
irm https://astral.sh/uv/install.ps1 | iex # or if you get permission errors:
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

```

or if you use [winget](https://learn.microsoft.com/en-us/windows/package-manager/)

install the entire toolchain (erase what you already have):

```
winget install --id Git.Git -e --source winget
winget install --id Microsoft.VisualStudioCode -e --source winget
winget install --id Python.Python.3 -e --source winget
winget install --id=astral-sh.uv -e
```

##### Finalizing uv on all platforms

Then, assuming you are at the ML-For-Beginners root folder

```
uv sync
code . 
```

Select from any notebook.ipynb the uv kernel (Select-kernel/PythonEnvironments/ml-for-beginners, usually starred). You are good to code and machine learn.

##### Suggested activities

In any case

- Start with a pre-lecture quiz.
- Read the lecture and complete the activities, pausing and reflecting at each knowledge check.
- Try to create the projects by comprehending the lessons rather than running the solution code; however that code is available in the `/solution` folders in each project-oriented lesson.
- Take the post-lecture quiz.
- Complete the challenge.
- Complete the assignment.
- If marked as MandatoryAssignment, submit it to Moodle.

> For further study, we recommend following the link to the [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/k7o7tg1gp306q4?WT.mc_id=academic-15963-cxa) modules and learning paths.

---

## Video walkthroughs

Some of the lessons are available as short form video. You can find all these in-line in the lessons, or on the [ML for Beginners playlist on the Microsoft Developer YouTube channel](https://aka.ms/ml-beginners-videos).

## Meet the Microsoft Team

[![Promo video](ml.gif)](https://youtu.be/Tj1XWrDSYJU "Promo video")

**Gif by** [Mohit Jaisal](https://linkedin.com/in/mohitjaisal)

> 🎥 Click the image above for a video about the project and the Microsoft folks who created it!

---

## Pedagogy

We have chosen two pedagogical tenets while building this curriculum: ensuring that it is hands-on **project-based** and that it includes **frequent quizzes**. In addition, this curriculum has a common **theme** to give it cohesion.

By ensuring that the content aligns with projects, the process is made more engaging for students and retention of concepts will be augmented. In addition, a low-stakes quiz before a class sets the intention of the student towards learning a topic, while a second quiz after class ensures further retention. This curriculum was designed to be flexible and fun and can be taken in whole or in part. The projects start small and become increasingly complex by the end of the 12-week cycle. This curriculum also includes a postscript on real-world applications of ML, which can be used as extra credit or as a basis for discussion.

Find Microsoft's' [Code of Conduct](CODE_OF_CONDUCT.md), [Contributing](CONTRIBUTING.md), and [Translation](TRANSLATIONS.md) guidelines in the links. In 2025, your teacher is [Cumhur Erkut](https://cerkut.github.io/).

## Each lesson includes:

- optional sketchnote
- optional supplemental video
- pre-lecture warmup quiz
- written lesson
- for project-based lessons, step-by-step guides on how to build the project
- knowledge checks
- a challenge
- supplemental reading
- assignment
- post-lecture quiz

> **A note about quizzes**: All quizzes are contained [in this app](https://ff-quizzes.netlify.app/en/ml/), for 52 total quizzes of three questions each. They are linked from within the lessons. Multiple lessons will be contained in Sessions, which are the sessions you'll also see at Moodle.

Below is a preliminary schedule, which mainly follows Microsoft's ML for beginners, from our own fork at [https://github.com/SMC-AAU-CPH/ML-For-Beginners](https://github.com/SMC-AAU-CPH/ML-For-Beginners)

| **Sec** | **Date**     | **Theory**                          | **Lesson Group**                                                                                                                                                      | **Lessons** | **Learning objectives addressed**                                                                                                                                                                                                                                                                                                                                                           |
| ------------- | ------------------ | ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1             | 2025-09-08 Mon 1a  | [Workshop I: Introduction]()                 | [Introduction](1-Introduction/README.md)                                                                                                                                       | 1.1, 1.4          | Multivariate statistics                                                                                                                                                                                                                                                                                                                                                                           |
| 2             | 2025-09-08 Mon 1b  | Supervised Learning I                     | 2-[Regression](2-Regression/README.md)                                                                                                                                         | 2.1-2.4           | [![Open In Colab](https://camo.githubusercontent.com/96889048f8a9014fdeba2a891f97150c6aac6e723f5190236b10215a97ed41f3/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/SMC-AAU-CPH/ML-For-Beginners/blob/main/2-Regression/3-Linear/solution/notebook.ipynb)<br />Least-squares, regression |
| 3             | 2025-09-08 Mon 2a | Supervised learning II                    | 3-[Classification](3-Classification/README.md)                                                                                                                                 | 3.1-3.3           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SMC-AAU-CPH/ML-For-Beginners/blob/main/3-Classification/images/3-Classification.ipynb)                                                                                                                                                                                           |
| 4             | 2025-09-08 Mon 2b | Supervised learning III:Deployment        | [3.4-Applied](3-Classification/4-Applied/README.md)                                                                                                                            | 3.4               | Builds on the previous session<br />Application to media                                                                                                                                                                                                                                                                                                                                          |
| 5             | 2025-09-22 Mon 3  | Unsupervised Learning I                   | [Clustering](5-Clustering/README.md) & Vizualization                                                                                                                           | 14-15             | [![Open 5-Clustering In Colab](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/SMC-AAU-CPH/ML-For-Beginners/blob/main/5-Clustering/images/5-Clustering.ipynb)<br />k-means, tSNE, PCA  |
| 6             | 2025-09-22 Mon 3  | Unsupervised Learning II                  | [Natural Language Processing](6-NLP/README.md)                                                                                                                                | 16-20             | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SMC-AAU-CPH/ML-For-Beginners/blob/main/6-NLP/images/6-NLP.ipynb) <br />Context and application                                                                                                                                                                                  |
| 7             | 2025-09-29 Mon 4  | ~~Time-series analysis~~Motion and Sound | [Time series](7-TimeSeries/README.md). Edge Impulse                                                                                                                            | 21-23             | Application to media<br />[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SMC-AAU-CPH/ML-For-Beginners/blob/main/7-TimeSeries/images/7-TimeSeries.ipynb)TBA                                                                                                                                                                      |
| 7             | 2025-10-20 Mon 5  | Vision                                    | [Time series](7-TimeSeries/README.md). Edge Impulse                                                                                                                            | -                 | TBA                                                                                                                                                                                                                                                                                                                                                                                               |
| 8             | 2025-11-03 Mon 6   | Reinforcement Learning                    | [Reinforcement learning](8-Reinforcement/README.md)                                                                                                                            | -                 | [Q-learning, Gym<br />![Open In Colab](https://camo.githubusercontent.com/96889048f8a9014fdeba2a891f97150c6aac6e723f5190236b10215a97ed41f3/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/SMC-AAU-CPH/ML-For-Beginners/blob/main/8-Reinforcement/images/8-Reinforcement.ipynb)            |
| 9, 10        | 2025-11-17 Mon 7  | Workshop II: Deployment                   | [ML in the Wild](9-Real-World/README.md): [gradio](https://gradio.app/), [streamlit](https://streamlit.io/)Mini-projects<br />[Danish National Champion in AI](https://dmiai.dk/ "DMI-AI") | -                 | Mini-projects                                                                                                                                                                                                                                                                                                                                                                                     |

## Other Curricula

Microsoft team produces other curricula! Check out:

- [AI for Beginners](https://aka.ms/ai-beginners)
- [Data Science for Beginners](https://aka.ms/datascience-beginners)
- [ML for Beginners](https://aka.ms/ml-beginners)
- [Generative AI for Beginners](https://aka.ms/genai-beginners)
- [Generative AI for Beginners .NET](https://github.com/microsoft/Generative-AI-for-beginners-dotnet)
- [Generative AI with JavaScript](https://github.com/microsoft/generative-ai-with-javascript)
- [Generative AI with Java](https://github.com/microsoft/Generative-AI-for-beginners-java)
- [Cybersecurity for Beginners](https://github.com/microsoft/Security-101)
- [Web Dev for Beginners](https://aka.ms/webdev-beginners)
- [IoT for Beginners](https://aka.ms/iot-beginners)
- [XR Development for Beginners](https://github.com/microsoft/xr-development-for-beginners)
- [Mastering GitHub Copilot for Paired Programming](https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming)
- [Mastering GitHub Copilot for C#/.NET Developers](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers)
- [Choose Your Own Copilot Adventure](https://github.com/microsoft/CopilotAdventures)
