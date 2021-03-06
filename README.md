# Mobile Phone Detector
## What it does
Detects mobile phone in an image and reports the location within the image using normalized x y coordinates
![X and Y coordinates of mobile phone](https://github.com/danushkabandara/mobilephonedetector/blob/master/Capture.PNG)

## Getting started
Download the repository and run find_phone.py file. Install any prerequisites it asks for. I have included the compiles darknet library which might not work on your machine. In that case you should make your own libdarknet.so using the darnet repository.


I have used the darknet libraray to achieve object detection since it gives much better accuracy than training on the provided images in the data folder.

Here is an example of a successful detection
```
$ python find_phone.py ./data/37.jpg
0.846096428073 0.658926092043
```

Here is an unsuccessful detection
```
$ python find_phone.py ./data/113.jpg
No detection!
```

## Built with
[DarkNet](https://pjreddie.com/darknet/)

## Authors

* **Danushka Bandara**

## License

Licensed under MIT License

## Acknowledgements
@pjreddie for the awesome darknet repo
