commands for twitter bot @ImageEditBot

|**command**|**type**|**range**|**example**|**result**
|:---:|:---:|:---:|:---:|:---:|
|rotate=value|number|-360 to 360|rotate=45|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnVtnJWXYAA2N8i?format=png&name=240x240)
|crop=x_percentage,y_percentage,width_percentage,height_percentage|number;number;number;number|-|crop=0;0;20;20|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV0WwxWEAAzQOi?format=png&name=120x120)
flip=value|string|v or h|flip=v|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV04KDWMAEmfJk?format=png&name=240x240)
text the_text;x;y;font_size|string;number;number;number|-|text=Hello;200;50;50|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) 
min=value|number|0 - 17 (must be odd number)|min=17|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV10TSWMAEol3j?format=png&name=240x240)
max=value|number|0 - 17 (must be odd number)|max=17|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV2y1sXMAgNr0M?format=png&name=240x240)
median=value|number|0 - 17 (must be odd number)|median=17|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV3Tz4XMAAm-Sz?format=png&name=240x240)
contour=value|boolean|true|contour=true|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV4AloXMAgnSV1?format=png&name=240x240)
enhance=value|boolean|true|enhance=true|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV5MMPXUAAbtVz?format=png&name=240x240)
emboss=value|boolean|true|emboss=true|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV5tU-W8AEt6bo?format=png&name=240x240)
grayscale=value|boolean|true|grayscale=true|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV6QPVXYAUZ0Sd?format=png&name=240x240)
invert=value|boolean|true|invert=true|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV6hTDW8AAVrD3?format=png&name=240x240)
contrast=value|number|-1000 to 1000|contrast=200|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV7AuKXUAAekD9?format=png&name=240x240)
solarize=value|number|-100 to 100|solarize=50|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV7bO9W8AAVN99?format=png&name=240x240)
edges=value|string|true|edges=true|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV8C-xXIAc9JPl?format=png&name=240x240)
repeat=h_count;v_count|number;number|-|repeat=5;3|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV8hilW4AMFxrK?format=png&name=240x240)
resize=width;height|number;number|0 - 8192;0 - 8192 (if the image is too large it may not work)|resize=1000;100|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV86ZIXUAE28yK?format=jpg&name=small)
brightness=value|number|0 - 100|brightness=50|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV9ZoRXEAEK02B?format=png&name=240x240)
blend=alpha|number| 0.0 to 1.0 (target image must be 2 or more and number must be floating point number)|blend=0.5|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV-rGcW8AYaZPM?format=jpg&name=360x360) ![alt text](https://pbs.twimg.com/media/EnV-vm4XEAgLSSM?format=png&name=240x240)
r=expression|number and string (the expression uses https://github.com/danthedeckie/simpleeval)|-|r = 0 if r < 110 else r|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV_7XfWEAI7yGy?format=png&name=240x240)
g=expression|number and string (the expression uses https://github.com/danthedeckie/simpleeval)|-|g = 0 if g < 110 else g|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV_7XfWEAI7yGy?format=png&name=240x240)
b=expression|number and string (the expression uses https://github.com/danthedeckie/simpleeval)|-|b = 0 if b < 110 else b|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnV_7XfWEAI7yGy?format=png&name=240x240)
hue=value|number|-|hue=100|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnWAuN1W4AAyzdX?format=png&name=240x240)
wave=value;value|number;number|-|wave=5;5|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnWBGUkXEAACnUq?format=png&name=240x240)
glitch=value|boolean or number|true or 0 to 80|glitch=true|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnWCR33XMAAMN7t?format=png&name=240x240)

you can also chain command
|**command**|**result**
|:---:|:---:|
rotate=45,grayscale=true,repeat=10;10|![alt text](https://pbs.twimg.com/media/EnV0QUKXUAMj4RB?format=png&name=240x240) ![alt text](https://pbs.twimg.com/media/EnWCq7xW4AEen8B?format=png&name=240x240)
