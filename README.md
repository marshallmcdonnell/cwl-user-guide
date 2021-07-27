# Common Workflow Langauge User Guide

This holds my work for going through the
[Common Workflow Language User Guide](https://www.commonwl.org/user_guide).

## Setup `cwltool`

To run the workflows created using CWL,
I used the reference implementation tool,
[`cwltool`](https://github.com/common-workflow-language/cwltool)

To install, I create a virtual environment and install inside that:
```
python3 -m venv env
source env/bin/activate
pip install --upgrade pip
pip install cwltool
cwltool --version
```
