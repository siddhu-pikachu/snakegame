# SNAKE GAME

>> This game uses mediapipe, which is a model trained by google to recognise the hands and opencv 
>> to recognize your index finger from the identified landmarks on your hand. Let us take the 
>> example of the first solution, Hands. 
>> We feed a stream of images as input which comes out with hand landmarks rendered on the images. Now the 
>> index finger gets selected and we draw the snake using opencv.

## how to play ?!

* A snake 🐍 will then follow your finger around trying to eat the randomely generated donuts 🍩 on the screen overlaying your webcam recording.

* Try to eat as-many-as donuts as the hungry snake can before it gets too large and eats itself 🍽.

* The game gets over when the snake eats itself and the score gets displayed on the screen 📺. 

## Deployment

To deploy this project run

```bash
  py3 main.py
```
