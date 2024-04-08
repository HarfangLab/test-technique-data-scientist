# Data Scientist / Technical Case

👋 Welcome! Here's everything you need to work on the Data Scientist technical case which is part of HarfangLab's recruitement process.

## Overview

### About the interview

The technical case is primarily a discussion support for the onsite technical interview. The topics are intentionally dense, especially considering that the preparation period may be very short. The goal isn't to cover everything exhaustively but to provide an overall understanding and let you develop the areas of work you wish. We will ask you at the beginning of the interview how much time you were able to dedicate to this preparation.

The technical case is split into two parts: a technical subject and a case study subject.

### The technical subject

We want to see code. It's important that this code can be executed. This allows us to observe your habits and understand your thought process.

ℹ️ Instead of doing the technical subject, you can share some relevant code you're proud of that you have done on a previous project.

You can submit your answers in the way that suits you best:
* By making a new private github repository and adding [HugoMichard](https://github.com/HugoMichard) and [goncalogiga](https://github.com/goncalogiga) as contributors (preferred)
* By sending a ZIP file with your code
* ...Or any other method you prefer!

⚠️ If you choose to share your answers using a github repository, don't forget to make it private !

#### Exercise

You have an archive containing both malicious and legitimate binary files. The password is `infected`. You also have a Jupyter notebook to get started, with the necessary libraries listed in `requirements.txt`.

Can you build a binary classification model for these files?

#### Data

**The malicious files contain their active payload. Be careful, never execute them**. For additional safety, you should work on executable files that are **not compatible** with your OS.

⚠️ If your laptop is on `Linux` or `Mac`, please use the playground in `technical-subject/windows` and download the files from [here](https://drive.google.com/file/d/1WP3pzeSK4P177uKwuBWuogYzloqAiG51/view?usp=drive_link)

⚠️ If your laptop is on `Windows`, please use the playground in `technical-subject/linux` and download the files from [here](https://drive.google.com/file/d/1B7257GjyYldK1Scd8CKEfFDWO6tRiF7d/view?usp=drive_link)

### The case study subject

We propose several topics for the case study. We ask you to prepare at least one. You are free to make any assumptions you deem relevant.

ℹ️ You do not need to code anything on this subject, we only want to know how you would tackle the topic you choose.

#### Abnormal connections

Suppose there is a computer network consisting of multiple computers. Multiple users can connect to the same machine. The goal is to determine, for each connection to each machine, whether it is abnormal. To assist you in your analysis, you can consider only Windows machines and assume that you have access to all the information available on each machine in real-time.

#### File similarity

Suppose you have access to a dataset of `N` malicious binary files (similar to the ones given in the technical subject). For each of these files, you have a similarity label to the `N-1` other files (1 if the files are similar, 0 if they differ sufficiently). Given a new file, the goal is to determine the similar files in the dataset.

#### Hunting LLM

Suppose you have an API with different endpoints enabling you to fetch information on security alerts, computers and events happening on these computers on your computer park. The goal is to build an expert LLM that can interact with the API to assist cyber analysts hunt threats. It should identify the information needed in a threat investigation and help the analysts interpret the data.
