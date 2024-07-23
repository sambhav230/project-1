Public Variables:

The contract has public variables to store the details about the coin:
Tname: The name of the token.
TAbbrivation: The abbreviation of the token.
Supply: The total supply of the token.
Mapping of Addresses to Balances:

The contract uses a mapping to keep track of balances associated with each address. This is done using mapping(address => uint).
Mint Function:

The mint function takes two parameters: an address and a value.
It increases the total supply by the specified value.
It also increases the balance of the provided address by that value.
Burn Function:

The burn function works opposite to the mint function.
It takes two parameters: an address and a value.
It deducts the value from the total supply.
It also deducts the value from the balance of the provided address.
Conditionals in Burn Function:

The burn function includes conditionals to ensure the balance of the address is greater than or equal to the amount to be burned. This prevents burning more tokens than the address holds.
