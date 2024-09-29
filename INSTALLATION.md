## Installation

To use `aibo`, both the Python server and the Elisp package need to be installed. Here's how:

1. Clone the `aibo` repository:
```sh
git clone https://github.com/dmed256/aibo.git
```

2. Install Python dependencies:

2.1. Install using `pip`
```sh
pip install aibo-server
```

2.2. Install using the cloned git repo
```sh
cd aibo/python
pip install -e .[dev]
```

3. Update your Emacs configuration file (`~/.emacs` or `~/.emacs.d/init.el`):
```elisp
(add-to-list 'load-path "/path/to/aibo")
(require 'aibo)
```

4. Make sure your `OPENAI_API_KEY` environment variable is set

5. Restart or eval the Elisp code snippet.

Optional keybindings and Ivy buffer configurations are de
