# GSIC

GSIC 🚀

## Setup

Clone the repository, then create a virtual environment in the cloned folder.
Each contributor creates their own environment; `.venv` is ignored by Git.

### Windows PowerShell

```powershell
git clone https://github.com/Faaris-Kaber/GSIC.git
cd GSIC
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

### Linux, WSL, or macOS

```bash
git clone https://github.com/Faaris-Kaber/GSIC.git
cd GSIC
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

When finished, run `deactivate`. Add shared Python dependencies to
`requirements.txt` so other contributors can install them.
