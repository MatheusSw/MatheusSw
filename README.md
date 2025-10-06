# Hey-o! 👋 I'm Matheus

I'm currently 26 years old and I'm a hands-on software engineer with industry experience developing desktop applications. I have comprehensive knowledge about Agile Methodologies and programming architectures. I once was a Desktop application lover, but boy-oh-boy the web development environment got me good! But I still have thorough knowledge of .NET and .NET Core.

# 🚀 Projects
## [Nauru](https://github.com/MatheusSw/nauru)

#### Description
An event-driven, low-latency **FX order scheduling system** that enables clients to schedule automatic execution of FX spot orders when the market (treasury) rate reaches a client-visible target.

**The architecture is designed to:**
- Match treasury ticks to scheduled orders in real-time
- Claim and execute orders with **exactly-once** semantics
- Scale to **millions of scheduled orders** while maintaining bounded latency
- Provide event-driven processing for high throughput

#### Technologies used
- **Infrastructure**: AWS with Terraform (Lambda, DynamoDB, SQS, SNS, ElastiCache Redis, VPC)
- **Architecture**: Event-driven serverless design with low-latency Redis caching
- **Focus**: Distributed systems, exactly-once processing, high-scale event matching

---

## [Willow](https://github.com/MatheusSw/willow)

#### Description
A self-hosted, open source **feature flag service** built with **.NET 9**, designed for teams who want full control over their release toggles without relying on SaaS vendors. Deployable on AWS via Terraform and Kubernetes Helm charts.

**Key features include:**
- **Remote evaluation API** for checking feature enablement
- **Admin API** for managing organizations, projects, environments, and feature rules
- **SignalR WebSocket hub** for real-time toggle change notifications
- **PostgreSQL** as source of truth with **Redis** for low-latency caching

#### Technologies used
- **Back-end**: .NET 9, ASP.NET Core, SignalR for real-time communication
- **Infrastructure**: AWS (EKS, RDS PostgreSQL, ElastiCache Redis), deployed via Terraform and Helm
- **Architecture**: Modular, event-oriented, API-first design
- **Focus**: Self-hosting, enterprise features, distributed caching

---

## 📦 Other Projects

### [dotnet-clean-arch](https://github.com/MatheusSw/dotnet-clean-arch)

Implementation of the **CLEAN architecture** in a production-like C# solution integrating with a weather HTTP API. Includes **Prometheus** and **Grafana** for monitoring and observability. Built with ASP.NET Core, Serilog, and Prometheus.NET.

### [chess-bot](https://github.com/MatheusSw/chess-bot)

A simple chess bot using **Lichess** and **Stockfish** engine, built with Python.

### [Ticketier](https://github.com/MatheusSw/Ticketier)

A modern support ticket handling system built with **Laravel** (back-end) and **React with Tailwind CSS** (front-end). Designed to offer a faster, more intuitive experience than traditional internal ticketing systems.

### [Fruit Recognizer](https://github.com/MatheusSw/Fruit-Recognizer)

An AI fruit recognition system built with **TensorFlow** and **Python** using the Fruits-360 Dataset. Explores LSTM and GRU layers for image classification.

---

## 📫 How to reach me

[LinkedIn](https://www.linkedin.com/in/matheussouzacs/)
