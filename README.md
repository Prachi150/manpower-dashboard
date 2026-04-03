# manpower-dashboard

A simple decision-support dashboard to help team managers understand workload distribution and take action — redistribute work or consider hiring.

## 🔗 Live Demo
https://manpower-dashboard-ruddy.vercel.app/

## 🎯 Problem
Managers often see overloaded or underutilized team members but still need to manually figure out:
- Can work be redistributed?
- Do we actually need to hire?

This dashboard focuses on answering **what to do next**, not just showing data.

## ⚙️ Key Features
- Team utilization overview (allocated vs capacity)
- Clear classification: Overloaded, Healthy, Underutilized, Idle
- Rebalancing panel to identify who can offload and who can absorb work
- Task type awareness (Flexible vs Priority) to guide redistribution decisions
- Simulated redistribution logic to validate if workload balancing is possible

## 🧠 Assumptions
- 40 hours/week capacity per person
- Utilization is based on allocated hours (planning view)
- Role compatibility is assumed (not enforced)
- Only flexible tasks can be redistributed

## 🚧 Limitations
- No live data integration (static/mock data)
- No role-based matching logic
- No historical trends

## 🚀 Future Improvements
- Integration with Jira/Linear for real-time data
- Role-aware task redistribution
- Weekly trend tracking
- Context annotations (leave, transitions)
- Slack-based weekly summary

## 👩‍💻 Author
Prachi Joshi
