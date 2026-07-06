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

<img width="1139" height="307" alt="image" src="https://github.com/user-attachments/assets/78f6f3e5-5a8f-424f-8d72-94903e837b60" />


- ![Terminal]

!terminal.png

<img width="1497" height="785" alt="image" src="https://github.com/user-attachments/assets/d33f3607-ba6c-4036-a254-ca1958d1c978" />


- ![Docker app]

<img width="1706" height="997" alt="image" src="https://github.com/user-attachments/assets/77542c5d-d134-4895-8441-41ebf5db7d68" />

- ![Verify Docker (terminal)]

<img width="1910" height="440" alt="image" src="https://github.com/user-attachments/assets/df33fb75-c0d0-4c70-9107-23637b44740b" />


- ![Support center]

<img width="1290" height="760" alt="image" src="https://github.com/user-attachments/assets/735aae4b-9a70-438b-837f-09e731957700" />


- ![Login]

<img width="1911" height="979" alt="image" src="https://github.com/user-attachments/assets/bb7578db-3e4d-4b77-a231-a3de1c510b94" />


- ![Ticket list (dashboard)]

<img width="1131" height="534" alt="image" src="https://github.com/user-attachments/assets/f512fbe4-91f7-4b5f-85e6-48cdc6be6805" />

- ![Ticket system]

<img width="1379" height="618" alt="image" src="https://github.com/user-attachments/assets/f54b85e2-e277-442c-a837-5c189a00e44d" />


- ![Creating ticket]

<img width="797" height="993" alt="image" src="https://github.com/user-attachments/assets/cae005bc-891d-4385-9d0a-083f7352d84f" />


- ![Ticket created]

<img width="813" height="551" alt="image" src="https://github.com/user-attachments/assets/93881183-c8cf-421f-a775-e0df9d15a231" />


- ![Ticket claimed]

<img width="979" height="949" alt="image" src="https://github.com/user-attachments/assets/3338a5c0-3c20-4c72-a324-121750e551ef" />


- ![Ticket details]

<img width="974" height="611" alt="image" src="https://github.com/user-attachments/assets/490462fc-d498-4972-94e8-ae43df3a6cf2" />

- ![Ticket details (view)]

<img width="974" height="611" alt="image" src="https://github.com/user-attachments/assets/66c03409-8df3-41a1-af92-29640d214dd5" />


- ![Ticket reply]

<img width="960" height="900" alt="image" src="https://github.com/user-attachments/assets/1209604b-f863-4c0f-ba2a-0feb3391610d" />


- ![Transfer support]

<img width="769" height="418" alt="image" src="https://github.com/user-attachments/assets/9e4c9ac0-ad04-45b2-bf61-430c3df31caf" />


- ![Closing ticket]

<img width="939" height="444" alt="image" src="https://github.com/user-attachments/assets/1274c5fc-94bb-44d6-a8a3-71a9f96218b5" />


- ![Ticket closed (success)]

<img width="998" height="494" alt="image" src="https://github.com/user-attachments/assets/0d804bd9-82eb-4515-b2a8-4052a9958e6c" />


---

## 🧰 Folder Structure

- `docker-compose.yml`
- `.env.example` (rename to `.env`)
- `README.md`
- `screenshots/` (drop in your .pngs for GitHub)
- fix: corrected admin login credentials
