# TYPO3 extension `func`

This extension brings the "Web->Functions" module to the TYPO3
backend. It acts as a container for other extensions to hook in, the
two core extensions [wizard_crpages](https://packagist.org/packages/typo3/cms-wizard-crpages)
and [wizard_sortpages](https://packagist.org/packages/typo3/cms-wizard-sortpages)
known from TYPO3 core version 8 and previous versions did that. With the
integration of these two extensions into the backend pages context menus, the
"func" extension became obsolete and has been removed from the core.

The extension is now available as composer package and TER extension
as backwards compatible layer if other extensions use the container
functionality of "func".

|                  | URL                                                          |
|------------------|--------------------------------------------------------------|
| **Repository:**  | https://github.com/FriendsOfTYPO3/func                       |
| **Read online:** | https://docs.typo3.org/p/friendsoftypo3/cms-func/main/en-us/ |
| **TER:**         | https://extensions.typo3.org/extension/func/                 |
