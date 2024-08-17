# Flora Care - Xiaomi

Starting from `https://github.com/sidddy/flora` we continuously send Flora Care sensor data to Blynk

## Initialize

Just remember to create the `config.h` file starting from the `config.h.example`

## Sketch size issues

The sketch does not fit into the default arduino parition size of around 1.3MB. You'll need to change
your default parition table and increase maximum build size to at least 1.6MB. On Arduino IDE this
can be achieved using "Tools -> Partition Scheme -> No OTA"
