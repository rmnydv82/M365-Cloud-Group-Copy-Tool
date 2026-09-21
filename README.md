# Microsoft 365 Cloud Group Copy Tool

A PowerShell-based tool designed to copy Microsoft 365 cloud group
memberships from one user account to another user account.

## Features

- Copy cloud group memberships between Microsoft 365 users
- Easy-to-use interface
- Useful during new user onboarding
- Reduces manual group assignment
- Displays operation results and errors

## Requirements

- Windows 10/11
- PowerShell
- Microsoft 365 administrator account with User administrator Rights
- Required Microsoft PowerShell modules
- Required Microsoft Graph Permission
- Internet connection

## Installation

Download the latest release from the GitHub Releases section.

Alternatively, download the PowerShell script directly from this repository.

## Usage

1. Download the tool.
2. Open PowerShell.
3. Run the PowerShell script.
4. Authenticate using your Microsoft 365 administrator account via graph.
5. Select or enter the source user.
6. Select or enter the destination user.
7. Review and select the group memberships.
8. Start the copy operation.

## Important

Always review the groups before copying memberships to another user.
The administrator running the tool must have appropriate permissions
in Microsoft 365.

## Disclaimer

This tool is provided "as is" without warranty. Test the tool in a
non-production environment before using it in production.

## License

Licensed under the MIT License.
