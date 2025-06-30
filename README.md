# LINE Chatbot – Payslip Text Extraction with Gemini

A robust n8n-based chatbot for LINE, leveraging Google Gemini AI to extract structured data from user-submitted payslips (images or PDF). Stores results in Google Sheets, provides admin features, and includes user authentication, error handling, and more.

---

## Features
- LINE Messaging API webhook integration
- Gemini AI for advanced OCR and information extraction
- Google Sheets logging and CSV export
- Admin broadcast and error notifications
- User feedback and rating system
- Authentication/whitelisting for users
- Multilingual support (optional)
- PDF and image file support

---

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/berkanireda/line-gemini-payslip-bot.git
    cd line-gemini-payslip-bot
    ```

2. **Import n8n Workflows:**
    - Import the workflows from `/n8n_workflows/` into your n8n instance.

3. **Set up Environment:**
    - Configure environment variables and credentials for LINE, Google Sheets, Gemini, etc.

4. **Install Optional Scripts:**
    ```bash
    npm install
    ```

5. **Read Documentation:**
    - See [`docs/architecture.md`](docs/architecture.md) for full architecture and node details.

---

## Repository Structure

- `/n8n_workflows/` – Main n8n workflows (JSON)
- `/scripts/` – Utility scripts (e.g., data export, batch admin tools)
- `/docs/` – Extended documentation
- `.github/workflows/ci.yml` – Optional: Continuous Integration
- `README.md` – This file

---

## License

MIT. See [LICENSE](LICENSE) for details.

---

## Contributing

PRs welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) if present.

---

## Credits

Built with [n8n.io](https://n8n.io/), [Google Gemini](https://ai.google.dev/), and [LINE Messaging API](https://developers.line.biz/en/docs/messaging-api/overview/).
