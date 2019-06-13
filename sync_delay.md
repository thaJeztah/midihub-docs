# Sync Delay

A modifier pipe that drops a given number of Real-Time Clock MIDI messages. The dropped message count can be reset using Play Start message.
Using this pipe some tricky MIDI hardware sync incompatibility issues can be resolved.

| Parameter              | Description                                                  |
| ---------------------- | ------------------------------------------------------------ |
| Bypass                 | Whether processing is enabled.                               |
| Delay by               | The amount of clocks to delay by.                            |

[List of Pipes](index.md#the-list-of-pipes)