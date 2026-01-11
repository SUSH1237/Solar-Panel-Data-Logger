# Solar Panel Data Logger

## Goal
Log voltage/current data from solar panel setup and save it for analysis.

## Setup
1. Connect voltage/current sensors to Arduino or Raspberry Pi.
2. Upload `data_logger.ino` to the microcontroller.
3. Run `plot_data.py` to visualize CSV data (optional).

## Files
- `data_logger.ino` — Arduino script to read sensors
- `plot_data.py` — Python plotting script
- `sample_data.csv` — Example logged data

## Notes
- Logs data at regular intervals and saves to CSV.
- Can be used for analysis or plotting in Python.
