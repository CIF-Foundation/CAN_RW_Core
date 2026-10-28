# CAN_RW_Core

LabVIEW class that provides the core API for reading and writing CAN frames. Hardware-specific classes, including NI-XNET, inherit from `CAN_RW_CORE.lvclass`.

## Installation

Build or install the package using the VIPM project in [`VIPM/CAN RW Core.vipb`](VIPM/CAN%20RW%20Core.vipb).

Package-specific documentation is in [`VIPM/README.md`](VIPM/README.md).

## Repository Layout

| Path | Description |
| --- | --- |
| `src/` | LabVIEW source for `CAN_RW_CORE.lvclass`, including core, accessors, utilities, typedefs, and tests |
| `VIPM/` | VI Package Manager build specification and package readme |
| `LICENSE` | Apache License 2.0 |

## License

Copyright 2025-2026 CIF Foundation

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

The full license text is in [`LICENSE`](LICENSE).
