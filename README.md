<img align="right" width="250" height="47" src="images/Gematik_Logo_Flag_With_Background.png"/> <br/>

# ePA-FdV Test Driver

This repository contains the OpenAPI specification for the ePA-FdV Test driver API. The API is used to test the ePA-FdV implementation in context of automated tests for gematik approval process.

The test driver module transfers information from the external interface defined in this repo to a manufacturer-specific internal interface to trigger certain requirements for the ePA FdV. It acts as a gateway and doesn't implement its own logic, like retrieving additional information. It is allowed to process the responses from the ePA FdV according to the technical interface, but it must not change the technical content.

Binding to a document release takes place via tags. A tagged version is a normative part of the specification of the referenced document release.

This repository is also used for the collaborative further development of the ePA-FdV Test driver interface by ePA-FdV manufacturers and gematik. Hints, issues and pull requests are welcome.

The API specifications that apply to a given document release are maintained in the corresponding branch (e.g. `ePA3.0.5`). During development, interim versions are tagged as `<version>-rc<n>` (e.g. `3.0.5-rc3`), where `rc` stands for “release candidate”. The version that is binding for approval (Zulassung) is marked with the final document release version (e.g. `3.0.5`).

## License

Copyright 2024-2025 gematik GmbH

Apache License, Version 2.0

See the [LICENSE](./LICENSE) for the specific language governing permissions and limitations under the License

## Additional Notes and Disclaimer from gematik GmbH

1. Copyright notice: Each published work result is accompanied by an explicit statement of the license conditions for use. These are regularly typical conditions in connection with open source or free software. Programs described/provided/linked here are free software, unless otherwise stated.
2. Permission notice: Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    1. The copyright notice (Item 1) and the permission notice (Item 2) shall be included in all copies or substantial portions of the Software.
    2. The software is provided "as is" without warranty of any kind, either express or implied, including, but not limited to, the warranties of fitness for a particular purpose, merchantability, and/or non-infringement. The authors or copyright holders shall not be liable in any manner whatsoever for any damages or other claims arising from, out of or in connection with the software or the use or other dealings with the software, whether in an action of contract, tort, or otherwise.
    3. The software is the result of research and development activities, therefore not necessarily quality assured and without the character of a liable product. For this reason, gematik does not provide any support or other user assistance (unless otherwise stated in individual cases and without justification of a legal obligation). Furthermore, there is no claim to further development and adaptation of the results to a more current state of the art.
3. Gematik may remove published results temporarily or permanently from the place of publication at any time without prior notice or justification.
4. Parts of this software and - in isolated cases - content such as text or images may have been developed using the support of AI tools. They are subject to the same reviews, tests, and security checks as any other contribution. The functionality of the software itself is not based on AI decisions.
