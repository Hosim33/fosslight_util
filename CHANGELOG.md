# Changelog

## v1.4.9 (01/09/2022)
## Changes
## 🐛 Hotfixes

- Fix to sigalrm error for windows @dd-jy (#93)

## 🔧 Maintenance

- Add a variable for yocto that loads from yaml @soimkim (#91)
- Change FOSSLIGHT -> FOSSLight in help msg @bjk7119 (#90)

---

## v1.4.8 (12/08/2022)
## Changes
## 🔧 Maintenance

- Add function to convert excel to yaml @bjk7119 (#89)
- Check if the type of item in yaml is list @soimkim (#87)

---

## v1.4.7 (09/08/2022)
## Changes
## 🔧 Maintenance

- Modify to be available .yml file for yaml parsing @bjk7119 (#86)
- Modify to convert `*sbom-info*.yaml` @bjk7119 (#85)

---

## v1.4.6 (04/08/2022)
## Changes
- Set xlrd==1.2.0 to read .xlsx file @bjk7119 (#84)

---

## v1.4.5 (01/08/2022)
## Changes
## 🐛 Hotfixes

- Fix a bug that returns even if there is no result file. @soimkim (#82)

## 🔧 Maintenance

- Check null after removing empty sheet @soimkim (#83)
- Remove unnecessary return variables @soimkim (#81)

---

## v1.4.4 (22/07/2022)
## Changes
## 🔧 Maintenance

- Fix not to create csv if format is empty @dd-jy (#80)

---

## v1.4.3 (19/07/2022)
## Changes
## 🔧 Maintenance

- Print warning msg when there is no matched sheet @bjk7119 (#79)
- Add read_excel.py file @bjk7119 (#78)

---

## v1.4.2 (15/07/2022)
## Changes
## 🐛 Hotfixes

- Fix bug where relpath is printed differently in yaml @soimkim (#77)

## 🔧 Maintenance

- Change error msg of parsing yaml error @bjk7119 (#76)

---

## v1.4.1 (12/07/2022)
## Changes
## 🚀 Features

- Add the function to compare yaml @dd-jy (#74)

## 🐛 Hotfixes

- Fix the error to write opossum @dd-jy (#75)

---

## v1.4.0 (16/06/2022)
## Changes
## 🚀 Features

- Add to write yaml @dd-jy (#68)

## 🐛 Hotfixes

- Add field for FOSSLight Report's BIN (*) Sheet @soimkim (#73)
- Fix the bug with ./ for path @soimkim (#72)

## 🔧 Maintenance

- Add a yaml field for file @soimkim (#71)
- Change parsing_yaml return value @bjk7119 (#70)
- Apply parsing new yaml format @bjk7119 (#69)

---

## v1.3.20 (11/05/2022)
## Changes
## 🔧 Maintenance

- Add resue output format for check_output_format fct. @bjk7119 (#67)

---

## v1.3.19 (10/05/2022)
## Changes
## 🔧 Maintenance

- Update SPDX lcense list data v3.17 @dd-jy (#66)

---

## v1.3.18 (02/05/2022)
## Changes
## 🔧 Maintenance

- Modify relative path in parsing yaml function @bjk7119 (#65)

---

## v1.3.17 (29/04/2022)
## Changes
## 🔧 Maintenance

- Add yaml parsing code @bjk7119 (#64)

---

## v1.3.16 (22/04/2022)
## Changes
## 🐛 Hotfixes

- Fix the unbound error (write_excel.py) @dd-jy (#63)

---

## v1.3.15 (14/04/2022)
## Changes
## 🐛 Hotfixes

- Fix the bug where csv name is output differently @soimkim (#62)
- Fix formatting errors that occur when dir is input @soimkim (#60)

## 🔧 Maintenance

- Add a commit message checker @soimkim (#59)

---

## v1.3.14 (24/02/2022)
## Changes
## 🐛 Hotfixes

- Modify to get the source url for pypi @dd-jy (#57)

## 🔧 Maintenance

- Comment out some sentences in the PR template @soimkim (#58)
- Install pygit2 according to python version @soimkim (#56)

---

## v1.3.13 (17/02/2022)
## Changes
## 🔧 Maintenance

- When merging excel, add the option to create a csv file @soimkim (#55)

---

## v1.3.12 (10/02/2022)
## Changes
## 🐛 Hotfixes

- Fix the opossum result to print the multiple resourcesToAttribution @dd-jy (#54)

## 🔧 Maintenance

- Update spdx license list data v3.16 @dd-jy (#53)
- Print output file(s) list @bjk7119 (#52)

---

## v1.3.11 (20/01/2022)
## Changes
## 🔧 Maintenance

- When outputting opossum format, cut as many columns as necessary. @bjk7119 (#51)

---

## v1.3.10 (14/01/2022)
## Changes
## 🔧 Maintenance

- Support to output SRC and BIN sheets as opossum. @soimkim (#49)

---

## v1.3.9 (13/01/2022)
## Changes
## 🐛 Hotfixes

- Add scanoss info on opossum @JustinWonjaePark (#46)

## 🔧 Maintenance

- Modify to run github action for all branches when PR is created. @bjk7119 (#48)
- Change the upgrade message @soimkim (#47)

---

## v1.3.8 (04/01/2022)
## Changes
## 🔧 Maintenance

- Add function for print package version @soimkim (#45)

---

## v1.3.7 (30/12/2021)
## Changes
- Add extended header feature for additional information on excel @soimkim (#44)

## 🚀 Features

- Add extended header feature for additional information on excel @JustinWonjaePark (#43)

---

## v1.3.6 (18/11/2021)
## Changes
## 🐛 Hotfixes

- Fix bug in opossum exporter @nicarl (#37)

## 🔧 Maintenance

- Modify the tox issue @dd-jy (#41)
- Update spdx license list data v3.15 @dd-jy (#39)
- Exclude null fields from opossum export @nicarl (#38)

---

## v1.3.5 (28/10/2021)
## Changes
## 🔧 Maintenance

- Add function to get spdx licenses @dd-jy (#36)

---

## v1.3.4 (21/10/2021)
## Changes
## 🚀 Features

- Modify the function to write opossum result @dd-jy (#35)

## 🔧 Maintenance

- Modify the function to write opossum result @dd-jy (#35)

---

## v1.3.3 (18/10/2021)
## Changes
## 🚀 Features

- Add the function to write opossum format result file and modify the function write result file. @dd-jy (#33)

## 🔧 Maintenance

- Add the function to write output with format @dd-jy (#34)
- Add the function to write opossum format result file and modify the function write result file. @dd-jy (#33)

---

## v1.3.2 (12/10/2021)
## Changes
## 🔧 Maintenance

- Update version of pygit2 to 1.6.1 @soimkim (#32)

---

## v1.3.1 (24/09/2021)
## Changes
## 🔧 Maintenance

- Change sheet name format when merging excel @soimkim (#31)
