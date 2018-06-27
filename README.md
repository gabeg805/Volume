# vol

## Introduction

Control and print the system volume.

## Dependencies

- amixer

## Usage

The following commands will be run with the default control, *Master*, however
specifying the control option will allow the script to act on the desired
control.

An example of using the control option will be at the end of the Usage section.

### Print current volume level

To print the volume for the *Master*, run the following command:
```
vol
```

### Increment/Decrement the volume level

To increment the volume level, run the following command:
```
vol -i
```

To decrement the volume level, run the following command:
```
vol -d
```

To specify a value to increment/decrement by, use the delta option. The
following command will increment the volume level by 10%.
```
vol -i -D 10
```

### List the available volume controls

```
vol -l
```

### Set the volume level

The following command will set the volume to 75%.
```
vol -s 75
```

### Toggle mute

```
vol -m
```

### Print the mute status

```
vol -S
```
