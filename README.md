# Open Commissioning: TwinCAT Profinet Library

The TwinCAT Profinet Library is used in the TwinCAT PLC project and provides the behaviour models for Profinet devices as function blocks.

## Project setup
+ Create PLC Project
+ Install and add the `OC_Profinet` compiled-library
+ Install referenced libraries (see below)

## Referenced libraries

| Library       | Organisation             | Version | Download                                                                                                                                |
|:--------------|:-------------------------|:-------:|:----------------------------------------------------------------------------------------------------------------------------------------|
| OC_Core       | Opem Commissioning       | 1.3.1.0 | [OC_Core.library](https://github.com/OpenCommissioning/OC_TwinCAT_Core/releases/download/v1.3.1/OC_Core.library)                        |
| OC_Profisafe  | Opem Commissioning       | 1.0.0.0 | [OC_Profisafe.library](https://github.com/OpenCommissioning/OC_TwinCAT_Profinet/releases/download/v1.0.0/OC_Profisafe.compiled-library) |                                                                                     |
| Tc2_Math      | Beckhoff Automation GmbH | 3.4.4.0 | -                                                                                                                                       |
| Tc2_Standard  | Beckhoff Automation GmbH | 3.4.5.0 | -                                                                                                                                       |
| Tc2_System    | Beckhoff Automation GmbH | 3.6.4.0 | -                                                                                                                                       |
| Tc2_Utilities | Beckhoff Automation GmbH | 3.8.2.0 | -                                                                                                                                       |
| Tc3_Module    | Beckhoff Automation GmbH | 3.4.5.0 | -                                                                                                                                       |
| TcUnit        | TcUnit.org               | 1.3.0.0 | [TcUnit.library](https://github.com/tcunit/TcUnit/releases/download/1.3.0.0/TcUnit.library)                                             |

> [!NOTE]
> It is recommended to have the same versions installed on your system.
> However, newer versions should be safe to use in most cases, but without guarantee.
> The Beckhoff libraries are included in the TwinCAT installation and can't be downloaded as single file.

## Contributing
We welcome contributions from everyone and appreciate your effort to improve this project.
We have some basic rules and guidelines that make the contributing process easier for everyone involved.

### Submitting Pull Requests
1. For non-trivial changes, please open an issue first to discuss your proposed changes.
2. Fork the repo and create your feature branch.
3. Follow the code style conventions and guidelines throughout working on your contribution.
4. Create a pull request with a clear title and description.

> [!NOTE]
> All contributions will be licensed under the project's license

### Code Style Convention
Please follow [Beckhoff Programming Conventions](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_plc_intro/12049233675.html&id=6398798947359024199) in your code.

### Guidelines for Contributions
- **Keep changes focused:** Submit one pull request per bug fix or feature. This makes it easier to review and merge your contributions.
- **Discuss major changes:** For large or complex changes, please open an issue to discuss with maintainers before starting work.
- **Commit message format**: Use the [semantic-release](https://semantic-release.gitbook.io/semantic-release#commit-message-format) commit message format.
- **Write clear code:** Prioritize readability and maintainability.
- **Be consistent:** Follow existing coding styles and patterns in the project.
- **Include tests:** It is recommended to add or update tests to cover your changes.
- **Document your work:** Update relevant documentation, including code comments and user guides.

## Credits for third-party software components and developers:
* [TcUnit](https://github.com/tcunit/TcUnit) - TwinCAT unit testing framework
