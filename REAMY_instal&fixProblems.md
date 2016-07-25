# UBX
Joystick Android/IOS Unity

                           !If not work, readmy! ...YOUR FREE TO USE IT... !Read me for instalation tutorial!

For more informations and questions send an mail to:
unbionix@gmail.com



Take a lock: https://youtu.be/Vtpcln2PLOQ





Simple Instalation:
Drag the player prefab in side of the Player folder to the Scene
Drag the VirtualJoystick prefab in side of the Canvas folder to the Scene


Manual instalation:
Create an UI Canvas and call it "VirtualJoystic"; VERY IMPORTANTE TO HAVE THIS NAME
In that canvas, create an Image and call it "Background_Joystic_Move", and drag the "VirtualJoystic.cs" script in side of tham.
In that image, that means in side of that Image, create another Image call "Joystic_Look_Image"
On the player GameObject "if you dont have, create a simple 3D esfere"  and drag the "Player_Script.cs" script in tham.
                                                      AND HAVE FUN






PROBLEMS FIX:
Simple instalation problem usual problem is the script is not find, in that case, do:
Try to remove the "Player_Script" from the "Player" gameObject and drag the "Player_Script.cs" to whim.
Try to remove the "VirtualJoystic" from the "Background_Joystic_Move" image in side of the "VirtualJoystic" canvas and drag the "VistualJoystic.cs" script to the "Background_Joystic_Move" Image.

If not working or have an error on joystick, like the central image disappear and are giving an error, try to change the Public variable "Joystick Distance from Background" in the Image "Background_Joystic_Move" on the canvas call "VirtualJoystick"   to an number. We suggest  the number "2".


