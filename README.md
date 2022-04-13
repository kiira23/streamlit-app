# Streamlit 

[Streamlit](https://streamlit.io) turns data scripts into shareable web apps in minutes. 
All in pure Python. No front‑end experience required.

![](https://s3-us-west-2.amazonaws.com/assets.streamlit.io/videos/hero-video.mp4)

A [Streamlit demo](https://streamlit.io/gallery) to interactively visualize Uber pickups in New York City:

![](img/uber.png)


## Setup

First, we need to ensure you have a recent version of **Anaconda** installed: 

- If you don't have Anaconda, follow this [Anaconda installation tutorial](https://kirenz.github.io/codelabs/codelabs/anaconda-install/#0). 

- If you already have Anaconda, we update it: On *Windows* open the Start menu and open an Anaconda Command Prompt. On *macOS* or *Linux* open a terminal window:

```bash
conda update --all
```

In your terminal: 

- `cd` into a folder you want to install this repo:

```bash
cd your-path
```


- Clone the repository containing all code:

```bash
git clone https://github.com/kirenz/streamlit-app
```

- cd into the streamlit-app folder

```bash
cd streamlit-app
```

- Now we install all needed Python libraries from the `environment.yml` file to create a virtual environment named `streamlit`:

```bash
conda env create -f environment.yml
```

- Activate the `streamlit` environment:

```bash
conda activate streamlit
```

- Test if your installation was succesful (this will open a demo):

```bash
streamlit hello
```
- Stop your app with `Ctrl+C`

- cd into 0-first-app

```bash
cd 0-first-app
```

- Start the app:‚

```bash
streamlit run app.py
```

## Guides

- Get familiar with the [main concepts](https://docs.streamlit.io/library/get-started/main-concepts)
 
- [API reference](https://docs.streamlit.io/library/api-reference)

- [Cheat Sheet](https://docs.streamlit.io/library/cheatsheet)