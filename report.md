# 2022DM-Lab2 Report

Here are the main tools I used in these Lab:

    1. HuggingFace
    2. Transformers
    3. Bert
    4. pandas
    5. numpy

I start from Data Preprocessing, the raw file is in JSON format, I load it with pandas, then transform to .csv file after drop some useless columns. After finish the preprocessing, I start to build my model with HuggingFace and Transformers.

When building my model, I meet many many problems, these problems teach me a lot, the biggest problem I met is my model can't converge, and these problem cost lot of time, I talk with my labmate and they can't find the problem too, even I change to a new conda env, it still have high loss when training, at the end, I borrow my labmate's server and do preprocessing again, build model again, finally get the result.

Here's the method I tried when model can't converge:

    1. change compute_metrics
    2. change another random seed
    3. rebuild my model with other pre-trained model
    4. change another conda vurtual environment
    5. borrow labmate's server and run my code
    6. discuss with labmate all day long...
    7. do preprocessing again even with same way...
    8. pray
