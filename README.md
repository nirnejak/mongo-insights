# SQL Integrations Tool

A tool for building integrations between SQL database and other services.

**Features**

- SQL Code Editor(with Auto-completion)
- Data in Tabular Form
- Graphs and Charts
- Saved Queries
- Export to CSV
- Export to JSON
- Users and Invites
- Integrations - Zapier, IFTTT, Google Sheets, Airtable etc.

---

## Available Scripts

> Note: Need to configure `.env` file to use local server

**Install Dependencies**

```bash
npm install
```

**Setup Pre-commit**

```bash
npm run prepare
```

**Start Development Server**

```bash
npm run develop
```

**Build for Production**

```bash
npm run build
```

**Start Production Server**

```bash
npm start
```

---

## Docker Config

**Build Image**

```bash
docker build
```

**Run Image**

```bash
docker run -p 5000:5000 <image-id>
```
