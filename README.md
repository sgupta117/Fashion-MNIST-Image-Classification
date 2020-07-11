# Fashion-MNIST

<details><summary>Table of Contents</summary><p>

* [Why we made Fashion-MNIST](#why-we-made-fashion-mnist)
* [Get the Data](#get-the-data)
* [Usage](#usage)
* [Benchmark](#benchmark)
* [Visualization](#visualization)
* [Contributing](#contributing)
* [Contact](#contact)
* [Citing Fashion-MNIST](#citing-fashion-mnist)
* [License](#license)
</p></details><p></p>


`Fashion-MNIST` is a dataset of [Zalando](https://jobs.zalando.com/tech/)'s article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend `Fashion-MNIST` to serve as a direct **drop-in replacement** for the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/) for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

Here's an example how the data looks (*each class takes three-rows*):

![](doc/img/fashion-mnist-sprite.png)

<img src="doc/img/embedding.gif" width="100%">

### Labels
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

