# UI Background Blur
## How it works

1. Apply Blur Effect: The base layer has a blur effect applied to it.
2. Take Snapshot: A snapshot of the blurred base layer is taken and rendered into a sprite called bg. The bg sprite has the same size as the camera.
3. Disable Blur Effect: The blur effect is disabled on the base layer.
4. Mask with NewSprite3: The bg sprite is then masked with NewSprite3.

## Static blur
Instead of repeating the above multiple times, its done once.
![image](https://github.com/user-attachments/assets/b73cb922-16d9-473a-8b18-4f1f452f12e0)

## Dynamic blur
Repeates the steps every 0.055 seconds, which is 18 frames per second.
It can be executed every frame.
![image](https://github.com/user-attachments/assets/d6839355-9d04-4f37-bae2-5c7a884aff37)

