Project guidelines

    Decide the topic (see topics)
        Specify the preferences here (Lenker til en ekstern side.)
        Deadline for registering the project is 31.03.2022 (11.59 pm).
    Register your team in Canvas (group registration)
    Check if know the task clearly,
        Is it supervised? or unsupervised task?
        Pattern detection or anomoly detection?
        Write down the task description, input, expected output, potential challenges you expect
    if you have the appropriate data for the task
        Look for multiple datasets preferably
        if it is supervised task do you have labels?
        If you want to use deep learning do you have enough data?
    Decide your roles in the project
        Divide tasks team work is important
        Roughly each member should contribute for 1/3rd of the load (or whatever your team size is)
    Cleanup, Explore the data
        Remove noise if any
        Check for outliers
        Normalize, feature scaling, binarize see what is necessary
        apply SVD or PCA or TSNE to visuzalize
    Decide which data mining algorithm is suitable?
        Possibly several
        Try a few algorithms you are free to use sklearn or whatever library you prefer
        Possibly ensemble techniques like random forest or adaboost work better
        Possibly a new method, or novel set of features for the same methods
    Experiments
        paramter tuning
        Learning rate, regurlarization parameter, dropout etc
        Depth and width of neural network
        Model specific parameters for CNNs and RNNS or any other type of neural network you are training
        For unsupervised techniques cluster size etc
        compare all the approaches
        document the limitations of all the approaches you try
        Choose the best performing method and do more detailed analysis
        evaluation measures
        Precision, Recall, F1, ROC curve
        Statistical significance test (see the examples here (Lenker til en ekstern side.))
    Report
        At least 4 pages (max 10 pages) in 2 column ACM conference style in latex (Here is the link to the template on overleaf (Lenker til en ekstern side.))
        Writing should be high quality technical writing not copy pasting think of this as a writing practice for your thesis (Refer to this book (Lenker til en ekstern side.) for tips on good writing )
        Describe the task, dataset, methods you use and discuss their limitations you saw in the experiments
        Don't forget to include the github link to your code in the report along with a README.md in github repository which mentions how to reproduce your results in the report.
        Very important: Document who did what and justify you did equal share of the tasks
    Presentation
        5-10 minutes presentation per team
        Discuss the problem, data, interesting findings etc
        In person project presentations are preferred. But you can present over zoom as well. 
    Deadline
        15.05.2022

Topic:
CLEF check that! lab: Identifying Relevant Claims in Tweets (pick 2 or more of subtasks and only English is fine)
    Subtask A: Check-worthiness of tweets: Given a tweet, predict whether it is worth fact-checking. This task is defined with binary labels: Yes and No.. This is a classification task.

    Subtask B: Verifiable factual claims detection: Given a tweet, predict whether it contains a verifiable factual claim. This is a binary task with two labels: Yes and No. This is a classification task

    Subtask C: Harmful tweet detection : Given a tweet, predict whether it is harmful to the society and why. This task is defined with binary labels: Yes and No. This is a classification task.

    Subtask D: Attention-worthy tweet detection: Given a tweet, predict whether it should get the attention of policy makers and why. This task is defined with eight class labels: (i) No, not interesting, (ii) not sure, (iii) Yes, asks question, (iv) Yes, blame authorities, (v) Yes, calls for action, (vi) Yes, classified as in harmful task, (vii) Yes, contains advice, (viii) Yes, discusses action taken, (ix) Yes, discusses cure, and (x) Yes, other. This is a classification task. 
    
    See more info here https://sites.google.com/view/clef2022-checkthat/tasks/task-1-identifying-relevant-claims-in-tweets (Lenker til en ekstern side.)
    data is here https://gitlab.com/checkthat_lab/clef2022-checkthat-lab/clef2022-checkthat-lab/-/tree/main/task1