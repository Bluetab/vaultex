# Changelog

## 0.12.5
* When reading from Vault, do not allow a nil errors or warnings value to hijack the response

## 0.12.4
* Updating ex_doc dependency to enable mix docs and in turn, mix hex.publish

## 0.12.3
* poison should be listed as runtime dependency

## 0.12.2
* Ensure warnings are exposed in the response

## 0.12.1
* Update to use Poison 4.x

## 0.12.0
* AWS IAM authentication support

## 0.11.1
* Add VAULT_CACERT support

## 0.11.0
* Add support for renewing lease

## 0.10.0
* Add support for read dynamic secrets

## 0.9.0
* Added delete key feature

## 0.8.0
* Authentication methods are more generic

## 0.7.0
* Add support for certificate files in request
* Add timeout to client
* Upgrade httpoison to 1.0

## 0.6.2
* Add support for VAULT_SSL_VERIFY environment variable - this brings VaultEx in line with equivalent Vault libraries in Ruby, Node, etc

## 0.6.1
* Use atom instead of sting for econnrefused
* On error don't stringify the error reason - this adds too much noise

## 0.6.0
* Added support for token authentication
* Misc documentation changes

## 0.5.1
* Fixing deployment error

## 0.5.0
* Fix missing VERSION file

## 0.4.0
* Add support for LDAP authentication
* Fix minor bugs in unit tests and Dockerfile

## 0.3.4
* Adding eliver tool for easier version bumping
