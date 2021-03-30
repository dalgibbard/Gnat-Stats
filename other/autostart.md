## Autostart Hardware Serial Monitor
### Enable Administrator running
* Locate Hardware Monitor executable> Right-Click> Properties> Compatibility> Run this program as Admin [X]

### Enable auto-start on system log-in
* Start Menu > Search for "Task Scheduler"
* Create Task
  * General:
    * Name: Whatever you like
    * Run only when user is logged on
    * Run with highest privileges
    * Configure for: Windows 10
  * Triggers> New:
    * Begin the task: At log on
    * Specific User: <your user>
  * Actions> New:
    * Program/script: <Hardware Monitor Executable>
  * Conditions:
    * [optional] Disable "Start the task only if the computer is on AC power"
  * Settings:
    * Enable: "Allow task to be run on demand"
    * Disable: "Stop the task if it runs longer than"

