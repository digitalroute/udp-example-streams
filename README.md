# Pre configured streams for Usage Data Platform by DigitalRoute

Here you will find a number of example streams of various complexity that you can import.

### Simple Transform Stream

This stream serves as an easy example to get you going.

It contains a `counter` node that counts from 1 to 10, then doubling the value in a `transform` node. Finally it logs the doubled values as can be seen in the `logs` option in the toolbar.

### Simple Route Stream

This is another easy example.

It contains a `counter` node that counts from 1 to 10, then routing the value in a `route` node. If the value is equal to 5 or 8 it gets logged, otherwise the value is disregarded, i.e. sent to a `noop` node.