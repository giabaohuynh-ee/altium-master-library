# Altium Master Component Library

Personal Altium Designer integrated library of verified, reusable parts for embedded and power PCB projects. Each part includes a symbol, a footprint, and sourcing data (Manufacturer, MPN, LCSC), so exported BOMs are ready to order. Passives use JLCPCB Basic parts where possible.

## Parts

| Category | Part | Value | Footprint | MPN | LCSC |
|---|---|---|---|---|---|
| Resistor | RES_1K_0603 | 1k | RESC1608X55N | 0603WAF1001T5E | C21190 |
| Resistor | RES_4.7K_0603 | 4.7k | RESC1608X55N | 0603WAF4701T5E | C23162 |
| Resistor | RES_5.1K_0603 | 5.1k | RESC1608X55N | 0603WAF5101T5E | C23186 |
| Resistor | RES_10K_0603 | 10k | RESC1608X55N | 0603WAF1002T5E | C25804 |
| Resistor | RES_100K_0603 | 100k | RESC1608X55N | 0603WAF1003T5E | C25803 |
| Capacitor | CAP_22PF_0603 | 22pF | CAPC1608X90N | CL10C220JB8NNNC | C1653 |
| Capacitor | CAP_100NF_0603 | 100nF | CAPC1608X90N | CC0603KRX7R9BB104 | C14663 |
| Capacitor | CAP_1UF_0603 | 1uF | CAPC1608X90N | CL10A105KB8NNNC | C15849 |
| Capacitor | CAP_10UF_0603 | 10uF | CAPC1608X90N | CL10A106KP8NNNC | C19702 |
| LED | LED_RED_0603 | Red | LED_0603 | KT-0603R | C2286 |
| LED | LED_GREEN_0603 | Green | LED_0603 | KT-0603G | C12624 |
| Regulator | LDO_AMS1117-3.3 | 3.3V 1A | SOT-223 | AMS1117-3.3 | C6186 |
| Connector | CONN_USB-C_16P | USB 2.0 | USB-C_16P_TYPE-C-31-M-12 | TYPE-C-31-M-12 | C165948 |
| Connector | HDR_1X2 | 1x2 | HDR_1X2_P2.54 | 61300211121 | - |
| Connector | HDR_1X3 | 1x3 | HDR_1X3_P2.54 | 61300311121 | - |
| Connector | HDR_1X4 | 1x4 | HDR_1X4_P2.54 | 61300411121 | - |
| Connector | HDR_1X6 | 1x6 | HDR_1X6_P2.54 | 61300611121 | - |

## Conventions

- Symbols: `TYPE_VALUE_PACKAGE` (e.g. `RES_10K_0603`). Comment is `=Value`.
- Footprints: IPC-7351 names for chip passives, short names for connectors.
- All symbol pins are checked against footprint pads. The SOT-223 tab pad is numbered `2` (VOUT).
- LED: pin 1 = anode, pin 2 = cathode.

## Usage

1. Clone this repository.
2. Open `MasterLibrary.LibPkg` in Altium Designer.
3. Right-click the project and select **Compile Integrated Library**.