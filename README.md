# Main Documentation Repo

<!-- Change the name and information here to reflect your organization or repo and its values -->

### [![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)

This is just a simple way of holding templates to use for future repos. As I add generic docs I will update this README to make it easier to locate information. For now it has the following:

## Reference Table

- [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md)
- [CONTRIBUTING](CONTRIBUTING.md)
- [LICENSE](#license)
- [CHANGELOG](CHANGELOG.md)
- [BUG_REPORT_TEMPLATE](/.github/ISSUE_TEMPLATE/bug_report.md)
- [FEATURE_REQUEST_TEMPLATE](/.github/ISSUE_TEMPLATE/feature_request.md)
- [CODE_TEMPLATES](#code_templates)


### Code Of Conduct

Our Code of Conduct template can be used as is, or just modify it and add whatever you need specific to your project. Ours can be found [here](CODE_OF_CONDUCT.md). We network and communicate on Discord so our CoC reflects that.We use the Mozilla Public License v2.0 it covers all of the bases and can be modified to fit your project whatever your needs are. It isn't too long and can be found [here](LICENSE)

### Contributing

Our [contributing](CONTRIBUTING.md) file is pretty simple. It lays out the process for raising issues, how to communicate with org leaders, and where to find the templates to file issues and request feature changes. 

### Changelog

A CHANGELOG is common on `package` repos. It will lay out changes from old versions to the newest release with some detailed information on changes that have taken place and issues solved with this release. 

## CODE_TEMPLATES

The code templates are used in the header of your file to include detailed information on what it does and how to use it along with other information. You do not **HAVE** to use these, but they are good to make into a habit as you grow as a developer.

### JavaScript

This header is very detailed, just remove the fields you do not want to use to trim it down.

```js
/**
 * filename.js
 * This had better be a single object written in JavaScript, if you like your job.
 * Polluting the global space with objects is not good citizenship.
 * Have a nice day. 
 * -- Management
 *
 *
 * @license The Unlicense, http://unlicense.org/
 * @version 0.1
 * @author  The Pffy Authors, https://github.com/pffy/
 * @updated 2014-05-21
 * @link    url goes here
 *
 *
 */
```

## Python

This header is very detailed, just remove the fields you do not want to use to trim it down.

```py
#!/usr/bin/env python
""" Short description of this Python module.
Longer description of this module. This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.
"""

__author__ = "One solo developer"
__authors__ = ["One developer", "And another one", "etc"]
__contact__ = "mail@example.com"
__copyright__ = "Copyright $YEAR, $COMPANY_NAME"
__credits__ = ["One developer", "And another one", "etc"]
__date__ = "YYYY/MM/DD"
__deprecated__ = False
__email__ =  "mail@example.com"
__license__ = "GPLv3"
__maintainer__ = "developer"
__status__ = "Production"
__version__ = "0.0.1"
```