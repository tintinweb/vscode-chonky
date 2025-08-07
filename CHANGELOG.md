# Change Log

All notable changes to the "chonky" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## v0.6.6
- Fixed .chonky directory discovery for files in root (.chonky/xxx.workflow.md)
- Simplified validation logic to support flexible file placement patterns

## v0.6.5
- Simplified workspace filtering: Use repositoryId:"workspace" to filter primers/workflows to workspace .chonky directories only
- Updated tool descriptions: Clear guidance for workspace vs external repository filtering
- Improved workspace discovery: Streamlined .chonky directory scanning without complex workspace:name patterns
- Enhanced UX: Simplified filtering makes it easier for users to find workspace-specific security resources
- Workspace integration: Auto-discovery of .chonky folders in workspace for project-specific security resources
- Pattern-based resource discovery: Flexible file extension matching (*.primer.md, *.workflow.md, tools/*.yml)
- Improved discovery output: Repository information display for better filtering and context

## v0.6.4
- Comprehensive GitHub Wiki
- Updated primer search logic for better discoverability in small collections

## v0.6.3
- Updated Readme

## v0.6.2
- Moved chonky-semgrep, chonky-solidity-external-calls, and chonky-solidity-erc-compliance to BASE availability
- Added chonky-chat-decorator: AI-powered interactive code decoration through chat
- Added chonky-editor-diagnostics: Read and create VS Code diagnostics with precise code snippet validation
- Enhanced base tier offerings with advanced security analysis tools

## v0.6.1
- Multi-Repo primer support

## v0.6.0

- Initial release