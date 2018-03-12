A fork of ERC20 standard example based on https://ethereum.org/token

Changes:
- use Compiler 0.4.21
- change tokenRecipient type from interface to contract to dismiss warning
- add 'emit' to Event
- extend implementation parameter to make easier to deploy
- add parameter decimal to setPrice, so it can be set to lower unit
- add contract convertDecimal to convert any transaction in Decimal
- duplicate transactional function with capability of decimal
- add withdrawn function to move contract balance to owner
- add contractBalance function to check contract balance