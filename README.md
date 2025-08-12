# Logic Circuit Project: Digital Occupancy Counter

This repository contains the Proteus project for a digital occupancy counter. It was developed as a final project for the **Logic Circuit** course at **Iran University of Science and Technology (IUST)**, under the supervision of **Dr. Kashi**.

The entire circuit is designed using standard digital logic ICs and does not involve any microcontrollers or programming.

## Key Features

* **Up/Down Counting:** Tracks the number of people entering and exiting a space.
* **7-Segment Display:** The current occupancy count is displayed on a two-digit 7-segment display.
* **Settable Capacity:** The maximum capacity of the space can be set manually using DIP switches.
* **Full-Capacity Alarm:** An LED alarm is triggered when the current count reaches the preset maximum capacity.
* **Reset Functionality:** A master reset button instantly clears the count to zero.

## Technical Details

* **Software:** Designed and simulated in **Proteus Design Suite**.
* **Core Components:**
    * **Counters:** `74LS192` (Synchronous BCD Up/Down Counters)
    * **Display Drivers:** `74LS47` (BCD to 7-Segment Decoders)
    * **Comparator:** `74LS85` (4-Bit Magnitude Comparator) for checking the capacity limit.

## How to Use

1.  Clone the repository.
2.  Open the `.pdsprj` file in Proteus.
3.  Run the simulation.
4.  Use the input buttons for "Enter," "Exit," and "Reset."
5.  Set the desired maximum capacity using the DIP switches to test the alarm functionality.