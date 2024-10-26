
# Echo 📅🤖
> *Virtual Assistant for Scheduling Events via WhatsApp with Automated Notifications*

### Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributions](#contributions)
- [License](#license)

---

### Description
**Echo** is an AI-powered agent designed to manage scheduling requests via WhatsApp. It checks availability, creates calendar events, and automatically sends confirmation messages.

### Features
✅ Integrates with WhatsApp to receive scheduling requests.

📅 Adds events directly to Google Calendar or Outlook based on availability.

🔔 Notifies users via WhatsApp about confirmed events.

💬 Conducts natural dialogue to capture all necessary information for scheduling.

---

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-organization/echo.git
   cd echo
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure the environment (see more in [Configuration](#configuration)).

---

### Configuration
To configure Echo, create a `.env` file with the following variables:

```plaintext
WHATSAPP_API_KEY=your_whatsapp_api_key
CALENDAR_ID=your_calendar_id
TIMEZONE=America/Sao_Paulo
```

- **WHATSAPP_API_KEY**: API key for WhatsApp access.
- **CALENDAR_ID**: ID of the calendar to add events.
- **TIMEZONE**: Time zone to ensure scheduling accuracy.

---

### Usage
1. Start Echo:
   ```bash
   npm start
   ```

2. Receiving requests:
   - Echo will process scheduling requests sent via WhatsApp and respond with status updates.

3. Calendar events:
   - Events are automatically created in the configured calendar, with notifications sent to the user.

---

### Technologies
- **Node.js**: Runtime environment.
- **WhatsApp API**: Direct connection for receiving and sending messages.
- **Google Calendar API**: Integration with Google Calendar for event scheduling.
- **NLP (Natural Language Processing)**: To interpret scheduling requests on WhatsApp.

---

### Contributions
Contributions are welcome! Please review our [CONTRIBUTING.md](./CONTRIBUTING.md) for more information.

### License
Distributed under the MIT License. See [LICENSE](./LICENSE) for more details.

--- 
