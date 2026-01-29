# Call Function

**Description:** Calls a user-defined function with parameters and stores the returned value in a variable.

**Inputs:**

* Function (trigger)
* Store returned value in variable
* Parameters (list)

**Outputs:**

* action

**Variable Types:** None

**Behaviour:** Emits a "function" event with the provided function name and parameters. When the function returns a value, stores it in the given variable and continues.
