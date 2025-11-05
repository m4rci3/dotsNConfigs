<div>
  <p align=center style="font-size:24px;">【Preview】</p>
  <img src="./Images/Tmux preview image.png" width="890" height="880">
</div>
<div style= "font-size:18px">

  <h4>This configuration includes:</h4>
The little modules shown above (battery, runtime, cpu utilization, and their colors) as well as specific keybindings; the prefix key is set to `ctrl + \` so as to not interfere with terminal emulator keybindings like `ctrl + a ` to jump to the beginning of a line.
<h4>Getting Started</h4>
  After placing this <a href="./.tmux.conf">Tmux configuration file from this repository </a>in your `~/.tmux.conf`, you must reload Tmux by either restarting or reloading with:

  ```bash
  tmux source ~/.tmux.conf
  ```

  Next you need to use `prefix` + `I` to "fetch" / initialize the plugin(s) that are apart of this configuration. Then you should be good to go. 
</div>
<footer>
  <p>References/Sources:</p>
  <ul>
    <li><a href="https://github.com/tmux-plugins/tpm">Tmux Plugin Manager (TPM)</a><br></li>
    <li><a href="https://github.com/catppuccin/tmux">Catppuccin for Tmux</a></li>
  </ul>
</footer>
