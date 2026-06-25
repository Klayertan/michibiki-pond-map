# Michibiki Pond Map

Michibiki Pond Map is a hackathon field-survey hazard map for Yamatokoriyama, Japan. It will use NMEA-0183 logs from field walks to visualize pond and waterway hazard observations on a map.

This repository currently contains only the initial project scaffold. Application logic will be added later.

## Hardware Notes

Field data is captured with a QZ1 GNSS receiver using みちびき/QZSS SLAS sub-meter augmentation.

The blue QZ1 receiver has no screen, so the NMEA logs are the proof source for augmentation status. In GGA sentences, a fix-quality field value of `2` indicates a differential GNSS fix and is used here as evidence that みちびき augmentation was active.

## How to Use

Placeholder.
