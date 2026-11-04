# 🪖 WASHTAG — Drop Into The Laundry Battlegrounds

![PHP](https://img.shields.io/badge/PHP-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Development-blue?style=for-the-badge)

> 🍗 *"WINNER WINNER — FRESH LAUNDRY DINNER."*

Every match starts with a drop. WASHTAG is the drop you take into the laundry
arena — a modern, **web-based laundry management system** built as a
**BCA Final Year Mini Project** to streamline bookings, order tracking and
user management for both customers and administrators.

Built with **PHP, JavaScript, SCSS and HTML**, it demonstrates the full
spectrum of full-stack web development — from authentication and database
integration to a responsive UI and full admin controls.

---

## 🎯 Drop Zone — What Is WASHTAG?

A complete laundry workflow in one arena:

| Player | Role |
|---|---|
| 🧍 Customer | Registers, books services, tracks live order status |
| 🛡️ Admin | Manages users, orders and updates through the dashboard |
| 🧾 System | Records bookings, notifications and order history in MySQL |

No rubber bullets in this run — every feature listed below is a real,
working system component, not a concept art.

---

## 🎒 Gear You Gain (Features)

✅ User Registration & Login — secure entry plane  
✅ Service Booking & Order Tracking — live on the minimap  
✅ Admin Dashboard — full control tower for users & orders  
✅ Notification System — supply-drop alerts for order updates  
✅ Secure Authentication & Session Handling — vault-grade  
✅ Responsive Front-End — optimized for every loadout  
✅ Clean SCSS/JS UI — no inventory clutter  

---

## 🧰 Loadout (Tech Stack)

| Slot | Item | Tech |
|---|---|---|
| 🔫 Primary | Server-side logic | PHP |
| 🥤 Sidearm | Front-end behavior | JavaScript |
| ⛑️ Helmet | Styling & UI kit | SCSS / CSS |
| 💉 Heal Kit | Data vault | MySQL |
| 🎒 Backpack | Local server | XAMPP |
| 💣 Impact | Markup | HTML |
| 🎯 Optics | Editor | VS Code |
| 🧭 Navigation | Source control | Git |

---

## 📜 Pre-Requisition Drop (Requirements)

- PHP **>= 7.4**
- MySQL **>= 5.7**
- A local server: **XAMPP / LAMP / MAMP** (or equivalent)

---

## 🪂 How To Drop (Installation — XAMPP)

1. **Clone or download** the repository:

   ```bash
   git clone https://github.com/Razer0x1/WASHTAG.git
   ```

2. **Move the project folder** to your XAMPP `htdocs` directory:

   ```
   C:\xampp\htdocs\WASHTAG
   ```

3. **Start XAMPP** and run the **Apache** and **MySQL** modules.

4. **Set up the database:**

   * Open [phpMyAdmin](http://localhost/phpmyadmin)
   * Create a new database (e.g., `washtag_db`)
   * Import the provided `database.sql` file

5. **Update database credentials:**

   * Open `config.php` (or `.env`, if used)
   * Enter your MySQL username, password and database name
   * Defaults: user `root`, empty password

6. **Land in the arena:**

   👉 <http://localhost/WASHTAG>

---

## 🎮 Match Gameplay (Usage)

1. Open the app at **http://localhost/WASHTAG**
2. **Register or log in** as a User or Admin
3. **Book laundry services**, track orders and manage your profile
4. Admins manage orders, users and feedback from the dashboard

Stay inside the blue zone: booking early in the match secures priority washes.

---

## 🤝 Recruit New Winners (Contributing)

Developed as part of the **BCA academic curriculum** — contributions,
suggestions and improvements are welcome:

1. **Fork** the repository
2. **Create** your feature branch: `feature/your-feature`
3. **Commit** and push your changes
4. **Open a Pull Request** with a clear description

---

## 👑 Squad Credits

- **Developer:** [Bhargav Haldipur (@Razer0x1)](https://github.com/Razer0x1)
- **Project:** WASHTAG — Laundry Management System (BCA Final Year Mini Project)
- **Supervisor:** Satish Naik
- **Institution:** KBCA, Karwar

---

## 📜 License

Licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

- **GitHub:** [Razer0x1](https://github.com/Razer0x1)
- **Email:** bhargav.haldipur2004@gmail.com

---

## 🧯 Blue Zone First Aid (Troubleshooting)

- **Apache won't start?** Another service (usually Skype/IIS) is squatting on port `80` — edit `httpd.conf` (`Listen 80`) or stop the squatter.
- **Database errors on first run?** Import `database.sql` *before* opening the app, and match `config.php` credentials to your MySQL user.
- **Blank pages / white screens?** Enable `display_errors` in `php.ini` while developing; then check the `logs/apache` folder.
- **Styles look unstyled?** The SCSS must be compiled to CSS once (`npm run scss` or your editor plugin) before serving.

---

> 🧺 *As the plane passes over Pochinki, someone is still folding shirts in the
> blue zone. Deploy early. Book early. Dinner belongs to the laundromat squad.*

---

🧼 **WASHTAG** — *Simplify your laundry, amplify your time.*
