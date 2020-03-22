# Testing Catboost on the titanic dataset
I've heard that catboost was doing quite well on various benchmarks and that it came with built-in mechanisms to process categorical and text variables. I wanted to put it to the test.

Many of the other algorithms I've used (e.g. logistic regression, but even xgboost, my current go-to) require quite some preprocessing and a fair bit of data exploration. What I find very interesting here is that we could speed up the work greatly and get at least comparable results, if not same / better according to certain benchmarks. There can be a lot of value there, as time saved can be used to do other projects, or have a fast prototype / first version and trigger continuous improvement. Having a first working version has proved to be key in my experience, as it gives all stakeholders of a project an idea of the kind of output they will get, leading to a faster overall project integration as services interacting with the model can be built with real data, and the project can fail fast if it seems overall it won't work. 

# On Kaggle
https://www.kaggle.com/gtregoat/testing-catboost-on-the-titanic-dataset

