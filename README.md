
# 🕵️‍♂️ IPRecon - IP Intelligence Tool for Cybercell Agra

IPRecon is a Python-based IP intelligence tool designed to help cybersecurity teams gather detailed metadata about IP addresses using the [IPinfo.io API](https://ipinfo.io/). It features a sleek Tkinter GUI, supports concurrent data fetching, and exports structured data into a CSV file for analysis and reporting.

---

## 🚀 Features

- 📍 Fetches location, ISP, company, and abuse information for each IP
- ⚡ Fast processing using multithreading (concurrent futures)
- 💾 Saves data to CSV with clean formatting
- 🧠 Detects privacy flags: VPN, proxy, Tor, hosting, and more
- 🖥️ User-friendly GUI with dark mode style

---

## 🛠️ Installation

### Requirements

- Python 3.7+
- [IPinfo.io API Token](https://ipinfo.io/account/token)

### Install Dependencies

You can install the required packages using pip:

```bash
pip install requests
```

> No additional dependencies required for `tkinter` as it comes built-in with most Python distributions.

---

## 🧩 Usage

1. **Clone the repository**

```bash
git clone https://github.com/your-username/IPRecon.git
cd IPRecon
```

2. **Run the tool**

```bash
python iprecon.py
```

3. **Enter your IPinfo token and paste IP addresses (one per line)** into the text field.

4. **Click “Start Processing”**, choose where to save the CSV file, and let the tool do the rest!

---

## 📂 Output Format

The output CSV includes:
- IP, Hostname, City, Region, Country
- Location (lat, long), Organization, Postal, Timezone
- ASN Info (ASN, Name, Route, Domain, Type)
- Company Info (Name, Domain, Type)
- Privacy Flags (VPN, Proxy, Tor, Relay, Hosting)
- Abuse Contact Info (Name, Email, Phone, Network, Address, Country)

---

## 📸 Screenshot

> _You can add a screenshot of the GUI interface here for better visual appeal_

---

## 🤝 Contributors

- Developed by **Kartikeyan Singh Tomar** 
- Special thanks to [IPinfo.io](https://ipinfo.io/) for their reliable API services.

---

## 💡 Future Enhancements

- Add export to Excel format
- Support bulk import of IPs from text/CSV
- Visual analytics dashboard integration

---



