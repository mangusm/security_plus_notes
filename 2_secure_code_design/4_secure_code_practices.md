# Secure Code Practices

## Input Validation
* Whitelisting - specifies allowable input
* Blacklisting - specifies disallowed input
* Input validiation should always be done on the server

## Paramaterized queries

## Authentication and session management issues
* Hashing - transforms a password to a unique value that can't be reversed
* Adds a random value to passwords prior to hashing
* Encryption in transit (TLS)

## Output Encoding
* replaces dangerous characters
* HTML encoding
* URL encoding
* use trusted library, don't do it yourself

## Error and Exception Handling
* 

## Code signing
* Developer obtains a certificate
* The developer creates a digitial signature for the code using the private key associated with the certificate.
* User downloads the code
* OS uses the certificate's public key to validate the signature
* OS verfiies that the signature's hash matches the code
* OS verifies that the developer is trusted

## Database Security
* Database Normal Forms
    * Seperate tables for different sets of related data
    * Primary key for every table
    * Records may not have multivalued fields
    * Records in a table must have the same number of fields
    * Every non-key field must be a fact about the entire key
    * No non-key field may be a fact about another non-key field
* Encryption
* Obfuscation
* Logs of admin users

## Data Deidentification
* Remove obvious identifiers of individuals

## Data obfuscation
* Hashing, Salting, Tokenization, Masking