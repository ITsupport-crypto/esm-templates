# Formal ESM Reply Templates

> **Usage Guide**
> - Replace all `<placeholders>` with the relevant information before sending.
> - These templates are designed for use within a ticketing tool (ESM/ServiceHub).
> - Do not include subject lines or signature blocks — these are handled by the system.

---

## Template Index

| #  | Template Name                                      | When to Use                          |
|----|----------------------------------------------------|--------------------------------------|
| 1  | Request for Clarification                          | Missing info from user               |
| 2  | Customer Contacted – Pending Action                | Post call/Teams follow-up            |
| 3  | Meeting Request                                    | Complex request needing discussion   |
| 4  | Request Fulfillment                                | Request completed                    |
| 5  | Incident Resolution                                | Incident fixed                       |
| 6  | Canceled – Wrong Service Offering                  | Wrong ticket category                |
| 7  | Task Assignment to Support Team                    | Inter-team handoff                   |
| 8  | Initial Acknowledgment                             | Ticket just received                 |
| 9  | On Hold – Pending Third Party                      | Blocked by external team             |
| 10 | Ticket Escalation                                  | Escalated to higher team             |
| 11 | Duplicate Ticket                                   | Same request already open            |
| 12 | Request Rejected                                   | Out of policy / not feasible         |
| 13 | Closure Warning                                    | No user response                     |
| 14 | Known Issue – Workaround Available                 | Issue already identified             |
| 15 | Request Partially Fulfilled                        | Only part of request done            |
| 16 | Planned Maintenance / Scheduled Downtime           | Scheduled downtime                   |
| 17 | Request Reopened – Further Investigation Required  | Closed ticket needs revisit          |

---

## Placeholders Reference

| Placeholder                      | Description                                      |
|----------------------------------|--------------------------------------------------|
| `<User>`                         | Customer's name                                  |
| `<Date>`                         | Date of call, meeting, or maintenance            |
| `<X business days>`              | Configurable SLA / response period               |
| `<System/Portal Name>`           | Target application or portal name                |
| `<Correct Service Offering Name>`| Right service category                           |
| `<Correct Request Type>`         | Right request type                               |
| `<Team/Recipient Name>`          | Target support team name                         |
| `<Third Party Team/Vendor>`      | External team or vendor name                     |
| `<Existing Ticket ID>`           | Reference ID of the duplicate ticket             |
| `<Start Time>` / `<End Time>`    | Maintenance window times                         |

---

## Templates

---

### 1 — Request for Clarification – Pending Customer Action

```
Dear <User>,

Thank you for reaching out to us.

In order to proceed with your request, we kindly ask for your support in
providing the following information:

  •  <Required detail 1>
  •  <Required detail 2>
  •  <Required detail 3>

Once we receive the above, we will proceed with your request accordingly.

Thank you for your cooperation.
```

---

### 2 — Customer Contacted (Teams/Call) – Pending Customer Action

```
Dear <User>,

Thank you for your time during our recent <call / Teams meeting> on <Date>.

As discussed, we kindly request your support in providing the following
to allow us to proceed:

  •  <Required detail 1>
  •  <Required detail 2>
  •  <Required detail 3>

Please share the above at your earliest convenience so we can continue
with the required actions without further delay.

Thank you for your cooperation.
```

---

### 3 — Meeting Request – Pending Customer Action

```
Dear <User>,

To ensure we fully understand your requirements and proceed effectively,
we would like to schedule a brief meeting to discuss your request in
further detail.

We kindly ask you to share your availability within the next <X business
days> so we can arrange a suitable time accordingly.

We look forward to your response.

Thank you for your cooperation.
```

---

### 4 — Request Completion / Fulfillment

```
Dear <User>,

We are pleased to inform you that your request has been successfully fulfilled.

Action Taken:
<Briefly describe what was done — e.g., "Access has been granted to the
requested system with the appropriate role assigned.">

Should you require any additional support, please do not hesitate to
contact us.

Thank you for your cooperation.
```

---

### 5 — Incident Resolution

```
Dear <User>,

We are pleased to inform you that your reported incident has been
successfully resolved.

Resolution Summary:
<Briefly describe the resolution — e.g., "The issue was caused by
[root cause] and has been addressed by [action taken].">

We kindly request that you review the resolution and confirm your
acceptance within 3 business days by accepting the resolution in
<System/Portal Name>. If no response is received within this period,
the ticket will be automatically marked as resolved and closed.

Should you encounter any related issues or require further assistance,
please do not hesitate to reach out.

Thank you for your cooperation.
```

---

### 6 — Canceled Request – Incorrect Service Offering or Request Type

```
Dear <User>,

After reviewing your request, we have determined that it falls outside
the scope of the current service offering.

Accordingly, this ticket has been closed with the status: Closed – Incomplete.

To ensure your request is handled promptly, we kindly ask you to submit
a new ticket under the correct service category:

  •  Service Offering: <Correct Service Offering Name>
  •  Request Type:     <Correct Request Type>

Should you need any assistance with submitting the new request, please
do not hesitate to contact us.

We appreciate your understanding and cooperation.
```

---

### 7 — Task Assignment to Support Team (Inter-Team Notification)

```
Dear <Team/Recipient Name>,

Please be informed that this request has been re-assigned to your
respective support group for action.

Action Required:
<Describe what the team needs to do — e.g., "Kindly create an AD HOC
task for the relevant support team if additional assistance is required.">

For reference, please consult the relevant process documentation or
training materials shared by the team.

Should you require any further clarification, please do not hesitate
to reach out.

Thank you for your cooperation.
```

---

### 8 — Initial Acknowledgment – Request Received

```
Dear <User>,

Thank you for contacting us.

We confirm that your request has been received and is currently being
reviewed by our team. We will get back to you shortly with an update.

Should you have any additional information to add, please feel free
to update this ticket.

Thank you for your cooperation.
```

---

### 9 — Request On Hold – Pending Third Party

```
Dear <User>,

We would like to inform you that your request is currently on hold,
pending a response/action from <Third Party Team/Vendor/Department>.

We are actively following up on this matter and will provide you with
an update as soon as we receive a response.

We appreciate your patience and understanding.

Thank you for your cooperation.
```

---

### 10 — Ticket Escalation Notification

```
Dear <User>,

We would like to inform you that your request has been escalated to
<Team/Level> for further review and action, in order to ensure it
is handled appropriately.

We will continue to monitor the progress and keep you updated
accordingly.

We appreciate your patience.

Thank you for your cooperation.
```

---

### 11 — Duplicate Ticket – Already Existing Request

```
Dear <User>,

After reviewing your request, we have identified that a ticket for
the same issue/request is already open under <Existing Ticket ID>.

Accordingly, this ticket will be closed to avoid duplication, and
your request will continue to be handled under the existing ticket.

Please refer to <Existing Ticket ID> for any further updates.

We appreciate your understanding and cooperation.
```

---

### 12 — Request Rejected – Not Feasible / Out of Policy

```
Dear <User>,

Thank you for your request.

After careful review, we regret to inform you that we are unable to
fulfill this request due to the following reason:

  •  <Clearly state the reason — e.g., "This action is restricted
     by the current security policy." / "The requested access level
     exceeds the approved entitlements for your role.">

Accordingly, this ticket will be closed with the status: Closed – Rejected.

If you believe this decision requires further review, please escalate
through the appropriate approval channel.

We appreciate your understanding.
```

---

### 13 — Pending Customer Response – Closure Warning

```
Dear <User>,

This is a reminder that we are still awaiting your response regarding
the information/confirmation requested in our previous update.

Please note that if no response is received within <X business days>,
this ticket will be automatically closed.

Should you still require assistance, please respond to this ticket at
your earliest convenience.

Thank you for your cooperation.
```

---

### 14 — Known Issue – Workaround Available

```
Dear <User>,

Thank you for reporting this issue.

We would like to inform you that this is a known issue currently under
investigation by the relevant team. In the meantime, the following
workaround is available:

  •  <Describe the workaround steps clearly>

We will notify you once a permanent fix has been implemented.

We apologize for any inconvenience caused and appreciate your patience.

Thank you for your cooperation.
```

---

### 15 — Request Partially Fulfilled

```
Dear <User>,

We would like to inform you that your request has been partially fulfilled.

Completed Actions:
  •  <Action 1 completed>
  •  <Action 2 completed>

Pending Actions:
  •  <Action still pending — e.g., "Pending approval from the
     relevant authority." / "Awaiting completion by <Team Name>.">

We will provide a further update once the remaining actions have
been addressed.

Thank you for your patience and cooperation.
```

---

### 16 — Planned Maintenance / Scheduled Downtime Notification

```
Dear <User>,

We would like to inform you that a planned maintenance window has
been scheduled for <System/Service Name> on <Date> from <Start Time>
to <End Time>.

During this period, <briefly describe the impact — e.g., "the service
will be temporarily unavailable.">.

Your request will be processed once the maintenance window is completed.

We apologize for any inconvenience and appreciate your understanding.

Thank you for your cooperation.
```

---

### 17 — Request Reopened – Further Investigation Required

```
Dear <User>,

Thank you for your follow-up.

We have reopened your request for further investigation based on the
additional information provided.

Our team will review the matter and provide you with an update as
soon as possible.

We appreciate your patience.

Thank you for your cooperation.
```

---

*Last updated: 2026-04-28*
