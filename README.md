# Talks
Batteries Incldued: Slides, Code, Data, and Instructions

# About
Using Spark, Python, and Parquet for Loading Large Datasets

# Level
Intermediate

# Abstract
Have you been in the situation where you’re about to start a new project and ask yourself, what’s the right tool for the job here? I’ve been in that situation many times and thought it might be useful to share with you a recent project we did and why we selected Spark, Python, and Parquet. My plan is take you through a use case that involves loading, transforming, aggregating, and persisting the dataset. We’ll use an open dataset consisting of full fund holdings graciously provided by Morningstar. My goal in presenting this use case are to have the audience learn about how these technologies can be applied to a real world problem and to inspire members of the audience to start learning these technologies and applying them to their own projects.

# Bio
I’m a founder of a company that’s focused on financial analytics with a vision to make systematic investors (quants) lives easier by making their data preparation/aggregation process vendor agnostic, writes/reads fast for exploratory analysis through to alpha generation, and making sure the underlying data tech stack is agile and reliable. I’ve worked directly with over 24 financial companies over the past 10 years and this has allowed me to see a lot of the tradeoffs made with off-the-shelf and homegrown solutions to address data related problems. My typical toolkit consists of Python, R, Spark, HIVE, Cassandra, TitanDB, MongoDB, and Matplotlib, what can I say I love the challenge of finding solutions for data-driven analytic problems. Oh and I am a CrossFit addict so don’t get me started there...


# PoC Steps
1. Follow these instructions http://goo.gl/cAEQtD to create a Hadoop cluster with Spark, Parquet, and Python
2. Run the code in TalkDemo_HadoopHivePySpark.txt to load in the test dataset and create your base tables
3. Fire up PySpark in Jupyter and step through each line of Spark code with your test dataset
4. Peruse the slides https://goo.gl/Bk8FFV and connect the dots for the bigger picture
5. Hit me with any questions @dougeisenstein on Twitter