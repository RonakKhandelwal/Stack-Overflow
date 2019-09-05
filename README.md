# Stack Overflow Data Analysis

My take on extracting insights from the dataset that stack overflow periodically dumps. Using machine learning models I try to find the approximate amount of time it should take for a question to get answered. 

## Getting Started

Download anaconda and open the file. Download the dataset from here https://www.kaggle.com/stackoverflow/stacksample and place it in the directory containing the directory containing the code file. 
Once the setup is complete. Just hit run and you'll see the output of the specific blocks.

### Methodology

To first undetstand how the questions are rated on stack overflow I took into account the advice penned down by the highest rated stack overflow user, Jon Skeet, and the paper on Evidence-based Guidelines for Writing Questions on Stack Overflow https://arxiv.org/abs/1710.04692 as reference and went forward on checking if a question is good enough or not. 

The idea was to give each question a particular score and any question which has a score above the threshold holds a reasonable chance at being answered. 

We could use other characterstics of the question such as the askers reputation, the question tags and the current trending tags to try to predict a timeline of responses to such a question. 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Jon Skeet, https://stackoverflow.com/users/22656/jon-skeet
* https://arxiv.org/abs/1710.0469
