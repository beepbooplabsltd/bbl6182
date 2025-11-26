BBL6182™ security design
==========================

## Overview

The BBL6182 is a physical adapter device that is designed to convert between a 3.5mm TRS male connector and Motorola mobile GCAI female connector. Electrically it is a transparent pass-through device.

It is **not** a cryptographic device: it does not generate keys, store keys, encrypt or decrypt data, or perform any other function of a cryptographic device.

## Details

| Component                  | Notes |
|----------------------------|-------|
| **Algorithms**             | The BBL6182 does not implement or use any encryption algorithms in hardware or firmware.
| **Cryptographic boundary** | The BBL6182 does not have a cryptographic boundary, as it does not perform any cryptographic operations.
| **Development**            | The BBL6182 is designed, assembled, and tested in the United States by US nationals.
| **FIPS validation**        | The BBL6182 is not FIPS validated.
| **Firmware security**      | The BBL6182 does not contain any firmware.
| **Keys**                   | The BBL6182 does not contain any CSPs or keys.
| **Logging**                | The BBL6182 does not perform any logging.
| **Other attacks**          | The BBL6182 is not designed to mitigate any specific attacks outside of those listed in this table, including but not limited to power consumption, timing, fault induction, or TEMPEST attacks.
| **Physical security**      | The BBL6182 does not include any physical anti-tamper features. All components are general-purpose commodity components; no custom components are used.
| **Ports**                  | The BBL6182 provides two physical ports, both of which are used for data input/output. 3.5mm TRS and GCAI are both used for TIA-102.AACD-A KFD protocol. GCAI is also used for accessory identification.
| **RNG**                    | The BBL6182 does not implement or use any random number generators in hardware or firmware.
| **Roles**                  | The BBL6182 supports one role: user.
| **Software**               | The BBL6182 does not interact with any software.
| **Storage: non-volatile**  | The BBL6182 does not use any non-volatile memory to store any encryption key material being sent. Accessory identification data is stored in non-volatile memory; this memory is physically and electrically separated from encryption key material.
| **Storage: volatile**      | The BBL6182 does not contain any volatile memory.

## Disclaimer

The above security details apply to a BBL6182 as manufactured, using original hardware provided by beep boop labs.

Unauthorized physical access to the BBL6182 or radios being keyloaded could result in malicious modifications by a third-party.

⚠️ It is the user's responsibility to maintain physical and electronic control of their BBL6182 device, radios they connect it to, and their encryption key material, at all times to prevent tampering.
