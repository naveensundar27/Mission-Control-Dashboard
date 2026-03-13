# 🚀 Mission Control Dashboard

A real-time testing orchestration dashboard for managing multi-agent testing workflows.

## Live Demo

🌐 **View the dashboard:** https://yourusername.github.io/mission-control-dashboard

## Features

- **Real-time Agent Monitoring** - Track status of all testing agents
- **Project Management** - View current project and testing phase
- **Activity Log** - Timeline of all agent actions
- **Responsive Design** - Works on desktop and mobile

## Agents

| Agent | Role | Status |
|-------|------|--------|
| 🎯 Echo | Orchestrator | Online |
| 📮 Postman | API Testing | Idle |
| 🌐 Web Tester | Web UI Testing | Idle |
| ⚡ Load Runner | Performance Testing | Offline |

## Local Development

To connect this dashboard to your local Mission Control instance:

1. Update the JavaScript to fetch from your local API:
```javascript
// Replace demoData with actual API calls
const response = await fetch('http://localhost:3000/api/status');
const data = await response.json();
```

2. Enable CORS on your local instance

3. Refresh the page to see live data

## Project Structure

```
.
├── index.html          # Main dashboard
└── README.md          # This file
```

## Technologies

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- GitHub Pages for hosting

## License

MIT