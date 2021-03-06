# Event ID 4707: A trust to a domain was removed.
###### Version: 0

## Description
This event generates when a domain trust was removed.

## Data Dictionary
|Standard Name|Field Name|Type|Description|Sample Value|
|---|---|---|---|---|
|trust_domain|DomainName|UnicodeString|the name of removed trusted domain.|`FABRIKAM`|
|trust_sid|DomainSid|SID|SID of removed trusted domain.|`S-1-5-21-2226861337-2836268956-2433141405`|
|user_sid|SubjectUserSid|SID|SID of account that requested the "remove domain trust" operation.|`S-1-5-21-3457937927-2839227994-823803824-1104`|
|user_name|SubjectUserName|UnicodeString|the name of the account that requested the "remove domain trust" operation.|`dadmin`|
|user_domain|SubjectDomainName|UnicodeString|subject's domain or computer name.|`CONTOSO`|
|user_logon_id|SubjectLogonId|HexInt64|hexadecimal value that can help you correlate this event with recent events that might contain the same Logon ID, for example, "4624: An account was successfully logged on."|`0x3e99d6`|

## References
* [MS Source](https://github.com/MicrosoftDocs/windows-itpro-docs/blob/public/windows/security/threat-protection/auditing/event-4707.md)
* [MS Security Auditing Category - Policy Change](https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/advanced-security-audit-policy-settings#policy-change)
* [MS Security Auditing Sub-category - Audit Authentication Policy Change](https://github.com/MicrosoftDocs/windows-itpro-docs/tree/master/windows/security/threat-protection/auditing/audit-authentication-policy-change.md)

## Tags
* etw_level_Informational
* etw_task_task_0
* Policy Change
* Audit Authentication Policy Change