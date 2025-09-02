# blog
```
wget https://quarto.org/download/latest/quarto-linux-amd64.deb
sudo apt install ./quarto-linux-amd64.deb

python3 -m pip install jupyter matplotlib plotly

# Preview
quarto preview /workspaces/blog/hello.qmd --no-browser --no-watch-inputs

# Render to docs, then push to main to deploy
quarto render

```