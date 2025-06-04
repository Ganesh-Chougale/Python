how to create a Python virtual environment in **CMD**, **PowerShell**, and **Bash**.

---

### 1. **CMD (Windows Command Prompt)**

```cmd
python -m venv myenv
myenv\Scripts\activate
```

* Creates `myenv` folder with env.
* Activates it (you’ll see `(myenv)` prefix).

---

### 2. **PowerShell**

```powershell
python -m venv myenv
.\myenv\Scripts\Activate.ps1
```

* Same creation command.
* Activation uses `Activate.ps1`.
* If blocked by policy, run:
  `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass`

---

### 3. **Bash (Linux/macOS or Windows WSL)**

```bash
python3 -m venv myenv
source myenv/bin/activate
```

* Create with `python3` (some systems use `python`).
* Activate with `source`.

---

### To deactivate (all environments):

```bash
deactivate
```