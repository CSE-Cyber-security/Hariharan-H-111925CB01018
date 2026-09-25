Manual Test Cases
Add Asset → Expect "Asset added successfully."
Display Assets → Expect formatted inventory + total count.
Search Asset (A102) → Expect details of Web-Server.
Update Asset (A103) → Change SecurityStatus to Secure.
Delete Asset (A101) → Expect "Asset deleted successfully."
Security Summary → Expect counts of each risk/status.
Validation → Invalid IP, RiskLevel, SecurityStatus should raise ValueError.
