---
title: "LPKF: Design Rules"
layout: doc
author:
date:

---

## Design Rules

You should design your PCBs for the LPKF with the following **design rules**:

1. >= 200/200 um (8/8 mils) trace/space.
2. Minimum drill diameter is 0.35 mm (13.7 mil).
3. Available drills are:
   - 0.35, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.00, 1.2, 1.4, 1.5, 1.6, 1.8, 2.0 mm
   - 13.7, 15.8, 19.7, 23.6, 27.6, 31.5, 35.4, 39, 47.2, 55.1, 59.1, 63, 70.9 , 78.7, 118.1 mils
4. By default, board outline will be routed with a 2.0 mm end mill.

Note that we have an EAGLE CAD design rule file (.DRU) in the LPKF git repo [here](https://github.com/psu-epl/LPKF/tree/master/eagle).

## Making your Gerber files

The CircuitPro software does a pretty decent job of importing Gerber files. To help you along, we've made some EAGLE CAD CAM files for you. You can find them [here](https://github.com/psu-epl/LPKF/tree/master/eagle).



