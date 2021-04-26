---
name: Feature Request 💡
about: Suggest a new idea for the project.
labels: enhancement, feature-request
---

<!--
Please search your feature on previous issues and our feature requests consolidation hub (https://github.com/microsoft/LightGBM/issues/2302) before you open a new one.
-->

## Summary

Saving and loading LightGBM model to binary stream or file like text.

## Motivation

Some analytical or predictive models are stored in binary format so that user cannot see the way model is implemented. It can be usefult also when user is layman. Other benefit can be model cannot be easily tampered. In that case two unnecessary steps of saving to text and then create blob out of it while saving and read blob and convert it to text for loading to library. This can lower the performance so can this be considered as new feature to implement?

Thanks,
Kiran

## Description
This was already implemented at below link so would be easy to implement it in master as an additional API to provide better flexxibility:
https://github.com/wxchan/LightGBM/blob/1e6091c01f75cbbc86b55b104ae3231d302a0a9f/src/proto/gbdt_model_proto.cpp

## References
As an reference this machine learning model is save and loaded from Binary format.
https://machinelearningmastery.com/save-load-machine-learning-models-python-scikit-learn/
