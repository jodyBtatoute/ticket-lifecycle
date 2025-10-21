<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [Video: How to create, work, and resolves tickets within osTicket](https://www.dailymotion.com/video/x9sd8n0)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

The **Lifecycle Stages of osTicket** describe how a **support ticket** moves from creation to closure within the osTicket helpdesk system. Understanding these stages helps support teams manage and track issues efficiently.

Here’s a breakdown of the **typical osTicket lifecycle stages**:

---

### **1. Ticket Creation**
<img width="2496" height="1664" alt="image" src="https://github.com/user-attachments/assets/bd3f1433-7799-4556-94ef-89e9c6c62447" />

**Description:**
A new ticket is created when a user submits a support request.

**How it happens:**

* A customer submits a ticket via:

  * Web form (Client Portal)
  * Email (auto-converted to a ticket)
  * API or manual staff creation
* The system assigns a **unique Ticket ID** and records the user’s details and issue.

**Status:**
🟢 *New*

**Key Actions:**

* Auto-response sent to user.
* Ticket routed to the appropriate department or help topic.

---

### **2. Ticket Assignment**


**Description:**
The ticket is assigned to a specific **agent** or **team** for handling.

**Status:**
🟡 *Open* (being worked on)

**Key Actions:**

* Staff reviews the ticket details.
* Ticket priority (Low, Normal, High, Emergency) may be set.
* Internal notes or responses can be added.

---

### **3. Ticket Response and Communication**
<img width="2496" height="1664" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/d1debce0-c099-4930-94e7-16a19407ed6c" />

**Description:**
The assigned agent communicates with the user to resolve the issue.

**Status:**
🟡 *Open / In Progress*

**Key Actions:**

* Agent replies to the ticket via the osTicket interface.
* The system logs all correspondence.
* User can respond back; ticket remains open until resolved.
* Internal collaboration can occur via **internal notes**.

---

### **4. Ticket Resolution**

**Description:**
The agent provides a solution, and the issue is considered resolved.

**Status:**
🟠 *Resolved / Pending Closure*

**Key Actions:**

* Agent updates the ticket with the resolution.
* Optionally, a confirmation request is sent to the user.
* If no further action is needed, the agent can close the ticket.

---

### **5. Ticket Closure**
<img width="2496" height="1664" alt="image" src="https://github.com/user-attachments/assets/71955d36-55b1-40da-a6cb-57a10980baad" />

**Description:**
The ticket is formally closed, meaning the issue is completed or no longer active.

**Status:**
🔴 *Closed*

**Key Actions:**

* Ticket becomes read-only (cannot be modified further).
* User can still view the ticket via the portal.
* Ticket data is retained for reports, audits, and future reference.

---

### **6. (Optional) Reopening or Archiving**

**Description:**
If the user replies after closure, depending on settings, the ticket may be **reopened**.

**Status:**
🔁 *Reopened* (returns to *Open* state)

**Key Actions:**

* Reopened tickets are reassigned for further action.
* Closed tickets may eventually be **archived** based on retention policies.

---

### **Lifecycle Summary Diagram:**

```
New  →  Open  →  In Progress  →  Resolved  →  Closed  →  (Optional) Reopened
```

---

### **Additional Notes:**

* osTicket supports **SLA (Service Level Agreements)**, which can affect how long tickets stay in each stage.
* Automations (like triggers, filters, and canned responses) can move tickets automatically through stages.
* Custom statuses can be added to fit organizational workflows.

---

Would you like me to make a **visual flowchart** of the osTicket lifecycle stages? It can help illustrate how tickets move between states.
