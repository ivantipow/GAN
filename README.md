# Generative adversarial network (GAN)

![low](https://user-images.githubusercontent.com/82726279/149596718-29ebffbf-9c10-4eb5-9706-4b59fca5d3aa.gif)

В этом репозитории мы имплеминтируем GAN, научим его генерировать лица людей и посмотрим на то, как можно оценивать качество генерации.

---------

## Содержание
- [`GAN.ipynb`](https://github.com/ivantipow/GAN/blob/main/GAN.ipynb) - блокнот, в котором на PyTorch'е имплеминтируем GAN и обучаем его генерировать лица людей. Строим leave-one-out оценку качества работы на основе 1NN Classifier. А также сравниваем распределения настоящих и сгенерированных изображений, используя t-SNE.

- [`evolution_compress.gif`](https://github.com/ivantipow/GAN/blob/main/evolution_compress.gif) - анимация, которая показывает, как менялись генерируемые GAN'ом изображения при его обучении на 1000 эпохах.

- [`evolution_v0_compress.gif`](https://github.com/ivantipow/GAN/blob/main/evolution_v0_compress.gif) - аналогично для 1251 эпохи.

- [`GAN_architecture.png`](https://github.com/ivantipow/GAN/blob/main/GAN_architecture.png) - схематический рисунок, описывающий работу GAN'а.


## Дополнительные ссылки
- Данный репозиторий выполнен в рамках обучения в [Deep Learning School](https://www.dlschool.org/).
- Отличный [туториал по GAN'ам](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html) с примерами кода на PyTorch.
- Goodfellow, Ian, et al. "[Generative adversarial nets.](https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf)" Advances in neural information processing systems 27 (2014).
- Radford, Alec, Luke Metz, and Soumith Chintala. "[Unsupervised representation learning with deep convolutional generative adversarial networks.](https://arxiv.org/pdf/1511.06434.pdf)" arXiv preprint arXiv:1511.06434 (2015).
- [Tips and tricks to make GANs work](https://github.com/soumith/ganhacks).
