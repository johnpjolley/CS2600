[Back to README.md](./blob/master/README.md)

(./blob/master/SkyBackground.png)

(https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjlpuzTgZjdAhUN1qwKHaTfD-4QjRx6BAgBEAU&url=https%3A%2F%2Fwww.ucityschools.org%2FPage%2F1006&psig=AOvVaw3HWJKC1Gd88M6LtOSR_Sfx&ust=1535829702517387)

```Javascript
var jsonObject = JSON.parse(stringified);
    jsonObject = jsonObject.split('"":""').join('"Where":"Home"');
    jsonObject = jsonObject.split('"":"@"').join('"Where":"Away"');
    jsonObject = jsonObject.split('"":').join('"Result":');
```
