# Digital-Modulation-Recognition
Digital Modulation Recognition using Machine Learning

An ideal detection scheme should be fast, accurate, and
efficient. Cyclostationary feature detection is a detection scheme that
satisfies all these criteria. The method also possesses the ability to
distinguish between noise and the primary user signal. One major
advantage of the cyclostationary feature detection method is that in
addition to identifying the primary user signal, it also identifies the
modulation scheme used by the primary user. This project investigates
the cyclostationary feature detection method under different
modulation schemes. In this project, cooperative spectrum sensing is
performed, which involves cooperation among various cognitive relay
nodes. Cooperative spectrum sensing is thus found to be an effective
technique to improve the detection performance by exploring the
spatial diversity of various relay nodes.

The dataset which is used herer is RADIOML 2016.10A (https://www.deepsig.io/datasets)

Our baseline method leverages the list of higher-order features and
other aggregate signal behavior statistics. Here we can compute each of
these statistics over each of the keys present, and translate the
example into feature space, a set of real values associated with each
statistic for the example. For making the classification task much
simpler but also discarding the vast majority of the data. We use an
ensemble model of Decision Tree to classify modulations from these
features, which outperforms a single support vector machine (SVM)
significantly on the task.
