# PyCodeBot
Python Code github integration bot.

This integration bot is for checking python code and restructured text documentarion files for PEP8 issues.

It is a sortcut into running flake8 and pycodestyle without needing to set it up in CI's like Travis and AppVeyor.

When this integration bot is complete it should replace setups that use CI's for the check and remove a lot of files in the process and simplifies it all down to a webhook.

Also unlike those CI's that would fail because of pep8 or other issues like isort that do not comment to the pull request that fail because of it this is planned to do just that notifying the user almost immediately about the issue they have in their latest commit.

## Development

Currently since I am not exactly sure on making an github integration like this it would have to be an learning process.

## Extending

This could eventually be extended to check for future PEP issues (or for PEP7 on C Code). But for now PEP8 and the other things like import sorting is planned.

