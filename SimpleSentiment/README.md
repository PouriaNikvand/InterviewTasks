<h1>In this project we want to solve a sentiment problem.</h1>

<h2>Dataset</h2>
- Use MultiClass DeepSentiPers original Dataset in your dataset folder for this task
<ol> <li>Furious</li> <li>Angry</li> <li>Neutral</li> <li>Happy</li> <li>Delighted</li> </ol>
<div class="table-wrapper"><table> <thead> <tr> <th style="text-align: center">Label</th> <th style="text-align: center">#</th> </tr> </thead> <tbody> <tr> <td style="text-align: center">Furious</td> <td style="text-align: center">236</td> </tr> <tr> <td style="text-align: center">Angry</td> <td style="text-align: center">1357</td> </tr> <tr> <td style="text-align: center">Neutral</td> <td style="text-align: center">2874</td> </tr> <tr> <td style="text-align: center">Happy</td> <td style="text-align: center">2848</td> </tr> <tr> <td style="text-align: center">Delighted</td> <td style="text-align: center">2516</td> </tr> </tbody> </table></div>
```
@misc{sharami2020deepsentipers,
    title={DeepSentiPers: Novel Deep Learning Models Trained Over Proposed Augmented Persian Sentiment Corpus},
    author={Javad PourMostafa Roshan Sharami and Parsa Abbasi Sarabestani and Seyed Abolghasem Mirroshandel},
    year={2020},
    eprint={2004.05328},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```

<h2>Solve This Task In The Following Sections</h2>

- Build a Language Model
- Build a Classifier Model
- Write a RestApi for your model for testing
- Build a Docker Image for your code
- Config Your Docker Image

<h2>BUILD LANGUAGE MODEL<h2>

- Build a Language model Using Gensim.

<h2>BUILD CLASSIFIER</h2>

- Build a Deep model using your Language model and analyze the challenges and problems. You have to explain your works for details of choosing hyperparameters and models you have used in your classifier.
- If you have any idea for solving this problem in any other ways, DO IT! 😁
- Tell Us What is your best Idea for solving this problem and what do you want to do for future works.

<h2>WRITE REST API</h2>

- Write a RestApi using flask or Django for testing your sentiment model.

<h2>***Bonus***</h2> 👇👇👇

<h2>BUILD DOCKER IMAGE</h2>

- Build an image for your project and setup the DockerFile and docker-compose for running and testing your code.

<h2>CONFIGURE AND DEPLOY</h2>

- For this part you have to setup nginx and gunicorn for your RestApi, setup the number of workers and solve the low stack memory and queue problems in deployments.
