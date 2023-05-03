# **Machine Learning Group Project:** Team 7 
- **Course & Course Code:** Machine Learning (2487)
- **Instructors:** Qiwei Han & Alessandro Gambetti
- **Academic Year:** 2022/2023

This project was developed by Alessandro Alfio Maugeri, Frank Andreas Bauer, Johannes Rahn, 
Nicole Zoppi, and Yannick von der Heyden as part of Nova SBE's Machine Learning course taught during Semester 2 of 
the 2022/2023 academic year by Qiwei Han and Alessandro Gambetti. The purpose of the group work is to develop an end-to-end 
Machine Learning project with data of our choice, clearly highlighting the business use for our model.

The project exploits data from two distinct Kaggle pages (["Game Recommendations on Steam"](https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam?select=games.csv) and ["Steam Store Games (Clean dataset)"](https://www.kaggle.com/datasets/nikdavis/steam-store-games?select=steam.csv)) which contain data on content published to the Steam libary (e.g. games and DLCs) and user-generated content associated with it (e.g. whether a review is positive or not, what general consensus is, how many people found the review useful, etc.). The final work merges data from 4 distinct CSV files and 1 JSON, all of which can be found in the _data_ folder and all of whose contents are covered in detail in notebook [a_csv_creation.ipynb]("a_csv_creation.ipynb"). 

The objective is to develop a Machine Learning pipeline from beginning to end whose output has a clear, pertinent, and useful business use. In this project, we explore multiple models in order to identify the one which is best-suited for predicting whether a given Steam user will enjoy a game or not. This should allow Steam to optimize its service by tailoring it to individual clients and fine-tuning their recommender systems. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

To get started with the project, please follow these steps:

1. Clone the repository to your local machine:
```bash
git clone https://github.com/JohannesRahn/MachineLearningGroupProject.git
```
2. Navigate to the cloned repository:
```bash
cd MachineLearningGroupProject
```
3. **Install the required dependencies by running:**
```bash
pip install -r requirements.txt
```
4. Download the recommendations.csv file from the Game Recommendations on [Steam Kaggle](https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam?select=recommendations.csv) page.

5. Add the recommendations.csv file to the _data_ folder in the local repository.

6. You're now ready to run the project! Navigate to the MachineLearningGroupProject folder and open a_csv_creation.ipynb to get started.

Note: The project is on the _main_ branch, so make sure you are on that branch when cloning the repository.

## Usage

Instructions on how to use the project, including any configuration or setup required. Examples of usage can be included as well.

## Contributing

Contributions to this project are always welcome! To contribute, please follow these steps:

1. Fork this repository to your own GitHub account
2. Clone your forked repository to your local machine
3. Create a new branch for your changes: git checkout -b my-new-branch
4. Make your changes and commit them with a descriptive commit message: git commit -am 'Add some feature'
5. Push your changes to your forked repository: git push origin my-new-branch
6. Submit a pull request from your branch to our main repository
7. Please include a clear and descriptive commit message and make sure your code follows our coding conventions and style guide. 8. Once your pull request is submitted, we will review your changes and provide feedback or request further changes if necessary.

**Thank you for your contributions!**

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](license.md) file for details.

## Contact

Contact information for the project owner and maintainers:

| Name                      | Email                |
|---------------------------|------------------------|
| Alessandro Maugeri  | [53067@novasbe.pt](mailto:53067@novasbe.pt) |
| Frank Andreas Bauer |[53121@novasbe.pt](mailto:53121@novasbe.pt) |
| Johannes Rahn          | [53958@novasbe.pt](mailto:53958@novasbe.pt) |
| Nicole Zoppi              | [53854@novasbe.pt](mailto:53854@novasbe.pt) |
| Yannick von der Heyden | [53629@novasbe.pt](mailto:53629@novasbe.pt) |
