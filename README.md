# Bic(SWIFT) from Iban
Generate BIC(SWIFT) from IBAN bank account number


Validating an IBAN 
------------------
```javascript
  var BICFromIBAN = require ("BICFromIBAN");
  
  // Return true if the IBAN is a correct banck account 
  var isValid = BICFromIBAN.validateIBAN("DZ4000400174401001050486");
```

Get a BIC(SWIFT) bank code from IBAN account number 
---------------------------------------------------
```javascript
  var BICFromIBAN = require ("BICFromIBAN");
  
  // Return a String with a Bic code
  var BIC = BICFromIBAN.getBIC("DZ4000400174401001050486");
```

The bank information is https://github.com/PeterNotenboom/SwiftCodes

## Technical debt links

[Barometer IT](https://wolterskluwer.barometerit.com/b/system/041800002496)
[SonarQube Project](https://sonarqube.cloud-dev.wolterskluwer.eu/dashboard?id=clearfacts%3ABic-from-IBAN)
[Checkmarx Project](https://test4tools.cchaxcess.com/CxWebClient/ProjectStateSummary.aspx?projectid=17867)