A fork ERC20 standard based on https://ethereum.org/token

Changes:
- use Compiler 0.4.21
- change tokenRecipient type from interface to contract to dismiss warning
- add 'emit' to Event
- change this type to address. this.balance -> address(this).balance
- add implementation parameter to make easier to deploy