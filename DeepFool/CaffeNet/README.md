We remove the final softmax layer (deploy_removeSoftmax.prototxt) to craft DeepFool adversarial examples as [The DeepFool project](https://github.com/LTS4/deepfool) suggests and use the original model (deploy_original.prototxt) for predictions.