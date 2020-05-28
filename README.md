# Analogy
- Program/Software: Cooking Recipe
- CPU: Chef

# Hardware
- CPU
* Brain of the computer
* Communicate heavily with RAM
* Register: Store the data that CPU works with

- RAM - Randomly Accessed Memory
* Short term memory
* Volatile, once you close your PC, it disappears.

- ROM
* Non volatile
* Store BIOS (Modern BIOS => UEFI)
* BIOS = software that helps initialize the hardware in our PC and get our OS up and running

- CMOS battery
* basic BIOS data about booting your PC (date, time, how you want to start)

- Cache
* Smaller than RAM, but it allow us to store data that we use often
* Almost the same with RAM
* Like the stuff in our pockets vs food in fridge (RAM)
* L1, L2, L3 => L1 is the smallest and fastest

- MCC - Memory Controller Chip
* Connect (aka the bridge) RAM and CPU
* MCC will grab the data from RAM and send it to CPU
* RAM => MCC => CPU

- Hard drive
* Long term memory
* HDD VS SSD
* HDD: Cheaper, but a lot of moving parts, prone to damage
* SDD: Expensive, but faster

- Motherboard
* Circuit board that hold everything together
* Components: chipsets, expansion slot, form factor (aka the shape and layout of the motherboard)
* Chipsets: Decide how components talk to each other on machine
* [Reference](https://computer.howstuffworks.com/motherboard1.htm)

- EDB (External Data Bus)
* Kind of like a veins in our body (Maybe like the nerves?)
* Transport binary data
* Sending a voltage through the wire = 1
* No voltage = 0
* 8, 16, 32, 64 wires
* 8 bits = 1 byte

- Address Bus
* Transport memory address
* MCC => Address Bus => CPU

- Clock Wire
* Internal clock that keeps its operational in sync
* When user send/receive data, he sends a voltage to the clock wire to let the CPU know it can start doing calculation
* Clock speed: Maximum amount of clock cycle that it can handle in a certain period of times
* eg. 3.4 GigaHertz = 3.4 billion cycles per second
* Overclocking: Potentially overheat the CPU/uses more power but also make it significantly faster than what it should be

- Peripheral
* External devices that we connect to the PC, eg. Mouse, keyboard, monitor
