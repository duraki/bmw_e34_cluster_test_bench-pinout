# bmw_e34_cluster_test_bench-pinout

![](/etc/ui/web-README_final_preview.png)

## GENERAL INFORMATION

This repository is a public analysis of a BMW 5 Series E34 instrument cluster dashboard, for cars produced up to 1996 (MY. `1988–1996`). Alongside the visual analysis of specific pins and headers, the pinout and expected voltage levels or bus signals required to trigger the sensor data are described next to each pin number. Each pin row aims to fully describe the purpose of each wire interface on the backside of the instrument cluster. This analysis began theoretically and evolved from early breadboard playground testing. It now lives permanently in the public domain, culminating in final PCB KiCad schematics, printables, and—hopefully—logically correct production files. Anyway...

* The source file is: [`E34_Low_Cluster_1988-1990-Pinout-Diagram `**`.numbers`**](/E34_Low_Cluster_1988-1990-Pinout-Diagram.numbers)
* Final build is a PDF: [`E34_Low_Cluster_1988-1990-Pinout-Diagram `**`.pdf`**](/E34_Low_Cluster_1988-1990-Pinout-Diagram.pdf), for `/exports/`, see [this page](/exports/pdf/)

### SUPPORTED MODELS

* BMW E32 (MY. ALL M.YEARS)
* BMW E34 (MY. ALL M.YEARS)

### FUTURE WORK

* [x] VDO LCD Display (11 AVAIL. LCD BACKSIDE PINS, `BLUE_CONNECTOR`)
* [ ] VDO LCD Display (18 AVAIL. LCD BACKSIDE PINS, `GREEN_CONNECTOR`)

## OWNERS

```
This file is a proprietary document that defines code ownership and review
responsibilities for the associated files available in this directory. The 
ownership remains soley to the original organizational owner of the project
available at the time of writing on the following URL: 
    https://github.com/durakiconsulting
```

**Primary code owners**

- `h@durakiconsulting.com`

**Optional approvers**

- `jane@example.com  # Frontend expert`
- `mark@example.com  # Security reviewer`

## CREDITS

Where due, credits shall be given to their respectful innovators.

Happy benching `:-)`
