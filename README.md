## Unlocking Sentiments in Code-Mixed texts using ensemble models of CNN and self-Attention Models

For analyzing sentiment of code mixed social media text. 

The approach used was to the strengthen the prevailent CNN structure with a self attention model to better enable the classification of neutral tweets.

The instructions to run the code are given below :


### Getting Started

A step by step series of examples that tell you how to get the code running in kaggle

Clone the repo

```
!git clone https://github.com/yasar-arafath/USCE
```

#### Install the project dependencies:
```
%cd /kaggle/working/USCE
!pip3 install -r requirements.txt
```

### Running
```
%cd /kaggle/working/USCE/src
!python main.py <dataset_name>

Example:
  python main.py hinglish
  python main.py spanglish
```
Note: We have shown our results on two datasets namely Hinglish and Spanglish
