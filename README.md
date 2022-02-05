# anime-clock-HD
membuat jam yang akurat di hp atau di laptop lu, coba chek aja, jam ini akurat banget padahal cuma pake javascript coibain dehh

using:
<br>HTML, CSS</br>

penggunaan:
<br>seperti jam pada umumnya</br>

## editing

### 1. background
disini gw pake background foto dan lu bisa ganti pake foto lu dengan mengganti di bagian
```html
body {
    background: url(./img/background.jpg);
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 90vh;
    overflow: hidden;
}
```


### 1. clock color
di bagian jamnya gw pake color line gradient, dan lu bisa ganti warnanya sesuka lu di bagian
```html
.clock {
    width: 300px;
    height: 300px;
    background: linear-gradient(to right, #2b428d, #325de9);
    border-radius: 50%;
    box-shadow: 20px 30px 20px rgba(0,0,0,0.3);
    position: relative;
}
```

mau milih warna yang cocok dan keren, lu bisa ke https://colorhunt.co/
