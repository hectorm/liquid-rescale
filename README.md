# liquid-rescale

A shell script to achieve a similar effect to [content-aware scaling](https://helpx.adobe.com/photoshop/using/content-aware-scaling.html) with [ImageMagick](https://imagemagick.org).

![Preview](./lena.gif)

## Installation

```sh
sudo curl -o '/usr/local/bin/liquid-rescale' 'https://raw.githubusercontent.com/hectorm/liquid-rescale/master/liquid-rescale'
sudo chown root:root /usr/local/bin/liquid-rescale
sudo chmod 755 /usr/local/bin/liquid-rescale
```

## Usage

```sh
liquid-rescale input.jpg [output.gif] [256x256]
```
