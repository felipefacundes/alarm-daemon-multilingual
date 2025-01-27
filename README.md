# Alarm Daemon Multilingual

A powerful and versatile alarm management system for Linux, offering a user-friendly graphical interface and extensive multilingual support. This script is part of the comprehensive [shell_utils framework](https://github.com/felipefacundes/shell_utils), one of the largest collections of scripts and utilities designed to enhance user experience on Linux systems.

## Features

- **Rich Multilingual Support**: Full interface translation for English, Portuguese, French, German, Romanian, Chinese, Korean, Russian, Hebrew, Arabic, and Spanish
- **User-Friendly Interface**: Intuitive graphical interface using Zenity for all interactions
- **Flexible Scheduling Options**:
  - One-time alarms
  - Daily repetition
  - Specific weekday scheduling
  - 10-minute snooze functionality
  - Immediate scheduling without root access

- **Advanced Notification System**:
  - Visual alerts through screen gamma manipulation
  - Audio alerts using system sounds
  - Customizable alert messages
  - Screen flashing for visibility
  - Volume-controlled sound notifications

- **Enhanced Functionality**:
  - Custom script/command execution on alarm trigger
  - File opening capability via xdg-open
  - Persistent alarm storage in ~/.alarms
  - User-level daemon operation
  - Automatic timezone and locale handling

## Installation

```bash
# Clone the repository
git clone https://github.com/felipefacundes/alarm-daemon-multilingual

# Navigate to the project directory
cd alarm-daemon-multilingual

# Make the script executable
chmod +x alarm-daemon-multilingual.sh
```

## Usage

The script provides three main operation modes:

1. Create a new alarm:
```bash
./alarm-daemon-multilingual.sh -c
```

2. Run the alarm daemon:
```bash
./alarm-daemon-multilingual.sh -r
```

3. Display help:
```bash
./alarm-daemon-multilingual.sh -h
```

## System Requirements

- Linux operating system
- X11 display server
- PulseAudio sound system
- Zenity for GUI dialogs
- xrandr for screen management

## Privacy and Security

- All alarm data is stored locally in the user's home directory
- No system-wide installation required
- No root privileges needed
- Self-contained execution environment
- Personal alarm configuration per user

## Integration

The script seamlessly integrates with standard Linux components:
- Works with PulseAudio sound system
- Integrates with X11 display server
- Uses standard filesystem operations
- Compatible with all major desktop environments
- Follows FreeDesktop.org standards

## License

This project is licensed under GPL-3.0

## Credits

Created by Felipe Facundes

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Related Projects

This script is part of the [shell_utils framework](https://github.com/felipefacundes/shell_utils), which provides a comprehensive collection of utilities and scripts for Linux users.