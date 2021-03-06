# Hash Schema
Event fields used to define metadata about hashes.

## Data Fields
|Standard Name|Type|Description|Sample Value|
|---|---|---|---|
| hash_imphash|string|IMPHASH hash of the image/binary/file. [For more info](https://www.fireeye.com/blog/threat-research/2014/01/tracking-malware-import-hashing.html)|2505BD03D7BD285E50CE89CEC02B333B|
| hash_ja3|string|[JA3]([https://github.com/salesforce/ja3) is a method for creating SSL/TLS client fingerprints that should be easy to produce on any platform and can be easily shared for threat intelligence.|6734f37431670b3ab4292b8f60f29984|
| hash_ja3s|string|[JA3S]([https://github.com/salesforce/ja3) is JA3 for the Server side of the SSL/TLS communication and fingerprints how servers respond to particular clients.|4192c0a946c5bd9b544b4656d9f624a4|
|hash_md5|string|MD5 hash of the image/binary/file|6A255BEBF3DBCD13585538ED47DBAFD7|
|hash_sha1|string|SHA1 hash of the image/binary/file|B0BF5AC2E81BBF597FAD5F349FEEB32CAC449FA2|
|hash_sha256|string|SHA256 hash of the image/binary/file|4668BB2223FFB983A5F1273B9E3D9FA2C5CE4A0F1FB18CA5C1B285762020073C|
|hash_sha512|string|SHA512 hash of the image/binary/file|1AD1D79F85D8F6A50EA282F63898D652661DAA0C1FD361C22647CABC98A70E8CBCE83200D579D10DD0A3D46BE9496DCDFDDF28B0C5E9709343B032A8796FBECB|
| hash_software_checksum|string|The hash, to verify, software/package||
| hash_ssdeep|string|SSDeep fuzzy hashing. " program for computing context triggered piecewise hashes (CTPH). Also called fuzzy hashes, CTPH can match inputs that have homologies. Such inputs have sequences of identical bytes in the same order, although bytes in between these sequences may be different in both content and length."|234:v7XINhXznVJ8CC1rBXdo0zekXUd3CdPJxB7mNmDZkUKMKZQbFTiKKAZTy:ShT8C+fuioHq1KEFoAU|
