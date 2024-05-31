# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Testing object detection (yolo, mobilenet, etc.) with picamera2 on Pi 5
 - [https://www.jeffgeerling.com/blog/2024/testing-object-detection-yolo-mobilenet-etc-picamera2-on-pi-5](https://www.jeffgeerling.com/blog/2024/testing-object-detection-yolo-mobilenet-etc-picamera2-on-pi-5)
 - RSS feed: https://www.jeffgeerling.com/blog.xml
 - date published: 2024-05-30T20:42:13+00:00

<span class="field field--name-title field--type-string field--label-hidden">Testing object detection (yolo, mobilenet, etc.) with picamera2 on Pi 5</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>Besides the Pi 5 being approximately 2.5x faster for general compute, the addition of other blocks of the Arm architecture in the Pi 5's upgrade to A76 cores promises to speed up other tasks, too.</p>

<p><img alt="Jeff Geerling person object detection on Pi 5" class="insert-image" height="auto" src="https://www.jeffgeerling.com/sites/default/files/images/jeff-geerling-object-detection-person-raspberry-pi-5.jpeg" width="700" /></p>

<p>On the Pi 4, popular image processing models for object detection, pose detection, etc. would top out at 2-5 fps using the built-in CPU. Accessories like the <a href="https://coral.ai">Google Coral TPU</a> speed things up considerably (and are eminently useful in b

