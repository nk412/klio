Changelog
=========

0.2.2 (UNRELEASED)
------------------

Fixed
*****

* fix config bug that skipped preprocessing (overrides, templates) of dict parsed from YAML
* ``KlioWriteToAvro`` has been enabled as an output event type (previously missing).

Changed
*******

* moved ``IndentListDumper`` to ``klio_core`` config utils.


0.2.1 (2020-12-03)
------------------

* Common klio-cli and exec options moved to klio-core
* ``with_klio_config`` moved from klio-cli to klio-core

0.2.0 (2020-10-02)
------------------

Initial public release!
