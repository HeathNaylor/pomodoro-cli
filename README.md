# Pomodoro CLI

This will be a Pomodoro CLI tool that provides the following API:

## API
`pomo start <task>` - Starts a given task, starts the countdown from a preconfigured default of 25 minutes.
`pomo stop <task>` - Stops a given task, clears any checkmarks associated with the task. Fires events for time tracking purposes.
`pomo pause <task>` - Pause a given task, put a checkmark against the task. Cooldown timer of a preconfigured 5 minutes will start. If there are four pomodoro checkmarks, cooldown timer of a preconfigured 20 minutes will start and clear all of the checkmarks
`pomo status` - This will give the current status of the Pomodoro, you will be able to pass formatting options to this command, allowing for integration with tools like Tmux.
`pomo show` - Bring up a full screen text render of the Pomodoro coundown including the current amount of checkmarks applied to the task.
