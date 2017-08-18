# stackoverflow
StackOverFlow Project on Spark

The overall goal of this project is to implement a distributed k-means algorithm which clusters posts on the popular question-answer platform StackOverflow according to their score. Moreover, this clustering should be executed in parallel for different programming languages, and the results should be compared.

The motivation is as follows: StackOverflow is an important source of documentation. However, different user-provided answers may have very different ratings (based on user votes) based on their perceived value. Therefore, we would like to look at the distribution of questions and their answers. For example, how many highly-rated answers do StackOverflow users post, and how high are their scores? Are there big differences between higher-rated answers and lower-rated ones?

Finally, we are interested in comparing these distributions for different programming language communities. Differences in distributions could reflect differences in the availability of documentation. For example, StackOverflow could have better documentation for a certain library than that library's API documentation. However, to avoid invalid conclusions we will focus on the well-defined problem of clustering answers according to their scores.

For this project, you also need to download the [data](http://alaska.epfl.ch/~dockermoocs/bigdata/stackoverflow.csv) (170 MB):
and place it in the folder: 𝚜𝚛𝚌/𝚖𝚊𝚒𝚗/𝚛𝚎𝚜𝚘𝚞𝚛𝚌𝚎𝚜/𝚜𝚝𝚊𝚌𝚔𝚘𝚟𝚎𝚛𝚏𝚕𝚘𝚠 in the project directory.
