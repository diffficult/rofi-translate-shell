# rofi-translate-shell
Use rofi to quickly translate a word or phrase to clipboard

## Required:

- `rofi`, 

- `translate-shell` of course. Use your favourite package manager to get it,

- `xclip` to get translated result into clipboard when pressing enter,

- `nerd fonts` or `font-awesome` to get icons properly displayed.

### Install: 

Clone repo with 

```
git clone https://www.github.com/diffficult/rofi-translate-shell 
``` 

### Usage:

Call the script and `rofi` will prompt you for the word or phrase you want to translate. Once you enter that, it will ask you for the language code (`en`, `es`, `ja`, `ru`, etc) you want to translate that to. Then it will display the translation, meaning, phonetic and similar or synonyms to your query. If you press **Enter ↵** it will put that result in your clipboard and push a notification confirming that.

The script will use the `.cache` directory to store most recent queries, last used language codes and also the latest results, in which case you can select instead of typing again and translate the same phrase to a different language. 

I suggest you clone the repo wherever you like and link the script to your `.local/bin` directory or wherever you keep your personal scripts. 

----
Π
