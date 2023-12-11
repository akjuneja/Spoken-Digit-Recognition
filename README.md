# Spoken-Digit-Recognition
Speaker-Independent Spoken Digit Recognition (xSDR)

In this project, we focus on developing a SDR system in a speaker-independent setting. That is,
the speakers in the evaluation set are disjoint from the training set speakers. We do so because
we expect real-world ASR systems to generalize to different speakers than those we have data
for. Moreover, for many languages that are under-resourced, we have have (limited) annotated
speech data from a single speaker, but we would still want the system to be deployed to work
on any speaker of that language. We tackle the problem of spoken digit recognition as a
sequence classification task. Concretely, the inputs are short audio clips of a specific digit (in the
range 0-9), then the goal is to build deep neural network models to classify a short audio clip
and predict the digit that was spoken.
