# Package Manager

**Description:**\
Automatically installs and manages npm packages required by triggers, actions, and extensions by scanning imports and installing missing packages.

**Inputs:**

* Packages (list of package names)

**Behaviour:**\
Scans JavaScript files in triggers, actions, and extensions folders for external imports. Installs missing npm packages automatically. Also installs packages provided in the list input. Logs installation progress and notes that a restart may be needed to complete installation.
