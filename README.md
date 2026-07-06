# 🛠️ osTicket Helpdesk Ticketing System (Docker Lab)

This project is a fully deployed IT Help Desk ticketing system using osTicket and Docker, designed to simulate real-world technical support operations.

- ✅ Full osTicket deployment (Dockerized: MySQL + osTicket)
- ✅ Admin and support user setup for ticket management
- ✅ Realistic sample tickets (VPN, Wi-Fi, permissions, performance issues)
- ✅ Ticket lifecycle simulation (create → assign → resolve → close)
- ✅ IT support workflow practice (Tier 1 troubleshooting & escalation)
- ✅ Ready for portfolio and GitHub demonstration

---

## 🚀 Quick Start

1. Rename `.env.example` to `.env`
2. Run:
   ```bash
   docker-compose up -d
   ```
3. Visit:  
   - End User Portal → [http://localhost:8080](http://localhost:8080)  
   - Admin Panel → [http://localhost:8080/scp](http://localhost:8080/scp)  
   - Login → `ostadmin / Admin1`

---

## 🎫 Practice Tickets

These tickets are great to recreate manually to simulate helpdesk workflows:

### Ticket 1: Wi-Fi Connectivity Issue  
**From:** Sarah Williams 
**Subject:** Laptop keeps disconnecting from Wi-Fi 
**Priority:** High 
**Resolution:** Reset network adapter, forgot and reconnected to Wi-Fi network, connection stabilized and user confirmed issue resolved

### Ticket 2: Shared Drive Access Issue 
**From:** David Martinez 
**Subject:** Cannot access shared folder on network drive  
**Priority:** High  
**Resolution:** Verified permissions, re-added user to correct security group, access restored and user confirmed folder is now accessible

### Ticket 3: Computer Running Slow  
**From:** Jessica Taylor 
**Subject:** PC is very slow during startup and use  
**Priority:** Low  
**Resolution:** Cleared temporary files, removed unnecessary startup programs, rebooted system and performance improved significantly

---

## 📸 Screenshots

> Add your own screenshots to the `screenshots/` folder for portfolio use.

- ![WSL app]

<img width="1769" height="1117" alt="image" src="https://github.com/user-attachments/assets/ad4878e1-cd1a-4b14-b034-6c204a8a4890" />


- ![Ubuntu running (terminal)]

!ubunturunninginterm.png

- ![Terminal]

!terminal.png

- ![Docker app]

!dockerapp.png

- ![Verify Docker (terminal)]

!verifydockerterminalcomplete.png

- ![Support center]

!supportcenter.png

- ![Login]

!osTicket.png

- ![Ticket list (dashboard)]

!osticketdashboard.png

- ![Ticket on dashboard]

!ticketondashboard.png

- ![Ticketing system]

!ticketingsystem.png

- ![Creating ticket]

!creatingticket.png

- ![Ticket created]

!ticketcreated.png

- ![Ticket claimed]

!ticketclaimed.png

- ![Ticket details]

!ticketdisplay.png

- ![Ticket details (view)]

!ticketdisplay1.png

- ![Ticket reply]

!ticketreply.png

- ![Transfer support]

!transfersupport.png

- ![Closing ticket]

!closingticket.png

- ![Ticket closed (success)]

!closeticketsuccessed.png

---

## 🧰 Folder Structure

- `docker-compose.yml`
- `.env.example` (rename to `.env`)
- `README.md`
- `screenshots/` (drop in your .pngs for GitHub)
- fix: corrected admin login credentials
