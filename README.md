# EBTCalc for Windows, Linux, and Mac OSX

EBTCalc (Desktop) is a Reverse Polish Notation (RPN) calculator with custom buttons, programmed in Javascript, using a convenient editor. EBTCalc runs on Windows 10, OSX, and Linux. EBTCalc is open source.

EBTCalc is built on the [`Electron`](https://github.com/electron/electron) framework.

# Copyright

EBTCalc (Desktop)

&#169; Copyright 2020, [`Eric Bergman-Terrell`](https://www.ericbt.com)

# Screenshots

![`EBTCalc Screenshot`](https://www.ericbt.com/uploaded_images/ebtcalc_github.png "EBTCalc Screenshot, Main Window")

![`EBTCalc Screenshot`](https://www.ericbt.com/uploaded_images/ebtcalc_github_2.png "EBTCalc Screenshot, Edit Window")

# Links

* [`website`](https://www.ericbt.com/ebtcalc_electron)
* [`binaries`](https://www.ericbt.com/ebtcalc_electron/download)
* [`installation`](https://www.ericbt.com/ebtcalc_electron/installation)
* [`reference`](https://www.ericbt.com/ebtcalc_electron/reference)
* [`version history`](https://www.ericbt.com/ebtcalc_electron/versionhistory)
* [`donate`](https://www.ericbt.com/ebtcalc_electron/donate)

# Android Version

A version of [`EBTCalc for Android`](https://www.ericbt.com/ebtcalc) is also available.

# Quick Start

To run EBTCalc:

```sh
git clone https://github.com/EricTerrell/EBTCalc.git
cd EBTCalc
npm install
npm start
```

Before running tests, update the path value in builtInOperationsTest.test.js:

```javascript
before(async function () {
    this.app = new Application({
        // Your electron path can be any binary. Specify a path value that points to where you installed EBTCalc.
        path: 'C:\\Users\\Eric Terrell\\Documents\\EBTCalc-win32-x64\\EBTCalc.exe',
```

# License

[`GPL3`](https://www.gnu.org/licenses/gpl-3.0.en.html)

# Feedback

Please submit your feedback to EBTCalc@EricBT.com.