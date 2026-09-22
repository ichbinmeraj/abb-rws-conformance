# abb-rws-conformance

Conformance test suite and compatibility matrix for ABB Robot Web Services clients: RWS 1.0 (IRC5 / RobotWare 6) and RWS 2.0 (OmniCore / RobotWare 7 and 8).

> **Status: early development.** Nothing to install yet. Watch or star the repo to follow progress.

## What it does

Point it at a real or virtual controller and get a table:

- Which RobotWare versions work, endpoint by endpoint
- Which endpoints fail or behave differently between versions
- Which known quirks apply to your controller

The suite comes from the test bed behind [abb-rws-client](https://github.com/ichbinmeraj/abb-rws-client). Published results will form a public compatibility matrix for ABB RWS clients and drivers.

## What it does not do

It does not move the robot. Write tests (signals, RAPID execution, mastership) are opt-in and meant for virtual controllers first.

## Related projects

- [abb-rws-client](https://github.com/ichbinmeraj/abb-rws-client): TypeScript RWS client tested on RobotWare 6, 7 and 8
- [abb-rws-ros2](https://github.com/ichbinmeraj/abb-rws-ros2): ROS 2 supervisory bridge
- [abb-rws-mcp](https://github.com/ichbinmeraj/abb-rws-mcp): MCP server for AI agents
- [abb-rws-vscode](https://github.com/ichbinmeraj/abb-rws-vscode): RAPID Live, VS Code extension for ABB controllers

## Licence

Apache-2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE). If you redistribute this work, keep the NOTICE file.

## Disclaimer

Independent open-source project by [Meraj Safari](https://github.com/ichbinmeraj). Not affiliated with, endorsed by or sponsored by ABB. ABB, RobotWare, OmniCore, IRC5 and RobotStudio are trademarks of ABB. See [TRADEMARKS.md](TRADEMARKS.md).
