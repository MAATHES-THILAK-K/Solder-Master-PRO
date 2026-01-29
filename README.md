# **SolderMaster PRO v1.0** 🔥

**Precision soldering station with smart temperature control**

## 📋 Quick Features
- ATtiny85 microcontroller
- Dallas DS18B20 temperature sensor (JST connector)
- 128x32 OLED display
- RTC with timer functions
- 10A relay for iron control
- Single-button interface
- 230V AC input with safety protection

## 🔌 Connections
```
ATtiny85 Pins:
PB0 → DS18B20 Data (+4.7k pull-up)
PB2 → OLED SCL
PB3 → OLED SDA + Relay control
PB4 → User button (+10k pull-up)
PB1 → RTC SDA
PB2 → RTC SCL
```

## ⚡ Power Input
- **Input**: 230V AC, 2A fuse, MOV protection
- **Conversion**: HiLink 5V isolated module
- **Output**: 5V DC for electronics + 230V to relay

## 🎮 Operation
- **Short press**: Cycle display modes
- **Long press (2s)**: Enter menu
- **In menu**: Adjust values
- **Long press (5s)**: Save & exit

## 📊 Display Modes
1. **Main Screen**: Temp/Set temp, timer, power %
2. **Timer Set**: Auto shutoff timer
3. **Statistics**: Usage time and sessions

## ⚠️ Safety Notes
- **HIGH VOLTAGE** - 230V AC present
- **HOT SURFACE** - Iron reaches 450°C
- **FIRE RISK** - Never leave unattended
- Always use proper enclosure
- Connect ground wire to iron

## 🔧 Quick Setup
1. Connect iron to relay output
2. Connect DS18B20 to JST port
3. Plug into 230V AC
4. Set temperature with button
5. Iron heats in 60-90 seconds

## 📞 Support
- Check connections first
- Verify all voltages
- Contact for schematic/code

---

**Built for precision soldering | DIY friendly | Professional results**
