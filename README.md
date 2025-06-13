# -IoT--

Вот весь текст `README.md`, написанный прямо здесь в чате:

---

# Door Monitoring Project

This is a simple Python project for monitoring the state of a door using a text file as the data source.

## Files

* `door_monitor_bot.py` – reads the door state and logs changes.
* `door_sensor_emulator.py` – simulates door state changes.
* `door_state.txt` – stores the current state (`open` or `closed`).
* `log.txt` – saves all door events with timestamps.

## How to Use

1. Run the sensor emulator:

   python door_sensor_emulator.py
   
2. In another terminal, run the monitor bot:

   python door_monitor_bot.py

The bot will check the door state and write changes to the log file.

## Requirements

* Python 3.x
* No additional libraries needed

## Example Output

Example content of `log.txt`:

[2025-06-13 10:00:01] Door opened  
[2025-06-13 10:01:45] Door closed  

## Notes

* Make sure both scripts are in the same directory.
* The emulator overwrites the door state every few seconds.

