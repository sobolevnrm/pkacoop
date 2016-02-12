# pKa Cooperative data and presentations

More information about the pKa Cooperative is provided at <http://pkacoop.org>

## Contents

* [isa-tab-data](isa-tab-data) - ISA-Tab formatted version of published datasets.
* [isaconfigPChem](https://github.com/sobolevnrm/pkacoop/tree/master/isaconfigPChem) - ISA configuration files.
* [old-data](old-data) - Data from past pKa Cooperative prediction challenges.
* [presentations](presentations) - Presentations from past pKa Cooperative meetings.

## How to use the configuration and isatab files available in this repository
1.  Clone this repository:  "clone https://github.com/sobolevnrm/pkacoop.git"
2.  Download [ISACreator](http://www.isa-tools.org/software-suite/) for your platform
2.  Start ISACreator.  You will prompted to log in or create an account.
3.  Point to the pkacoop configuration file:
   1.  At this point you will be directed to the configuration loader dialog: ![ISAcreator Configuration](https://github.com/sobolevnrm/pkacoop/blob/master/screenshots/ISAcreatorConfiguration.png "ISA config")
   2.  Selct "Open Another" and select the [pKa specific ISAtab configuration directory](https://github.com/sobolevnrm/pkacoop/tree/master/isaconfigPChem) file from your cloned repository.  Alternatively, you can copy the [pKa specific ISAtab configuration directory](https://github.com/sobolevnrm/pkacoop/tree/master/isaconfigPChem) to the "Configurations" directory of your ISACreator distribution.
   3.  The file will load and take you back to the main menu
4.  Point ISAcreator to the ISAtab files:
   1. Select "Settings" -> "Program File Locations"
   2. Point "ISAtab Location" to the directory containing the [pKa specific ISAtab Files](https://github.com/sobolevnrm/pkacoop/tree/master/isa-tab-data).
   3. Select "back" to return to the main menu
5.  Load pKa isatab files:
  1.  From the ISACreator main menu, select "Load an existing isatab file." ![ISAcreator Main Menu](https://github.com/sobolevnrm/pkacoop/blob/master/screenshots/ISAcreatorMain.png "Main menu")
  2.  Select any of the files available in the dialog. ![ISAcreator Files](https://github.com/sobolevnrm/pkacoop/blob/master/screenshots/ISAcreatorFiles.png "ISA Files") or load the isatab files manually by selecting any one of the isatab directories (e.g. [Assadi-Porter1995](https://github.com/sobolevnrm/pkacoop/tree/master/isa-tab-data/Assadi-Porter1995)) from this repository.  This will allow you to view the metadata associated with this author in the overview of the ISAcreator Overview window.  ![ISAcreator Overview](https://github.com/sobolevnrm/pkacoop/blob/master/screenshots/ISAcreatorOverview.png)
