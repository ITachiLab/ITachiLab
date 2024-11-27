# Ahoy!

## My repos worth looking at

Although every repo is worth seeing, here are the few that I would like to underline.

### [Hotkey Detective](https://github.com/ITachiLab/hotkey-detective)

This is a small Windows application that lets you find out what other application holds a global hotkey, preventing you from using that specific key combination in other places.

Repo's curiosities:

- Windows API
- Windows tricks
- Integrating Windows API and C++

### [Low-delay PL011 driver](https://github.com/ITachiLab/pl011-no-fifo)

My modification of the mainline PL011 (UART) driver for Raspberry Pi. The modification turns off FIFO queueing, effectively speeding up communications which mostly consist of short and single-byte bursts. This is perfect for integration with eBUS (I'm using it for my heating circuit controller).

Repo's curiosities:

- Disabling unwanted, built-in drivers
