# Dumbest Action Recovery Builder

Easily compile your first custom recovery using **GitHub Actions** — with **ldcheck** support.

### Supported Recoveries
- **TWRP**
- **SHRP Reborn**
- **PBRP**
- **OrangeFox (OFRP)**

---

## How to Use

1. **Fork** this repository.

2. Go to the **Actions** tab > **All workflows**, then select the recovery type you want to build:
   - `TWRP`, `PBRP`, `OFRP`, or `SHRP Reborn`

3. Click **Run workflow**, and provide the required information in the dropdowns:
   - **Manifest Branch** (e.g., `12.1`, `11.0`, `10.0`, `9.0`, etc.)
   - **Device Tree** (URL of your device tree repository)
   - **Device Tree Branch** (Branch name of the device tree)
   - **Build Target** (`boot`, `recovery`, or `vendor_boot`)
   - **LDCHECK** (Path to your target binary, e.g., `system/bin/qseecomd`)

> **Tip:** If you're building manually or locally and want to use `ldcheck`, see [this guide](https://github.com/TeamWin/android_device_qcom_twrp-common/tree/android-11#using-ldcheck-to-find-dependencies) for more information.

---

## Credits

Special thanks to the following people and projects:

- [lazycodebuilder](https://github.com/lazycodebuilder)
- [CaptainThrowback](https://github.com/CaptainThrowback)
- [azwhikaru](https://github.com/azwhikaru)
- [cd-Crypton](https://github.com/cd-Crypton)
- [that1](https://github.com/that1)
- [carlodandan](https://github.com/carlodandan)
- And all contributors of the repositories and scripts that made this possible.
