# CEX_Tagging
This Repo is intended to document the tagging of CEXs, On/Offramps, Casinos, and other custodians on the Algorand Network.

**Identifying a CEX**
  * Notes on txns headed to a deposit address, include the name of the CEX
  * An address is opted in to assets which the CEX has publically listed
  * A listing announcement from a CEX matches the when an address becomes active
  * A freeze in activity corresponding to a CEX security incident
  * A transaction links an address to a previously tagged CEX address
    * First txn came from existing CEX
    * Last txn from existing CEX goes to address
    * Large percent of funds transferred from existing CEX
    * In flows and outflows directly to CEX, not through deposit addresses
    * Exclusive flows with CEX
    * Deposit addresses for previous CEX also fund new address
