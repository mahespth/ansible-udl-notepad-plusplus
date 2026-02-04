# Notepad++ UDL: Ansible Job Output

Author: **Steve Maher, AIXTreme Research Ltd**

A Notepad++ **User Defined Language (UDL)** to highlight plain-text (no-colour) Ansible / AAP job output.

---

## Files

- `src/AnsibleJobOutput_UDL.xml` — the UDL import file for Notepad++
- `README.md` — this installation guide

---

## Install (Import the UDL)

1. Download or clone this repo.
2. Open Notepad++.
3. Go to: **Language → User Defined Language → Define your language…**
4. Click **Import…**
5. Select `AnsibleJobOutput_UDL.xml`
6. (Recommended) Restart Notepad++.

After importing, you should see it under:

**Language → Ansible Job Output**

---

## Optional: Auto-apply to file extensions

This UDL ships with these extensions mapped by default:

- `.ansiblelog`
- `.aaplog`
- `.joblog`

### Use it
Save your output as one of those extensions and reopen the file.

### Change the extensions
Edit `AnsibleJobOutput_UDL.xml` and update the `ext="..."` list on the `<UserLang ...>` line, for example:

```xml
<UserLang name="Ansible Job Output" ext="ansiblelog aaplog joblog txt log" udlVersion="2.1">
```

### Dark mode is recommended
Use Notepad++ Dark Mode / theme to make the editor black and text grey globally:
Settings → Preferences → Dark Mode (enable)
Then tweak: Settings → Style Configurator… → Global Styles → Default Style

