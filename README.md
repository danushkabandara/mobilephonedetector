# mobilephonedetector


I have used the darknet libraray to achieve my detection since it gives much better accuracy than training on the provided images.Therefore you can skip the training phase and go directly to the detector

Here is an example of a successful detection
$ python find_phone.py ./data/37.jpg
0.846096428073 0.658926092043

Here is an unsuccessful detection
$ python find_phone.py ./data/113.jpg
No detection!

