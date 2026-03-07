# Create Role

## Create Role

**Description:** Creates a new role in a server with customizable name, colors, icon, permissions, and other settings.

**Inputs:**

* Server
* Role name
* Primary color
* Secondary color
* Tertiary color
* Icon
* Position
* Hoist role
* Mentionable
* Permissions
* Store role in variable

**Outputs:**

* action

**Variable Types:**

* Server
* Role

**Behaviour:**\
Creates a role in the specified server using the provided configuration.

The role can include a name, up to three colors (primary, secondary, tertiary), and an optional icon. The icon can be either a custom image URL or a Unicode emoji. If a Unicode emoji is detected, it will be set as the role’s emoji instead of an icon.

Additional settings include:

* **Position** — Determines the role’s placement in the role hierarchy.
* **Hoist role** — If enabled, members with this role will be displayed separately in the member list.
* **Mentionable** — Allows anyone to mention the role.
* **Permissions** — A selectable list of permissions that will be assigned to the role.

If a position greater than `0` is provided, the role will be moved to that position after creation.

The created role is stored in the selected **Role variable**, allowing it to be used in later actions. After creation and optional positioning, continues with the next action.
