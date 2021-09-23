Repro for https://github.com/microsoft/vscode/issues/132483#issuecomment-925383193.

Run:

```
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```

Open the repo in VS Code Insiders, then check the "Python Language Server" output; it should be looping.
