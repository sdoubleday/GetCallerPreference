This module allows you to impose the preference variables (such as $VerbosePreference) from the parent scope on the function or script that runs Get-CallerPreference. Normally, PowerShell functions responds to the Global preference variable, which means nested code does not respond to -Verbose as helpfully as one might like.

This repo directly repackages the good work of David Wyatt from here: https://gallery.technet.microsoft.com/scriptcenter/Inherit-Preference-82343b9d
