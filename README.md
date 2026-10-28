# UoH Lab Experiments — Electronics Experiment Simulator

An interactive electronics laboratory simulator for the University of Hyderabad (UoH), M.Sc. Physics.

**Author:** Aryan Sarkar · 26PHMP54

## Run locally

Requires Python 3. From this folder, run:

```bash
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

- Windows: double-click `start-windows.bat`.
- macOS/Linux: run `./start-mac-linux.sh` in a terminal.
- You can also open `index.html` directly in a browser.

Google Fonts may need an internet connection; system fonts are used as a fallback.

## Publish with GitHub Pages

1. Upload `index.html` and `README.md` to the root of your repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose branch **main** and folder **/(root)**, then save.
5. After GitHub finishes deployment, the site should be available at:
   https://aryansarkar19.github.io/UOH-ELECTRONICS-EXPERIMENT-SIMULATOR/
