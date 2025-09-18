# W98 Clock+Weather

## Weather Configuration

Edit those lines in index.html to set your location:

```
            const latitude = '0.0';
            const longitude = '0.0';
```

## Disable CRT

To disable CRT, remove/comment out this line

```
<link rel="stylesheet" href="../assets/crt.css" />
```

## Rescale Windows

Those windows are very big, because they're meant to be displayed on a 480x320 screen with CRT filter ON. So if it's too big (or too small) to you, edit this CSS to set a custom scaling.

Default is 2.5.

```
.window {
    transform: scale(2.5);
}
```

After rescaling, the windows may move, so you can also adjust the position of `.clock` and `.weather`.