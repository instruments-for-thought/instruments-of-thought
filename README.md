# Instruments-of-Thought
A Machine that thinks.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What instruments of thought do you suggest, machine?" \
  | uvx instruments-of-thought \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install instruments-of-thought
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
instruments-of-thought -a multilogue.txt
```
Or:
```bash
instruments-of-thought multilogue.txt > response.txt
```
Or:
```bash
instruments-of-thought -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import instruments_of_thought
```
