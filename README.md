### Script to upload MODX Revolution for installation in 1 Click

#### This script is intended for initial installation. Install the Updater extra for upgrades.


Place the install.php file in the same directory as your site root. Load it in your browser and select the version you want to install. (i.e. mydomain.com/install.php)

The script will download the selected version from the MODX respository, unzip it in the same location, then forward you to the MODX setup. The install.php script will automatically delete itself.

#### This script is intended for initial installation. Install the Updater extra for upgrades.

In order to be able to directly download the MODX zip archive from the MODX repository, your server must have either allow_url_fopen or cURL enabled.

In order to be able to unzip the downloaded MODX archive, your PHP must be at least version 5.2, it must have been compiled to include the zip extensions, and have the zip extension enabled.

You may need to change the permissions for newly created folders on line 184. For example, your server may require directory permissions of 0755.

Changelog:

Version 1.6.26
(04.28.2021)
- Add links for Revo 2.8.2
- Remove links for 2.7.x

Version 1.6.25
(10.22.2020)
- Add links for Revo 2.8.1

Version 1.6.24
(10.06.2020)
- Add links for Revo 2.8.0

Version 1.6.23
(02.28.2020)
- Add links for Revo 2.7.3

Version 1.6.22
(09.26.2019)
- Add links for Revo 2.7.2
- Remove links for pre-2.7.0

Version 1.6.21
(02.14.2019)
- Add links for Revo 2.7.1
- Remove links pre-2.6.5

Version 1.6.20
(11.27.2018)
- Add links for Revo 2.7.0

Version 1.6.19
(07.13.2018)
- Add links for Revo 2.6.5

Version 1.6.18
(06.18.2018)
- Add links for Revo 2.6.4

Version 1.6.17
(04.19.2018)
- Add links for Revo 2.6.3

Version 1.6.16
(03.30.2018)
- Add links for Revo 2.6.2

Version 1.6.15
(12.15.2017)
- Add links for Revo 2.6.1

Version 1.6.14
(11.01.2017)
- Add links for Revo 2.6.0

Version 1.6.13
(09.14.2017)
- Add links for Revo 2.5.8

Version 1.6.12
(05.04.2017)
- Add links for Revo 2.5.6 and 2.5.7

Version 1.6.11
(09.02.2017)
- Add links for Revo 2.5.5
- Merge fixes for cURL

Version 1.6.9
(22-11-2016)
- Add links for Revo 2.5.2

Version 1.6.8
(30-08-2016)
- Fix bug causing 500 error

Version 1.6.7
(21-07-2016)
- Updated for Revo 2.5.1 release

Version 1.6.6
(06-05-2016)
- Corrected line 205 to use the mmkDir() function

Version 1.6.5
(22-04-2016)
- Changed test for safe_mode and open_basedir to account for non-boolean results, thanks to bezumkin and jako

Version 1.6.4
(21-04-2016)
- Update to Revo 2.5.0-pl

Version 1.6.3
(07-04-2016)
- Update to Revo 2.5.0-rc2

Version 1.6.2
(06-04-2016)
- Update to Revo 2.4.4
- Chaged URLs to use https

Version 1.6.1
(11-02-2016)
- Update to Revo 2.4.3
- Add targets to links

Version 1.6.0
(08-02-2016)
- Update to offer 2.5.0-RC1

Version 1.5.5
(06-10-2015)
- Update to 2.4.2

Version 1.5.4
(24-09-2015)
- Update to 2.4.1

Version 1.5.3
(30-08-2015)
- Updated links to 2.3.5
- Removed links to 2.2.x

Version 1.5.2
(19-08-2015)
- Updated links to Revo 2.4.0 release

Version 1.5.1-beta
(11-07-2015)
- Corrected some single-quotes

Version 1.5.0-beta
(26-06-2015)
- Change links back to MODX repository direct links
- Modified cURL code to emulate CURLOPT_FOLLOWLOCATION for systems with open_basedir and safe_mode

Version 1.4.3
(24-06-2015)
- Changed links to direct links to AWS to solve problems with servers that have open_basedir or safe_mode enabled.
- Dropped support for 2.2.16 due to some of the archive having issues unzipping.

Version 1.4.2
(24-06-2015)
- Updated to Revolution 2.3.4

Version 1.4.1
(19-02-2015)
- Fixed failure to extract error - temp directory needed trailing slash

Version 1.4 
(30-01-2015)
- updated to Revolution 2.3.3
