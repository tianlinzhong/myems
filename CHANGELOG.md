# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]
### Added
- None.

### Changed
- None.

### Fixed
- None.

### Removed
- None.


## [v1.1.0] - 2021-03-18
### Added
- added excel exporter of equipmentefficiency report.
- added excel exporter of conbinedequipmentefficiency report in API.
- added 'optional' tips to meter,virtual meter and offline meter setting in admin UI.
- added Optional key to translation in admin UI.
- added cominbedequipmentefficiency report to api and web.
- added equipmentefficiency report api.

### Changed
- updated cost file controller in admin UI
- updated user login session expire time to 8 hours.
- changed web UI and API to set contact of space is optional.

### Fixed
- fixed http headers issues of offlinemeterfile, knowledgefile and costfile in admin UI
- changed float datatype to Decimal datatype for offline meter normalization.
- fixed issue of add space in web UI.
- added historical database close and disconnect at the end of reports.

### Removed
- None.

## [v1.0.8] - 2021-03-11
### Added
- added excel exporter of combinedequipmentstatistics report
- added translation for German
- added excel exporter of storesaving report
- added excel exporter of equipmentincome report
- added excel exporter of shopfloorsaving report
- added excel exporter of equipmentload report

### Changed
- Changed default reporting range in EnergyFlowDiagram.

### Fixed
- None.

### Removed
- None.

## [v1.0.7] - 2021-03-07
### Added
- added excel exporter of storeload report
- added excel exporter of spaceincome report
- added excel exporter of equipmentsaving report
- added excel exporter of combinedequipmentsaving report
- added excel exporter of combinedequipmentload report
- added excel exporter of spaceoutput report
- added excel exporter of combinedequipmentoutput
- added excel exporter of combinedequipmentcost report
- added excel exporter of shopfloorcost report
- added excel exporter of shopfloorload report
- added excel exporter of combinedequipmentenergycategory report
- added excel exporter of combinedequipmentitem report.
- added excel exporter of equipmentenergyitem report.
- added excel exporter of equipmentenergycategory report.
- added excel exporter of shopfloorenergyitem report.

### Changed
- None.

### Fixed
- fixed wrong HTTP headers in admin.
- fixed typo in combinedequipment controller in admin.
- fixed energy item undefined issue when edit virtual meter and offline meter.

### Removed
- removed 'required' property from equipment model in admin.

## [v1.0.6] - 2021-02-26
### Added
- added store statistics report excel exporter.
- added equipment tracking excel exporter.
- added store cost report excel exporter.
- added equipment statistics report excel exporter.
- added store energy item report excel exporter.
- added shopfloor statistics report excel exporter.
- merged myems-api.

### Changed
- modified database table tbl_energy_flow_diagrams_links

### Fixed
- fixed energy category names and units issue in EnergyItem reports.

### Removed
- None.

## [v1.0.5] - 2021-02-23
### Added
- None.

### Changed
- None.

### Fixed
- None.

### Removed
- None.

[Unreleased]: https://github.com/MyEMS/myems/compare/v1.1.0...HEAD
[v1.0.8]: https://github.com/MyEMS/myems/compare/v1.0.8...v1.1.0
[v1.0.8]: https://github.com/MyEMS/myems/compare/v1.0.7...v1.0.8
[v1.0.7]: https://github.com/MyEMS/myems/compare/v1.0.6...v1.0.7
[v1.0.6]: https://github.com/MyEMS/myems/compare/v1.0.5...v1.0.6
[v1.0.5]: https://github.com/MyEMS/myems/releases/tag/v1.0.5

