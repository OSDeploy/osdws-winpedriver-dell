> [!NOTE]
> Vendor Published Drivers

---

# Dell

---

| Released | Build | Version | Download |
|--|--|--|--|
| 2024.10.25 | TPKY4 | A05 | https://downloads.dell.com/FOLDER12189044M/1/WinPE11.0-Drivers-A05-TPKY4.cab |

---

## Changelog
```
2025.01.05 - David Segura updated Drivers to the latest version.
```

---

## Notes
Drivers are imported into MDT (Microsoft Deployment Toolkit) to normalize the Driver folder structure and to validate the Driver content before adding to this Repository.

```
Download the latest DriverPack.
Expand the DriverPack to a temporary folder.
Copy any additional content from the temporary folder to .\Dell\*.*.
    .\Dell\driverarchivemanifest.xsd
    .\Dell\Manifest.xml
    .\Dell\Readme.txt
Import Drivers into an empty MDT Deployment Share.
Save the MDT Import Drivers output as .\Dell\ImportDrivers.txt.
Copy the MDT Drivers in "<Deployment Share>\Out-of-Box Drivers" to .\Dell\MDT\*.*.
Copy "<Deployment Share>\Control\Drivers.xml" as .\Dell\Drivers.xml.
In MDT Out-of-Box Drivers, run the Export List. Save the file as .\Dell\ExportList.csv.
```
---

## Links
- Dell Command | Deploy Driver Packs for Enterprise Client Operating System Deployment
  - https://www.dell.com/support/kbdoc/en-us/000124139/dell-command-deploy-driver-packs-for-enterprise-client-os-deployment
- Dell Command | Deploy WinPE Driver Packs
  - https://www.dell.com/support/kbdoc/en-us/000107478/dell-command-deploy-winpe-driver-packs
- WinPE 11 driver pack
  - https://www.dell.com/support/kbdoc/en-us/000211541/winpe-11-driver-pack

---