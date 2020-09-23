# Intro
This module adds auto complete for winget.

# Install Module

Install the module from the PSGallery.

    Install-Module kmt.winget.autocomplete

# Usage

Add this line to your powershell `$profile`.

    Import-Module kmt.winget.autocomplete

# Context
I wrote this to simplify configuring autocomplete for winget. If you don't want to download this module, see the [winget documentation](https://github.com/microsoft/winget-cli/blob/master/doc/Completion.md) for a larger command you can place in the `$profile` to do the same thing. This module just a wrapper for that other command.
