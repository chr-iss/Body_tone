# Body Tone Gym MVP System

A simple, affordable digital system to replace Body Tone Gym's paper forms and spreadsheets.  
The system uses **QR codes** to check members in and track their payments, helping the gym stop lost revenue at the door.

---

## 🚀 Features

- **Digital Member Sign-Up**  
  Staff can register new members via a simple web form. Each member gets a unique QR code (downloadable/printable).

- **QR Code Check-In**  
  Members scan their QR code on a tablet at the gym entrance.

  - ✅ Green Check → "Welcome!" (access granted, membership active)
  - ❌ Red X → "Membership Expired. Please see front desk."

- **Payment Tracking**  
  Staff can manually mark a member as "paid" (cash/EFT).  
  Automatic blocking occurs if payments are overdue by **7+ days**.

- **Offline Mode**  
  Check-ins are stored locally if internet is down and sync automatically once it’s restored.



## 🛠️ Tech & Tools

- Tablet or PC already available at the gym
- QR code generation for member IDs
- Simple database for members & payments
- Free/open-source software stack (to keep costs down)



## 🎯 Goal

To provide a **core, low-cost system** that:

- Ensures only paid members gain access
- Reduces admin workload
- Proves the concept before expanding into advanced features

---

## 📦 Installation & Setup (Draft)

1. Clone this repository:
   ```bash
   git clone https://github.com/AyandaLuthuli/bodytone-gym-mvp.git
   cd bodytone-gym-mvp
   ```
