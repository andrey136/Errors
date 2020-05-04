# Git
## How to switch from **vim** to **nano**

Solution:
* nano -->	$ git config --global core.editor "nano -w"

Other examples of setting default editors on other OSs:
* Atom -->	$ git config --global core.editor "atom --wait"
* Text Wrangler -->	$ git config --global core.editor "edit -w"
* Sublime Text (Mac) -->	$ git config --global core.editor "subl -n -w"
* Sublime Text (Win, 32-bit install) -->	$ git config --global core.editor "'c:/program files (x86)/* sublime text 3/sublime_text.exe' -w"
* Sublime Text (Win, 64-bit install) -->	$ git config --global core.editor "'c:/program files/sublime text 3/sublime_text.exe' -w"
* Notepad++ (Win) -->	$ git config --global core.editor "'c:/program files (x86)/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
* Kate (Linux) -->	$ git config --global core.editor "kate"
* Gedit (Linux) -->	$ git config --global core.editor "gedit -s -w"
* VS Code -->	$ git config --global core.editor "code --wait"
* emacs -->	$ git config --global core.editor "emacs"
* vim -->	$ git config --global core.editor "vim"

[source gist.github](https://gist.github.com/iamcodder/eed3b9d8164e1c23d26d6be66d12a064)
