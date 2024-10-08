---
uid: Connector_help_Nevion_Flashlink_Frame_-_3G-HD-OEL
---

# Nevion Flashlink Frame - 3G-HD-OEL

This exported connector shows data from a 3G-HD-OE-L module in a Nevion Flashlink frame.

## About

This is an **SNMP** connector that is automatically generated by the parent connector [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

### Version Info

| Range     | Description                                      | DCF Integration     | Cassandra Compliant     |
|------------------|--------------------------------------------------|---------------------|-------------------------|
| 1.0.0.x          | Basic range                                      | No                  | Yes                     |
| 2.0.0.x          | Tree controls added to monitor parameters        | No                  | Yes                     |
| 2.0.1.x          | Audio Block status fix (ONLY for firmware 2.0.4) | No                  | Yes                     |
| 2.0.2.x          | Changed naming structure                         | No                  | Yes                     |

### Product Info

| Range | Supported Firmware Version |
|------------------|-----------------------------|
| 1.0.0.x          | Unknown                     |
| 2.0.0.x          | Unknown                     |
| 2.0.1.x          | 5.0.4                       |
| 2.0.2.x          | 5.0.4                       |

## Installation and configuration

### Creation

This connector is used by DVE child elements that are **automatically created** by the parent connector [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

## Usage

### General Page

This page contains general information about a 3G-HD-OE-L module, including:

- Type
- Card Status
- Chassis Number
- Slot Number
- Label
- Alarm Status
- Alarm Trap
- Alarm Count
- Main Element Name
- Active Alarms in System

### Voltage Page

This page displays the **Voltage Table**, which contains information about voltage measurements.

It also allows you to configure the **Upper** and **Lower Limit** and **Alarms**, as well as to view the **Nominal** effect and the **Value** in Volts and Watts.

### Temperature Page

This page displays the **Temperature Table**, which contains information about temperature measurements.

It also allows you to configure the **Nominal** value, **Upper** and **Lower Limit** and **Alarms**, as well as to view the actual temperature **Value**.

### Optical Input Page

This page displays the **Optical Input** table, which contains information about optical input parameters.

It also allows you to view the **Opt Input**, **Input Status** and **Signal Strength**, as well as to configure the **Opt Input Alarms**.

### Reclocker Page

This page displays the **Reclocker Table**, which contains information about reclocker parameters.

It also allows you to view the Reclocker **Num**, **Status** and **Bit Rate**, as well as to configure **Config**, **ASI**, **Bandwidth** and **Alarms**.

### GPIO Page

This page displays the **General Purpose Input Output Table**, which contains information regarding I/O blocks.

It also allows you to configure the **Mode**, **Status**, **Description** and **Alarms**.
