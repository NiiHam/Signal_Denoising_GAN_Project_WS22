# INSTRUCTIONS TO UPLOAD YOUR PROJECT

We use this to guarantee the same structure for all projects.
Projects will be then uploaded to our [project page](https://opencampus-sh.github.io/oc-ml-projects/) and there these information will be displayed.
So you can check at any time the [project page](https://opencampus-sh.github.io/oc-ml-projects/) to have an idea about how that would look like.

### Objective

Your objective is to train a neural network to estimate the sales from past data. You can choose the form of the input and the output, usually the input is the data for a specific day (or more than one day) and the output is the sales for a specific day (or more than one).

### Data

More information on the data can be found in the data folder.
We have 2 datasets, which they contain similar data, the first one is smaller and maybe a bit simpler (and alreay used), the second may require some small pre-processing and is a bit larger and contains more location (so more challenging).
In each folder there is a presentation or a readme file to explain.

### Technical Information

It is advisable to start using FFNN without special features and find the optimal architecture configuration. Later you can use LSTM, CNN (1D) or whatever you like to try to improve the result.

### Target Results

To compare your results with the ones from previous groups, please use the Mean Absolute Percentage Error ([Wikipedia](https://en.wikipedia.org/wiki/Mean_absolute_percentage_error) - [Tensorflow Metric](https://www.tensorflow.org/api_docs/python/tf/keras/metrics/MeanAbsolutePercentageError))

Approximately you should reach an error below 20% on the prediction for a single day in the dataset1. Best results from the last semesters arrived around 15-16% error.

Once you are done, you could indicate the error you got (MAPE) and which architecture you used and it will be added here in a sort of ranking.

### Past Projects

For this project in particular, there were already 2 implementations:
- [SoSe 21, Group 1, Johannes Dupont, Pavan Jethvani, Osama Alrabayah, Jannik Knopp](https://github.com/opencampus-sh/ML-Projects/tree/main/data/DLFS/Bakery-Sales-project)
- [SoSe 21, Group 2, Amelie Schmuecker, Samira Ferssioui, Niko Schmidt, Christopher Hansen](https://github.com/opencampus-sh/ML-Projects/tree/main/data/DLFS/BakerySalesPrediction)

### Steps to follow

0. *if you are reading on Github*, clone or download this repository to your computer.
1. rename the folder `project_template_folder` to the name of your project (please avoid spaces in the name of the folder).
2. complete the `INFO.md` file with title, description, students name, course, semester and whatever is asked there
3. upload the required documents:
   * the code (one or more notebooks or python code) in the `code` folder. Inside the folder there is already a notebook with some informations. Please make sure to check it and start from there.
   * a picture of that represent your project in the `preview` folder. It will be used as a preview for the online visualization. It should have width larger than its height (something like 500x280 may work good), but it's not absolutely necessary. It will be centered anyway. Higher resolution will be down-scaled, so do not upload images higher than 720 pixels.
   * other resources you may need in the `resources` folder
   * please do not upload the dataset you used unless there are special reasons.
4. (Optional) rename `INFO.md` as `README.md`. This way when people open your repository page, they will see the information about your project (and not the instructions to upload it). The `README.md` file is automatically showed from github.
5. compress the whole folder as a `.zip` file and check the size. Please do not upload files larger than `10Mb`. If you have special reason to do so, please let us know before you upload.
6. upload the `.zip` file in your course's online page. If you do not know where, ask your teacher.
