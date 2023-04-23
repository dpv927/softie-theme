<div class="logo" align="center">
  <img src="../resources/images/logout.png" width="150">
</div>

<h1 class="title" align="center">
  Softie Colour Theme for Alacritty
  <br>
</h1>

<div class="description" align="center">
  <p>A dark and soft theme designed to maintain the health of your eyes while using Alacritty.</p>
</div>
<br>

<div class="preview" align="center">
<!-- La capura de pantalla va aqui -->
</div>

## Install
The colorscheme is stored at the `softie.yml`. You need to import the code from that file to the directory where the `alacritty.yml` file is located. First, download the softie.yml file and then type this command:

```bash
wget https://github.com/dpv927/softie-theme/blob/main/alacritty/softie.yml
cp -r softie.yml ~/.config/alacritty 
```

Then, at the start the `alacritty.yml`, add the next line:
```yml
import:
  - softie.yml
```

## License

This project is under the [MIT license](LICENSE).
