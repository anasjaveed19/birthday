## Shahroz Ghaffar Birthday

> <b>Modify the configuration in `config.js` to create a super creative webpage for your loved one's birthday. If you like it, please fork or star it~</b>

<img src="https://github.com/AJLoveChina/loveBalloon/blob/master/static/github-star.png" />

## TODO
* [x] Each line of blessing text can be matched with a picture
* [ ] Support image rotation

### `config.js` Instructions
> Friendly reminder: Every sentence, every image address, and every button text line must end with an **English comma**!
```text
var config = {
    // The length of the sentences can be arbitrary. You can write ten, twenty, or more sentences.
    // Try to keep each sentence under 15 characters, otherwise, the display effect might not be good.
    texts: [
        "For my amazing friend,",
        "Shahroz Ghaffar!",
        "Today is your special day!",
        // ... (and so on)
    ],
    /**
     * imgs can be left blank, but if you want to fill it in, you must follow the format below
     * "Corresponding text above, must be exactly the same" : "Image address, images can be placed in the imgs folder"
     * For example
     * "Shahroz Ghaffar!": "./imgs/shahroz.jpg"
     *
     * If you don't want pictures, just write two slashes at the beginning of each line to comment it out.
     * Tip: It's best to use square or near-square pictures for a better look.
     */
    imgs: {
        // "Shahroz Ghaffar!": "./imgs/your-image.png",
    },
    // Button text descriptions. The following are the default button texts (in English), you can change them to your liking.
    desc: {
        turn_on: "Start",
        play: "Music",
        bannar_coming: "Colors",
        balloons_flying: "Something's missing",
        cake_fadein: "Cake?",
        light_candle: "Candle?",
        wish_message: "Happy Birthday",
        story: "A MESSAGE FOR YOU",
    }
};