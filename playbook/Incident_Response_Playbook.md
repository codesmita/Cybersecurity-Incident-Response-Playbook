# Incident Response Playbook

## 1. Purpose

The main purpose of this playbook is to develop a structured process for handling cybersecurity incidents. In this case, the playbook will allow the team to detect, investigate, contain, eradicate, and recover from security incidents.

In this case, the selected scenario for the playbook is an account compromise as a result of phishing.

## 2. Incident Scenario

An employee receives a suspicious email from a reputable institution. This email is usually attached with a hyperlink to a fake login page. When the employee clicks on the link and enters his credentials, his account becomes compromised by an unauthorized individual.

The detection of the incident can be done through reporting of the email or an unexpected login.

## 3. Incident Response Life Cycle

### 3.1 Preparation

- Procedures for incident response should be available.
- Identification of incident response team and its roles.
- Availability of security and monitoring tools.
- Availability of backup and recovery procedures.
- Procedures for communication and escalation.

### 3.2 Detection and Identification

- Receive and document the incident report.
- Analyze the phishing email.
- Evaluate authentication and security logs.
- Identify abnormal logins.
- Check the login timing, location, and device.
- Establish if the behavior is a security incident.

### 3.3 Triage

- Categorize the severity of the incident.
- Establish the potential impact.
- Identify the compromised account and systems.
- Identify whether any other accounts or systems are compromised.
- Prioritize the incident according to its severity.
- Escalate the incident when necessary.

### 3.4 Containment

- Limit or terminate the access of the compromised account when necessary.
- Reset the compromised password.
- Terminate the suspicious logins.
- Invalidate the authentication token.
- Utilize multi-factor authentication.
- Block malicious phishing websites.
- Verify whether any other employees have also received the same email.
- Save all pertinent information of the account and logs.

### 3.5 Eradication

- Reinitialize compromised credentials.
- Eliminate unauthorized account modifications.
- Investigate forwarding rules or other applications connected to the account.
- Review authentication mechanism.
- Search for additional accounts that might be compromised.
- Fix the vulnerability that caused the incident.
- Analyze the root cause of the phishing incident.

### 3.6 Recovery

- Recover the affected account following the containment and eradication processes.
- Validate that password was changed appropriately.
- Confirm that security controls are working effectively.
- Verify that unauthorized sessions and authentication tokens were invalidated.
- Monitor the account for any signs of abnormal activity.
- Validate that normal functionality has been restored.
- Notify the impacted user when necessary.

### 3.7 Lessons Learned

- Record the incident and response efforts.
- Analyze evidence gathered in the course of the investigation.
- Determine the root cause of the incident.
- Document the lessons learned.
- Determine how security controls and procedures can be improved.
- Revise the incident response process if necessary.

## 4. Collection of Evidence

The relevant evidence related to the phishing attack might include:

- Phishing email
- Email headers
- Links or attachments in the email
- Authentication logs
- Account logs
- Time and location of logging in
- Information about the device
- Security alerts
- Screenshots of relevant evidence

The evidence needs to be collected prior to making any unnecessary changes to the affected accounts or systems. The evidence's source, collection time, and personnel involved in its collection need to be documented as well.

## 5. Severity Rating

| Severity | Description | Example |
|---|---|---|
| Low | Limited impact with no evidence of significant unauthorized access. | Suspicious phishing email reported but credentials were not entered. |
| Medium | Possible unauthorized access with limited impact. | Credentials were entered and suspicious login activity was detected. |
| High | Confirmed unauthorized access to sensitive resources. | A compromised account was used to access sensitive files or services. |
| Critical | Major compromise affecting critical systems, sensitive data, or multiple accounts. | The compromise spreads to privileged accounts or critical organizational systems. |

## 6. Communication and Escalation

- Communicate using authentic information.
- Do not reveal confidential incident information.
- Keep records of major communication activities.
- Inform relevant parties about the major changes in the incident status.
- Consider escalating the incident when its level of severity rises.
- Provide proper communication between the incident response team and users.
- Document important decisions and activities made during the incident response process.

## 7. Incident Response Checklist

### Preparation

- [ ] Ensure incident response procedures are available.
- [ ] Identify responsible response personnel.
- [ ] Ensure required monitoring and security tools are available.
- [ ] Maintain appropriate backup and recovery procedures.
- [ ] Establish communication and escalation procedures.

### Detection and Identification

- [ ] Receive and record the incident report.
- [ ] Identify the type of suspected incident.
- [ ] Collect initial information about the incident.
- [ ] Review relevant security alerts and logs.
- [ ] Identify the affected account, system, or resource.
- [ ] Determine whether the activity represents a security incident.

### Triage

- [ ] Assess the severity of the incident.
- [ ] Identify the potential impact.
- [ ] Determine the scope of the incident.
- [ ] Check whether additional accounts or systems may be affected.
- [ ] Prioritize the required response actions.
- [ ] Escalate when required.

### Containment

- [ ] Restrict or disable the affected account when required.
- [ ] Terminate suspicious active sessions.
- [ ] Revoke authentication tokens.
- [ ] Block identified malicious resources.
- [ ] Check whether other users received the same phishing email.
- [ ] Monitor the affected account for further suspicious activity.

### Eradication

- [ ] Reset compromised credentials.
- [ ] Remove unauthorized account changes.
- [ ] Check for suspicious forwarding rules or connected applications.
- [ ] Review authentication methods.
- [ ] Check for additional compromised accounts.
- [ ] Address the weakness that allowed the incident to occur.

### Recovery

- [ ] Restore the affected account after containment and eradication.
- [ ] Verify security controls are functioning correctly.
- [ ] Confirm unauthorized sessions have been terminated.
- [ ] Monitor the affected account after recovery.
- [ ] Confirm normal operations have been restored.
- [ ] Inform the affected user when appropriate.

### Post-Incident Review

- [ ] Document the incident and response actions.
- [ ] Review the evidence collected.
- [ ] Identify the root cause.
- [ ] Record lessons learned.
- [ ] Identify improvements to security controls.
- [ ] Update the incident response process if required.

## 8. Selected Scenario Response

For the selected account compromise resulting from phishing, the initial severity may be classified as **Medium** if the credentials have been entered and there has been unusual login activity.

The severity may be elevated if the investigation reveals access to sensitive data, privileged accounts, or additional systems.

## 9. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Incident Response Team | Coordinates the overall incident response process and investigation. |
| Security Analyst | Reviews alerts, logs, and evidence to identify suspicious activity. |
| IT Team | Performs technical actions such as account restriction, password reset, and system recovery. |
| Incident Response Lead | Coordinates response activities and makes decisions regarding escalation and priority. |
| Management | Provides authorization, resources, and organizational support. |
| Affected User | Reports suspicious activity and follows instructions provided by the response team. |

## 10. Conclusion

An incident response plan enables an organization to respond to a cyber attack in a systematic way. The response team can identify the incident, minimize its impact, collect evidence, recover systems, and enhance security measures in the aftermath of the incident.
