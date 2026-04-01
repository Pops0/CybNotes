
**SQL Injection Mitigations**
Input validation is an important part of mitigating SQL injection attacks. The best mitigation for SQL injection vulnerabilities is to use immutable queries, such as the following:
- Static queries
- Parameterized queries
- Stored procedures (if they do not generate dynamic SQL)
Immutable queries do not contain data that could get interpreted. In some cases, they process the data as a single entity that is bound to a column without interpretation.

**TIP** OWASP has a great resource that explains the SQL mitigations in detail; see [[SQL_Injection_Prevention_Cheat_Sheet]]
