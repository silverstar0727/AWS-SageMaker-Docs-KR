# AWS-SageMaker-Docs(TF)


본 문서는 [AWS SageMaker의 official document](https://sagemaker.readthedocs.io/en/stable/frameworks/tensorflow/using_tf.html#train-a-model-with-tensorflow)를 토대로 작성되었습니다.

- - -

## Contents

#### Train a Model with TensorFlow
* [Prepare a Training Script](https://github.com/silverstar0727/silverstar0727.github.io/blob/main/_posts/sagemaker/2020-12-26-SageMaker_01.md)(완)
  * Adapting your local TensorFlow script
  * Use third-party libraries
* [Create an Estimator](https://github.com/silverstar0727/silverstar0727.github.io/blob/main/_posts/sagemaker/2020-12-27-SageMaker_02.md) (완)
  * Specify a Docker image using an Estimator
* [Call the fit Method](https://github.com/silverstar0727/silverstar0727.github.io/blob/main/_posts/sagemaker/2020-12-28-SageMaker_03.md) (완)
* [Distributed Training](https://github.com/silverstar0727/silverstar0727.github.io/blob/main/_posts/sagemaker/2020-12-29-SageMaker_04.md) ()
  * Training with parameter servers
  * Training with Horovod
* Training with Pipe Mode using PipeModeDataset
* Training with MKL-DNN disabled

#### Deploy TensorFlow Serving models
* Deploy to a SageMaker Endpoint
  * Deploying from an Estimator
    * What happens when deploy is called
  * Deploying directly from model artifacts
  * Making predictions against a SageMaker Endpoint
* Run a Batch Transform Job
  * Create a Transformer Object
  * Call transform
  * Batch Transform Supported Data Formats
* TensorFlow Serving Input and Output
  * Supported Formats
    * Simplified JSON Input
    * Line-delimited JSON
  * Create Python Scripts for Custom Input and Output Formats
    * How to implement the pre- and/or post-processing handler(s)
    
#### SageMaker TensorFlow Classes

#### SageMaker TensorFlow Docker containers

- - -
