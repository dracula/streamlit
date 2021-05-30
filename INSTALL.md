### [Steamlit](https://streamlit.io/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/streamlit.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/streamlit/archive/master.zip) option and unzip them.

#### Activating theme

Streamlit's team has created a short video on custom theming [here](https://www.youtube.com/watch?v=Mz12mlwzbVU). For this guide, we'll apply the theme to the global config file:

1. Themes are held in a `config.toml` file
    - For macOS/Linux users, the global config file is located at `~/.streamlit/config.toml`
    - For Windows users, the global config file is located at `%userprofile%/.streamlit/config.toml`
2. If this file does not exist, copy the file from `src/config.toml` into the directory `.streamlit`. If this file does exist, copy the contents of `src/config.toml` into the existing file and save
3. Run your Streamlit app for the theme to be applied
    - If it does not apply automatically, you can activate it by clicking the hamburger icon in the top-right of your Streamlit app > **Settings** > **Theme** > **Custom Theme**