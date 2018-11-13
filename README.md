# grail

This is a simple tool to be used for managing and maintaining shared site-wide [conda](https://github.com/conda/conda) environments
in a stable and consistent manner, allowing one to keep up with system user requirements.

This is originally being written for use on shared use research computing clusters, so we may more
efficiently manage the various package dependencies our Python users, particularly those working on
Deep Learning, have.  One of our main concerns is being able to keep our package versions up to date,
without breaking the workflows of other users who may have specific version dependencies.
